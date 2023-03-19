<p align="center">
<img src="https://i.imgur.com/E016BKW.png" alt="Azure Logo">
</p>

<h1>What is an Azure Resource?</h1>
In Azure, a resource is an entity managed by Azure. Virtual machines, virtual networks, and storage accounts are all examples of Azure resources.

<img src="https://i.imgur.com/GMQjxcL.png" alt="Azure Logo">
</p>

<h2>What is an Azure Resource Group?</h2>
In Azure, a resource is an entity managed by Azure. Virtual machines, virtual networks, and storage accounts are all examples of Azure resources.

<img src="https://i.imgur.com/nRb0d6w.png" alt="Azure Logo">
</p>
Each resource in Azure must belong to a resource group. A resource group is a logical container that associates multiple resources so you can manage them as a single entity—based on lifecycle and security. For example, you can create or delete resources as a group if the resources share a similar lifecycle—such as the resources for an N-tier application. In other words, everything that you create, manage, and deprecate together is associated within a resource group.


To learn more about Azure Resource Group i will recommend you this page https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/get-started/how-azure-resource-manager-works

<h2>How to create an Azure Resource Group?</h2>

* From the **Home** screen you will want to either do a :mag:, look next to **Azure Services**, or under **Navigate**, and click **Resource Groups**.

<img src="https://i.imgur.com/SZh3dZH.png" alt="Azure Logo">
</p>

Click **Create**  

<p>
<img src="https://i.imgur.com/B2Ncz9S.png"/>
</p>
<p> 

For **Subscription**, just leave it alone since we are just creating one in this tutorial. **Resource group** will be named *RG-Lab-01* in this exmaple, but you can name it whatever you like. For **Region**, you can choose the one that you're currently living in. Click **Next**. We don't have to specify **Tags** if you don't want to. Used for organizations to keep track of certian resources. Click **Review + create**
  
<p>
<img src="https://i.imgur.com/F5xLtEq.png"/>
</p>
<p>

Verify **Validation passed** and Click **Create**

<p>
<img src="https://i.imgur.com/MTollLG.png"/>
</p>
<p>

Congrats! You have just created a Resourse Group.
