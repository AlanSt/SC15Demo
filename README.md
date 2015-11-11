# SC15Demo

##Deploying individual VMs at scale
This template creates a large number of individual VMs (up to 500).  Individual VMs can use almost all of the customization features within Azure.  This is designed to show how to add this to your code, there is no jump box or inbound NAT rule for accessing the VMs.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAlanSt%2Fazure-quickstart-templates%2Fmaster%2Flarge-cluster%2Fazuredeploy_nonat.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

[Template here](https://github.com/AlanSt/azure-quickstart-templates/tree/master/large-cluster)

##Deploying multiple VM Scale Sets
This template creates multiple scale sets, each of which supports up to 100 VMs.  Scale sets are designed for a set of identical VMs and easier to manage, but do not have all of the customization options available to individual VMs.  This is designed to show how to add this to your code, there is no jump box or inbound NAT rule for accessing the VMs.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F301-multi-vmss-linux%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

[Template here](https://github.com/Azure/azure-quickstart-templates/tree/master/301-multi-vmss-linux)

##Deploying a Torque cluster
<a href="http://www.adaptivecomputing.com/products/open-source/torque/">Torque</a> (Terascale Open-source Resource and QUEue Manager) is an open source distributed resource manager providing control over batch jobs and distributed compute nodes. This templates will deploy a Torque cluster in Azure based on CentOS 6.6. See <a href="http://docs.adaptivecomputing.com/torque/5-1-0/help.htm">Adaptive Computing</a> website for more detail.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Ftorque-cluster%2Fazuredeploy.json" target="_blank">
   <img alt="Deploy to Azure" src="http://azuredeploy.net/deploybutton.png"/>
</a>

Simply SSH to the master node and do a srun! The DNS name is _**dnsName**_._**location**_.cloudapp.azure.com, for example, yidingtorque.westus.cloudapp.azure.com.

[Template here](https://github.com/Azure/azure-quickstart-templates/tree/master/torque-cluster)

##Deploying a SLURM cluster

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fslurm%2Fazuredeploy.json" target="_blank">
   <img alt="Deploy to Azure" src="http://azuredeploy.net/deploybutton.png"/>
</a>

Simply SSH to the master node and do a srun! The DNS name is _**dnsName**_._**location**_.cloudapp.azure.com, for example, yidingslurm.westus.cloudapp.azure.com.

[Template here](https://github.com/YidingZhou/azure-quickstart-templates/tree/master/slurm)
