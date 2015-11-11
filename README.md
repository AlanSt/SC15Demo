# SC15Demo
SC 15 Demo Links

##Deploying individual VMs at scale


##Deploying multiple VM Scale Sets




##Deploying a Torque cluster
<a href="http://www.adaptivecomputing.com/products/open-source/torque/">Torque</a> (Terascale Open-source Resource and QUEue Manager) is an open source distributed resource manager providing control over batch jobs and distributed compute nodes. This templates will deploy a Torque cluster in Azure based on CentOS 6.6. See <a href="http://docs.adaptivecomputing.com/torque/5-1-0/help.htm">Adaptive Computing</a> website for more detail.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Ftorque-cluster%2Fazuredeploy.json" target="_blank">
   <img alt="Deploy to Azure" src="http://azuredeploy.net/deploybutton.png"/>
</a>

[Template here](https://github.com/Azure/azure-quickstart-templates/tree/master/torque-cluster)

Simply SSH to the master node and do a srun! The DNS name is _**dnsName**_._**location**_.cloudapp.azure.com, for example, yidingtorque.westus.cloudapp.azure.com.

##Deploying a SLURM cluster



