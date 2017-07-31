# Sample Cross-Platform .NET Core API

This example demonstrates the cross-platform nature of .NET Core. You can deploy to any system that has the .NET Core 1.1 framework installed, and run to verify the platform. Navigate to [http://localhost:5000/api/values](http://localhost:5000/api/values) to see the OS and timestamp.

Get started with the following steps:

`git clone https://github.com/jeremylikness/what-os`

`cd what-os`

`dotnet restore`

`dotnet run`

Read [this blog post](http://csharperimage.jeremylikness.com/2017/07/build-and-deploy-net-core-web-app-from.html) to see how to deploy a .NET Core app to Linux and read the [introduction to Azure Web App on Linux](https://docs.microsoft.com/en-us/azure/app-service-web/app-service-linux-intro).