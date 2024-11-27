---
layout: page
title: Describe Transpiler AWS
permalink: /language/reference/dev/tanspiler/aws/
exclude: true
---
<br>The Describe Compiler AWS is an Amazon Web Services Lambda function project. It is built for hosting the Describe Compiler as a microservice, in the form of a lambda function. The project is licensed under the AGPL v3 public license.<br>

The DescribeTranspiler.AWS Visual studio project contains few Amazon lambda functions that we upload to AWS Lambda and configure with HTTP APIs in the ASW API Gateway, in order to host the Describe Markup Language Transpiler as a micro-service, invoke-able from a URL.
The way this works is as follows:

a) User makes a POST request on the HTTP API url.<br>
b) Lambda function is triggered, receiving the data from the POST request.<br>
c) Lambda decodes the base64 body of that request.<br>
d) Lambda reads data from that request body to variables and checks some of it.<br>
e) Lambda uses Arguments class functions to fill up the Datnik class with the before-mentioned data.<br>
f) Lambda calls MainFunctions to do the compilation.<br>
g) MainFunctions.Compile uses the data inside the Datnik to compile the source code.<br>
h) Lambda gets the result and base64 encodes it.<br>
i) Lambda prepares the response object and returns it.<br>
j) HTTP API response is returned.<br>

## Resource Unavailable

<span style="color:gray;">*This section of the documentation is not completed yet*</span><br>

<br>
### Links
[Back](/language/reference/dev/)