# Assignment
ARM template and parameter file to create a resource in Azure as VM

Name: "template.json" and "parameters.json"

Description: The ARM template file will create a ubuntu virtual machine in Azure with specified parameters

How to use ARM Template: Execute the below powershell script to create a VM with parameters as defined below :- 

New-AzureRmResourceGroupDeployment -ResourceGroupName "DikshaRG" -TemplateFile "C:\ARM\template.json" -TemplateParameterFile "C:\ARM\parameters.json" -Force 


