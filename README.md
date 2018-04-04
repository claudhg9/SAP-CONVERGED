Step | description | infrastructure deploy template link | software installation template link
---- | ----------- | ------------- | -----------------------------------
1. | plan deployment | foo | foo 
1. | create virtual network & jumpbox (if needed) | none | foo 
1. | create iscsi server for Linux clustering support | foo | foo
1. | create highly available NFS | foo | foo
1. | create hana virtual machine cluster |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsap-3-tier-marketplace-image-converged-md%2Fazuredeploy.json) |  [![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fsap-3-tier-marketplace-image-converged-md%2Fazuredeploy.json)|
1. | create ascs virtual machine cluster | foo | foo
1. | create netweaver virtual machines | foo | foo
1. | create web dispatcher pool | foo | foo