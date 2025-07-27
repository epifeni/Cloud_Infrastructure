**My notes for Git**  
git init  
git add -A  
git commit -m 'Added my project'  
git remote add origin git@github.com:sammy/my-new-project.git  

**git push -u -f origin main**

git fetch  
git pull  

**My notes on ARM Templates**   
Example of creating a resouce group (Azure CLI):  
az group create --name tusre-dev-001 --location "Australia East"  

When deploying, specify the resource group name as 'tusre-dev-001' using Azure CLI:  
az deployment group create --resource-group tusre-dev-001 --template-file template.json  

New-AzResourceGroupDeployment -Name myfirsttemplate -ResourceGroupName tusre-dev-001 -TemplateFile .\template.json  


Get-AzResourceGroup  

--> Pushing updates to README.md: 
git add README.md 
git commit -m "Update README.md" 
git push 

--> Using Powershell  
Crating new resource group: New-AzResourceGroup -Name RGS-PowerShell -Locatio "Australia East" 
Connecting to Az Account (Student Account): 
connect-AzAccount -Tenant 63f6c050-c3dc-4b5c-8be3-a3f638941f12 -Subscription eb2746d5-a73e-4c92-87cb-9cfa32c0aeff 

--> Using Cli 
Creating a resource group 
az group create --name RSG-CLI --loation "Australia East" 

Creating a new user: 
az ad user create --display-name CLICreatedUser --password myComplexPassword1234 --user-principal-name tanoj2016.123@Tanoj2021outlook.onmicrosoft.com 

Managing Premium Licencing Features: 
Q. how many licences do you need for the privilege identity management and access reviews: Only need P2 licences for administarators or users that are actively using those tools (i.e. approvers) - everyone else can use a free account

<img width="782" height="398" alt="image" src="https://github.com/user-attachments/assets/7905f92a-3c1a-4576-b3de-73626f35a9f0" /> 





