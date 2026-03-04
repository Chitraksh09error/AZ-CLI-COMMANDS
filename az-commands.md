# AZ-CLI-COMMANDS
This repo contains basic commands which are needed in Azure to create resources

##  Login
```bash
az login
```

## Login using device code
```bash
az login --use-device-code
```

## Create resource group / Delete resource group
```bash
az group create -l regionName -n nameOfResourceGroup
```
```bash
az group delete --name ResourceGroupName
```

## Resource Group list
```bash
az group list
```

## Group Exists
```bash
az group exists -n nameOfGroup
```

## Create a Virtual Machine / start VM / stop VM
```bash
az vm create -n name -g ResourceGroupName --image Ubuntu2204 --vnet-name vname --subnet name --generate-ssh-keys --output json --verbose
```
```bash
az vm start
```
```bash
az vm stop
```

## Create Storage Account / Check whether name already exists 
```bash
az storage account create --name uniquename --resource-group GroupName --location eastus --sku Standard_GRS --kind StorageV2 --allow-blob-public-access false/true
```
```bash
az storage account check-name --name name
```
