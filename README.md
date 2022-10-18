# AzPolicyAsCode

To implement the recommended policies that align to the CAF framework. Deploy the CAF.tf file. This can be achieved by installing terraform.exe from hashicorp. 
Then run 'terraform init' and if you have the management group structure and permissions, run 'terraform plan' and 'terraform apply' to deploy them.

An Azure Policy as Code workflow makes it possible to manage your policy definitions and assignments as code, control the lifecycle of updating those definitions, and automate the validating of compliance results. In this repo, you can learn to use Azure Policy features with GitHub to build a lifecycle process. 

Citations: 

Tutorial on how to implement Azure Policy as Code with GitHub - https://learn.microsoft.com/en-us/azure/governance/policy/tutorials/policy-as-code-github

GitHub Actions for deploying to Azure - https://github.com/Azure/login

Open ID Connect (OIDC) - https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure

CAF - https://github.com/Azure/terraform-azurerm-caf-enterprise-scale

Enterprise policy as code repo - https://github.com/Azure/enterprise-azure-policy-as-code

Azure Enterprise Policy as Code – Azure Landing Zones Integration - https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-enterprise-policy-as-code-azure-landing-zones-integration/ba-p/3642784
