# deploystorageaccount

This repository contains an Azure Resource Manager (ARM) template to deploy a Storage Account.

## Deploy to Azure

Click the button below to deploy the Storage Account to your Azure subscription:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fddesonier%2Fdeploystorageaccount%2Fmain%2Fdeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton" alt="Deploy to Azure">
</a>

## Template Details

The ARM template deploys the following resources:
- **Storage Account** with the following properties:
  - **Type**: `Microsoft.Storage/storageAccounts`
  - **API Version**: `2019-04-01`
  - **SKU**: `Standard_LRS`
  - **Kind**: `StorageV2`