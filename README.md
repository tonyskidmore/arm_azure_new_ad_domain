# Create a new Windows VM and create a new AD Forest, Domain and DC

Taken from:  
[Create a new Windows VM and create a new AD Forest, Domain and DC](https://github.com/Azure/azure-quickstart-templates/tree/master/active-directory-new-domain)

This template will deploy a new VM (along with a new VNet and Load Balancer) and will configure it as a Domain Controller and create a new forest and domain.  

Address space  

172.16.0.0/12 VNET network address space

172.16.0.0/25 subnet  

|Subnet     |Mask           |Subnet Size|Host Range                 |Broadcast  |
|-----------|---------------|-----------|---------------------------|-----------|
|172.16.0.0 |255.255.255.240|14         |172.16.0.1  to  172.16.0.14|172.16.0.15|


Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Ftonyskidmore%2Farm_azure_new_ad_domain%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Ftonyskidmore%2Farm_azure_new_ad_domain%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>
