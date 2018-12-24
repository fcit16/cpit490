---
title: "Azure Functions"
date: 2018-12-03T13:12:48+03:00
toc: false
draft: false
---
## Server-less Application Using Microsoft Azure Functions

By Mohammed Qara & Salem Abdulaziz

<div class="col6 center" ><iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRtO48nIKyDr4VbOeUecbPO6Ls9lTWwGcXudlDLZbbE9triEWghXC4N4MlOtxZuSUE2WAhhSCP1s5hQ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe></div>


### Introduction

[Microsoft Azure functions](https://azure.microsoft.com/en-us/services/functions/) is server-less **event-driven**, compute-on-demand experience that extends the existing Azure application platform.

You only pay for the time that code is running on the server, you will be charged based on the number of resources that Azure functions needs and only for as long as it takes your code to execute.



### Features

Azure function support triggering an event based on an activity in an Azure service for example, you can run a specific code based on some log file or you can make a timer and schedule your code to be run on specific timing every week, it maybe backing up your data each hour or so. 



### Getting Started with Azure Function

Before start, you need to know that Microsoft Azure Function operate on windows and Linux environment, for the windows environment it supports

**Windows**

- .NET
- Java
- JavaScript

**Linux**

- .NET

- JavaScript

- Docker containers


In order to develop a server-less application in **Java** you you have to two options, 
1. Use Microsoft [VS Code](https://code.visualstudio.com) 

2. or use any IDE with [Maven](https://maven.apache.org/)

3. Optionally, if you want to test the app locally you need to install 

   1. [Node.js](https://nodejs.org/en/)

   2. [Azure](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)

   3. [Net Core](https://dotnet.microsoft.com/download)

And you need to compile that code locally in your machine and deploy it into your Azure function application.



On the other hand, you can use JavaScript for more easier development, you can choose it to handle http request for example, and it can be edited directly from the cloud, so you don't need Maven or VS code.

To get start using Amazon Function, you can visit Microsoft website to 


