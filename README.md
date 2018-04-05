Step | description | infrastructure deploy template link | software installation template link
---- | ----------- | ------------- | -----------------------------------
1 | plan deployment | [SAP on Azure Linux Planning guide](https://docs.microsoft.com/en-us/azure/virtual-machines/workloads/sap/planning-guide) | tbd 
2 | create virtual network & jumpbox (if needed) | none | tbd 
3 | create iscsi server for Linux clustering support | tbd | tbd
4 | create highly available NFS |[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://github.com/Azure/azure-quickstart-templates/tree/master/sap-file-server-md) | tbd
5 | create hana virtual machine cluster |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsap-3-tier-marketplace-image-multi-sid-db-md%2Fazuredeploy.json) |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frsponholtz%2FSAP-HANA-ARM-HSR%2Fmaster%2Faddcse.json)|
6 | create ascs virtual machine cluster | tbd | tbd
7 | create netweaver virtual machines | tbd | tbd
8 | create web dispatcher pool | tbd | tbd


