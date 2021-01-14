---
page_type: sample
languages:
- csharp
products:
- dotnet
- azure
- azure-resource-manager
description: "Azure Stack resource sample for managing resource groups"
urlFragment: hybrid-resources-dotnet-manage-resource-group
---

# Hybrid-Resources-DotNET-Manage-ResourceGroup

Azure Stack resource sample for managing resource groups.

- Create a resource group
- Update a resource group
- Create another resource group
- List resource groups
- Delete a resource group

## Running this sample

To run this sample:

1. Clone the repository using the following command:

    git clone https://github.com/Azure-Samples/hybrid-resources-dotnet-manage-resource-group.git

2. Create an Azure service principal and assign a role to access the subscription. For instructions on creating a service principal in Azure Stack, see [Use Azure PowerShell to create a service principal with a certificate](https://docs.microsoft.com/en-us/azure/azure-stack/azure-stack-create-service-principals). 

3. Set the following required environment variable values:
    * AZURE_ARM_ENDPOINT
    * AZURE_LOCATION
    * AZURE_TENANT_ID
    * AZURE_SP_APP_ID
    * AZURE_SP_APP_SECRET
    * AZURE_SUBSCRIPTION_ID

4. Change directory to sample:
    ```
    cd hybrid-resources-dotnet-manage-resource-group
    ```

5. Run the sample:
    ```
    dotnet restore
    dotnet run
    ```

## More information

[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
