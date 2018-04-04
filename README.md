Step | description | infrastructure deploy template link | software installation template link
---- | ----------- | ------------- | -----------------------------------
1. | plan deployment | | |
1. | create virtual network & jumpbox (if needed) | none | |



1. | create iscsi server for Linux clustering support | 
1. | create hana virtual machine cluster |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsap-3-tier-marketplace-image-converged-md%2Fazuredeploy.json) |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsap-3-tier-marketplace-image-converged-md%2Fazuredeploy.json)|


https://github.com/Azure/azure-quickstart-templates/tree/master/sap-3-tier-marketplace-image-converged-md | 
1. | create ascs virtual machine cluster | |
1. | create netweaver virtual machines | |
1. | create web dispatcher pool | |