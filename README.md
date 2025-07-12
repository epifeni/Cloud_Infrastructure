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

