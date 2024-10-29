# deploystorageaccount

This repository contains an Azure Resource Manager (ARM) template to deploy a Storage Account.

## Deploy to Azure

Click the button below to deploy the Storage Account to your Azure subscription:

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fddesonier%2Fdeploystorageaccount%2Fmain%2Fdeploy.json)

## Template Details

The ARM template deploys the following resources:
- **Storage Account** with the following properties:
  - **Type**: `Microsoft.Storage/storageAccounts`
  - **API Version**: `2019-04-01`
  - **SKU**: `Standard_LRS`
  - **Kind**: `StorageV2`
  - **Location**: Resource Group's location

## Parameters

- **storageAccountName**: The name of the Storage Account to be created. Default value is `mystorageaccount`.

## Usage

1. Click the "Deploy to Azure" button.
2. Fill in the required parameters.
3. Click "Review + create" and then "Create" to deploy the resources.