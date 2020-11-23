# CCOE-bastion-RG

Deploys Azure bastion host in a subnet and assigns the bastion reader assignment to that resource (hence anyone can get permissions to it)
## Deployment of template 

Executed in the current folder with Powershell, change resource gorup to the resource group in use and parameter file

```bash
New-AzResourceGroupDeployment -Name "1" -ResourceGroupName "bastion-rg" -Mode Incremental -TemplateParameterFile .\azuredeploy.parameters.json -TemplateFile .\azureDeploy.json -Verbose
```

## Outputs
| Name  | Output | UsedFor |
| ------------- | ------------- | ------------- |
|    |    |   |
|   |   |  |



