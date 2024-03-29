---
page_type: sample
languages:
- csharp
products:
- azure
extensions:
  services: App-Service
  platforms: dotnet
---

# Getting started on managing storage connections for Web Apps on Linux using C# #

  Azure App Service basic sample for managing web apps.
  - Create a storage account and upload a couple blobs
  - Create a web app that contains the connection string to the storage account
  - Deploy a Tomcat application that reads from the storage account
  - Clean up


## Running this Sample ##

To run this sample:

Set the environment variable `CLIENT_ID`,`CLIENT_SECRET`,`TENANT_ID`,`SUBSCRIPTION_ID` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-dotnet-manage-storage-connections-for-web-apps-on-linux.git

    cd app-service-dotnet-manage-storage-connections-for-web-apps-on-linux

    dotnet build

    bin\Debug\net452\ManageLinuxWebAppStorageAccountConnection.exe

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.