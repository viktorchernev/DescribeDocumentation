---
layout: page
title: Configuring Api Gateway
permalink: /language/how-to-compile/aws/api-gateway/
exclude: true
---
<br>Those are the steps I have used, in order to give you an idea about how to configure the Lambda and the HTTP API. However, this might not be exactly the case for you - for example AWS might change their interface somewhat in the future, or you might need to configure some additional settings. If something does not work exactly like I have described you'd need to do some tinkering to figure it out. Dealing with AWS can be frustrating, if you are not sufficiently knowledgeable in cloud computing, and are not willing to put in the effort to learn, but it is definitely doable. I find chatGPT extremely helpful with that.<br>

Just a word of caution about AWS - be very careful how you set up your budgets, authentications and throttling, or you might end up owing Amazon a lot of money (few hundred dollars to few hundred-thousand dollars, depending on who and how has abused your account or services).<br><br>

```
Log in to AWS console and go to Lambda.
Click "Create Function".
Select "Author from scratch".
Enter the desired function name that matches the one in the aws-config in visual studio.
For runtime select ".Net 8 (C#/F#/PowerShell)".
For architecture select "x86_64".
Click create function.
Go to visual studio.
Copy the desired lambda function JSON config as explained in 1.2. Folder aws-configs.
Right click on the project and select `Publish to AWS Lambda...`
Choose "Re-deploy to existing" and choose the correct name.

Log in to AWS console and go to API Gateway
Click get started with API Gateway or whatever the screen says to get to the main window for the API Gateway service.
Click "Create API" and select HTTP API - Build.
For Integrations, choose Lambda.
Choose the region your Lambda is published on, choose the lambda function itself, and choose version 2.0 .
Choose a name for your API - I use lowercase hyphen separated, like so "transpile-single-dml-to-single-json".
Click Next.
For method choose POST. 
For Resource path enter "/{proxy+}" - (which is a greedy parameter that will capture any path and send it to our lambda).
Make sure that "Integration target" has the desired lambda function name selected and Click next.
For "Define stages" leave it as is - "$default", Auto-deploy .
Click Next and Create.
Once the API is created, open it, go to "Project > Throttling" and set Burst limit and Rate limit values. 
(I use 5000 as burst and 0.116 as rate, which means that I will have 5000 executions available, but once those are exhausted it will take 12 hours give or take, to replenish them)

You can configure logging under "Monitor"
"Deploy > Stages > $default" to see the invocation URL for your API.
You can configure Authorization under "Develop > Authorization".
You can configure CORS, under "Develop > CORS".
```

<br>
### Links
[Technical overview](/language/how-to-compile/aws/tech-overview/)<br> 
[Back](/language/how-to-compile/aws/)