# Deploying Project 15 from Microsoft Open Platform in 3 steps

This document walks through deployment of Project 15 from Microsoft Open Platform in 3 steps.

1. Click to open Azure Resource Manager (ARM) Template
1. Personalize and configure deployment
1. Run Post Deployment Script

## Requirements

- Azure Subscription  
    If you do not have Azure Subscription, please create an account for free (12 months)  
    <https://azure.microsoft.com/free/>  
    You must be an administrator or an owner of the subscription  
- A PC with Web Browser

## 1. Open ARM Template Deployment

Click **Deploy to Azure** button below  

<a href="https://ms.portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2Fproject15%2Fmaster%2FDeploy%2Fazuredeploy-v2.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2Fmicrosoft%2Fproject15%2Fmaster%2FDeploy%2FazuredeployUI.json" target="_blank"><img src="deploy-to-azure.svg"/></a>

> [!TIP]  
> Right click the button below and select **Open link in new tab** or **Open lin in new window**

> [!NOTE]  
> This deployment will consume about 100 USD per month.  If you would like to deploy for your development, turn on `Development Environment` option to deploy with Free SKUs.  With Free SKUs, quotas and limitations apply.

## Next Step

- [Brief introduction](OpenPlatformPortal.md) of Open Platform Portal
- [Connect a device](ConnectingDevice.md) to the Open Platform web application
- Developers : Learn more technical details of the Open Platform Open Platform Developer Guide : [Architecture Overview](../Developer-Guide/Architecture-Overview.md)

[Project 15 from Microsoft - Open Platform](../README.md)
