# azure-arm-templates
Azure Resource Manager JSON templates

Download the sample and adapt as desired.

For example, to execute in PowerShell (after setting up PowerShell with the Azure tools, and adding your account), you can reference the template file directly. Note the parameters values will be prompted in this case.

New-AzureResourceGroupDeployment -Name <deployment-name> -ResourceGroupName <resource-group-name> -TemplateUri https://raw.githubusercontent.com/katriendg/azure-arm-templates/master/2-ARM_provision_web_SQL_storage_conns.json



