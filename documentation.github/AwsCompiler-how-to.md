The Describe Compiler AWS is an Amazon Web Services Lambda function project. It is built for hosting the Describe Compiler as a microservice, in the form of a lambda function. The project is licensed under the [AGPL v3](https://www.gnu.org/licenses/agpl-3.0) public license.

The DescribeTranspiler.AWS Visual studio project contains few Amazon lambda functions that we upload to AWS Lambda and configure with HTTP APIs in the ASW API Gateway, in order to host the Describe Markup Language Transpiler as a micro-service, invoke-able from a URL. The way this works is as follows:  
	
a) User makes a POST request on the HTTP API url.  
b) Lambda function is triggered, receiving the data from the POST request.  
c) Lambda decodes the base64 body of that request.  
d) Lambda reads data from that request body to variables and checks some of it.  
e) Lambda uses `Arguments` class functions to fill up the `Datnik` class with the before-mentioned data.  
f) Lambda calls `MainFunctions` to do the compilation.  
g) `MainFunctions.Compile` uses the data inside the `Datnik` to compile the source code.  
h) Lambda gets the result and base64 encodes it.  
i) Lambda prepares the response object and returns it.  
j) HTTP API response is returned.  

[[Configuring the API Gateway | Api-gateway-configuration]]  
[[Technical overview | AWS-technical-overview]]  

### Links
[[Describe Compilation | https://github.com/viktorchernev/DescribeCompiler/wiki/Compiler-how-to]]  
[[Use the CLI version | https://github.com/viktorchernev/DescribeCompiler/wiki/CliCompiler-how-to]]  
[[Use the API version | https://github.com/viktorchernev/DescribeCompiler/wiki/ApiCompiler-how-to]]  
