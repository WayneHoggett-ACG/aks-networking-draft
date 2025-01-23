# Configure Networking for Azure Kubernetes Service (AKS) (DRAFT)

## Demo: 1.2

To follow along in this demo using the Cloud Playground Sandbox, follow these steps:

1. Start an Azure Sandbox.
1. Log in to the Azure Sandbox using the provided credentials.
1. Click the **Deploy to Azure** button. Make sure the link opens in the Sandbox browser tab.

    [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FWayneHoggett-ACG%2Faks-networking-draft%2Frefs%2Fheads%2Fmain%2F1.2%2Fmain.json)

1. Select the existing **Subscription** and **Resource Group**.
1. Provide the `Application Client ID` and `Secret` from the Sandbox details.
1. Deploy the template.
1. Follow-along with the demo.

## Demo: 1.4 

To follow along in this demo using the Cloud Playground Sandbox, follow these steps:

1. Start an Azure Sandbox.
1. Log in to the Azure Sandbox using the provided credentials.
1. Click the **Deploy to Azure** button. Make sure the link opens in the Sandbox browser tab.

    [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FWayneHoggett-ACG%2Faks-networking-draft%2Frefs%2Fheads%2Fmain%2F1.4%2Fmain.json)

1. Select the existing **Subscription** and **Resource Group**.
1. Provide the `Application Client ID` and `Secret` from the Sandbox details.
1. Deploy the template.
1. Follow-along with the demo.

## Demo: 1.5

1. To follow along with this demonstration you will need your own subscription.
1. Log in to the Azure Portal.
1. Open **Cloud Shell** using **Bash** and set the subscription you'd like to use:

    ```bash
    az account set --subscription "<Subscription ID>"
    ```

1. Create a resource group for the demonstration.

> **Note**: You can change the name of the resource group and location as required. But you must use a region where App Gateway for Containers is available.

    ```bash
    RG=$(az group create --location australiaeast --resource-group rg-appgw-for-containers --query name --output tsv)
    ```

1. Click the **Deploy to Azure** button. Make sure the link opens in the same browser tab as the Azure Portal.

    [![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FWayneHoggett-ACG%2Faks-networking-draft%2Frefs%2Fheads%2Fmain%2F1.5%2Fmain.json)

1. Select your preferred **Subscription** and **Resource Group**.
1. Deploy the template.
1. Follow-along with the demo.
