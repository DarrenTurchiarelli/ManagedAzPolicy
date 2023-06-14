# AzPolicyAsCode

To implement the recommended policies that align to the CAF framework. Deploy the CAF.tf file. This can be achieved by installing terraform.exe from hashicorp. 
Then run 'terraform init' and if you have the management group structure and permissions, run 'terraform plan' and 'terraform apply' to deploy them.

An Azure Policy as Code workflow makes it possible to manage your policy definitions and assignments as code, control the lifecycle of updating those definitions, and automate the validating of compliance results. In this repo, you can learn to use Azure Policy features with GitHub to build a lifecycle process. 

Citations: 

Techcommunity - https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-enterprise-policy-as-code-azure-landing-zones-integration/ba-p/3642784

Policy repo - https://github.com/Azure/enterprise-azure-policy-as-code/tree/main/Scripts/CloudAdoptionFramework

Tutorial on how to implement Azure Policy as Code with GitHub - https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/policy-as-code-github

GitHub Actions for deploying to Azure - https://github.com/Azure/login

Open ID Connect (OIDC) - https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure

CAF - https://github.com/Azure/terraform-azurerm-caf-enterprise-scale

Enterprise policy as code repo - https://github.com/Azure/enterprise-azure-policy-as-code

Azure Enterprise Policy as Code – Azure Landing Zones Integration - https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-enterprise-policy-as-code-azure-landing-zones-integration/ba-p/3642784

## DISCLAIMER
The sample scripts are not supported under any Microsoft standard support program or service. The sample scripts are provided AS IS without warranty of any kind. Microsoft further disclaims all implied warranties including, without limitation, any implied warranties of merchantability or of fitness for a particular purpose. The entire risk arising out of the use or performance of the sample scripts and documentation remains with you. In no event shall Microsoft, its authors, or anyone else involved in the creation, production, or delivery of the scripts be liable for any damages whatsoever (including, without limitation, damages for loss of business profits, business interruption, loss of business information, or other pecuniary loss) arising out of the use of or inability to use the sample scripts or documentation, even if Microsoft has been advised of the possibility of such damages.
