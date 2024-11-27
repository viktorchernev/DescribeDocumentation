---
layout: page
title: AWS - Tech Overview
permalink: /language/how-to-compile/aws/tech-overview/
exclude: true
---
<br>
### 1. Function.cs  

`Function.cs` Contains the `Function` class, which contains our lambda functions. The `APIGatewayProxyRequest` class that goes in those functions is a standard way to get information in the lambda function in C#, for the request used to invoke the function. The `APIGatewayProxyResponse` we output is also standard.<br><br>

### 1.1. Lambda functions  
```
public APIGatewayProxyResponse HTranspile_SingleDmlToSingleJson(APIGatewayProxyRequest request, ILambdaContext context)
public APIGatewayProxyResponse HTranspile_SingleDmlToSingleJsonListiary(APIGatewayProxyRequest request, ILambdaContext context)
public APIGatewayProxyResponse HTranspile_SingleDmlToSingleXml(APIGatewayProxyRequest request, ILambdaContext context)
public APIGatewayProxyResponse HTranspile_SingleDmlToSingleHtml(APIGatewayProxyRequest request, ILambdaContext context)
public APIGatewayProxyResponse HTranspile_SingleDmlToSingleHtmlPlain(APIGatewayProxyRequest request, ILambdaContext context)
```
<br>

### 1.2. APIGatewayProxyResponse generation  
StatusCode is 200 here. The headers we include indicate that we are sending JSON. 
The Body is our JSON - the data we output from the lambda function. 
We get it by converting an `OutputJson` class to JSON, as shown below.

```
var response = new APIGatewayProxyResponse
{
	StatusCode = (int)HttpStatusCode.OK,
	Body = JsonConvert.SerializeObject(outputJson),
	Headers = new Dictionary<string, string> { { "Content-Type", "application/json" }, { "Access-Control-Allow-Origin", "*" } }
};
return response;
```
<br>

### 1.3. OutputJson  
This class represents the result of the execution of one of our lambda functions.
Command - The command we ran - like "parse-file"
Result - A string like "Success"
Logs - the generated log entries from the Transpiler
Output - The transpiled result in a base64 encoded string - we decode it to get our JSON, HTML, XML etc.

```
public class OutputJson
{
	public string? Command { get; set; }

	public string? Result { get; set; }
	public string? Logs { get; set; }
	public string? Output { get; set; }
}
```
<br>


### 2. Folder aws-configs

The `aws-configs` folder contains configuration files for all the different lambda functions in the project, for the AWS toolbox.
The thing is that the AWS tools for Visual Studio offer us a way to publish only one lambda at a time, from within Visual Studio. Within the project containing the lambda function we have a file named `aws-lambda-tools-defaults.json`, (which file has its build action set to none) so when we right click on the project and select `Publish to AWS Lambda...`, the AWS tools extension uses this configuration file to determine what to upload to where. This is why we have a folder full of those configs - when we want to upload a specific function, we simply copy that specific config under the main project and rename it accordingly by removing the prefix (like removing "HTML_PLAIN ").<br><br>


### 3. FunctionsMain.cs

Those are the functions that do the transpilation. 
We currently don't have lambda functions that utilize `CompileMulty` though.

```
internal static string? Compile(string code)
internal static string? CompileMulty(List<KeyValuePair<string, string>> codes)
```
<br>


### 4. Datnik.cs

This static class contains all the data for the current parse job.<br><br>



### 5. FunctionsArguments.cs

This static class contains methods for reading data into the Datnik.<br><br>



### 6. FunctionsMessages.cs

This static class contains all the methods that has to do with logging messages.

<br>
### Links
[Configuring the API Gateway](/language/how-to-compile/aws/api-gateway/)<br> 
[Back](/language/how-to-compile/aws/)