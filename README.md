# bicep-cloud-init
Sample bicep script to create VM with cloud-init

```
# 1. Modify azuredeploy.parameters.json file

# 2. Modify cloud-init.yml

# 3. create resource group
$ az group create --name ExampleGroup --location "koreacentral"

# 4. deploy azuredeploy.bicep 
$ az deployment group create   --name ExampleDeployment   --resource-group ExampleGroup   --template-file azuredeploy.bicep   --parameters azuredeploy.parameters.json

```


