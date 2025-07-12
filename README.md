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

Connecting to Az Account: 
connect-AzAccount -Tenant 63f6c050-c3dc-4b5c-8be3-a3f638941f12 -Subscription eb2746d5-a73e-4c92-87cb-9cfa32c0aeff 

Get-AzResourceGroup  

--> Pushing updates to README.md: 
git add README.md 
git commit -m "Update README.md" 
git push 


