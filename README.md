# Azure Lighthouse Managed Offer (Managed Security)
Stores the Azure Lighthouose Managed Security Offer template that can be used to provide delegation to customer environments from objects within the Softcat Partner account

The following permissions are included in this lighthouse offer.

# Delegated Permissions

| User/Group                                | Delegated Permission                                |
| ----------------------------------------- | --------------------------------------------------- |
| ALH - Managed Security L1 Analyst         | Log Analytics Reader                               |
| ALH - Managed Security L1 Analyst         | Microsoft Sentinel Reader                           |
| ALH - Managed Security L2 Analyst         | Log Analytics Reader                               |
| ALH - Managed Security L2 Analyst         | Microsoft Sentinel Reader                           |
| ALH - Managed Security L3 Analyst         | Log Analytics Reader                               |
| ALH - Managed Security L3 Analyst         | Microsoft Sentinel Reader                           |
| ALH - Managed Security Security Engineer  | Log Analytics Reader                               |
| ALH - Managed Security Security Engineer  | Microsoft Sentinel Contributor                      |
| ALH - Managed Security Security Engineer  | Managed Services Registration Assignment Delete Role|

# Deploy to Azure 

Use the below button to deploy this Azure Lighthouse offer to a tenant.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSoftcatMS%2Fazure-lighthouse-managedoffer-security%2Fmain%2Fproduction-security-lighthouse-offer-nopim.json)