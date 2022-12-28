<p align="center">
<img src="https://i.imgur.com/4wqxHID.png" height="40%" width="60%" alt="Microsoft Azure Logo"/>
</p>

<h1>Microsoft Azure</h1>
Microsoft Azure is a cloud platform that will let you rent space in order to store or process your own data. This guide will demonstrate how to create an Azure account and create a virtual machine.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free Azure credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create Azure Account</h3>


Create an Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account. 
     - You will need to put in your credit card information but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then.
- Finish prompt, click Go to Azure Portal and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


<p align="center">
<img src="https://i.imgur.com/rZNc4Ho.png" height="50%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/pEhVTc1.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Azure portal and resource groups</h3>

Now that the account has been created, let's go over how to navigate the Azure portal. The portal is where you can find all the products/resources and manage your subscriptions. It is a user friendly interface.

The portal is located [here](https://www.portal.azure.com).

<p align="center">
<img src="https://i.imgur.com/8JnxniW.png" height="80%" width="80%" alt="Azure Portal with RG Arrow"/>
</p>

In order to utilize some of the services in Azure, a resource group needs to be created. Resource groups store all resources that you are utilizing in Azure. This example will show how to deploy a Windows 10 virtual machine.

<p align="center">
<img src="https://i.imgur.com/x5P8pDQ.png" height="80%" width="80%" alt="Azure Resource Groups with circle"/>
</p>

When ready, click create resource groups. From there, you will need to name your resource group and select the region. The region will determine which Azure data center will be utilize. (US) West 3 was chosen for this example. Click "Review + Create" once finished

<p align="center">
<img src="https://i.imgur.com/4ZY0Twp.png" height="80%" width="80%" alt="Create Azure Resource Groups"/>
</p>

<h3>Step 3: Create a virtual machine</h3>
Next step is to create a virtual machine. At the portal, click on virtual machine and click create. Once at the create virtual machine menu, follow all the instructions. Make sure to fill out all the areas that have a red asterisk on them (resource group, name, etc.). Don't worry about the other tabs such as disks and networking as they will be prefilled. Make sure you remember the username and password! Once this is all completed, your virtual machine will appear in your resource group. 

<p align="center">
<img src="https://i.imgur.com/XC53r2o.png" height="80%" width="80%" alt="Virtual Machine Menu with arrow"/>
</p>

<p align="center">
<img src="https://i.imgur.com/a0OIYax.png" height="80%" width="80%" alt="Create Virtual Machine"/>
</p>

<h3>Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS</h3>
The final step to this process is accessing the virtual machine using Microsoft Remote Desktop. If you are using macOS (like me), you have to download the application in the App Store. 

<p align="center">
<img src="https://i.imgur.com/pp1yQTE.png" height="80%" width="80%" alt="Microsoft Remote Desktop"/>
</p>

In order to connect to the virtual machine, first you need the public IP address. You can find this on the right hand side of this menu.

<p align="center">
<img src="https://i.imgur.com/gT6F62H.png" height="80%" width="80%" alt="SampleVM menu with arrow and circle"/>
</p>

Once Microsoft Remote Desktop is downloaded, open the application. Click add PC. Copy and paste the public IP address of the virtual machine that was created when prompted. Type in the username and password the click connect. 

<p align="center">
<img src="https://i.imgur.com/WcRdlX3.png" height="80%" width="80%" alt="Microsoft Remote Desktop 1"/>
</p>

<p align="center">
<img src="https://i.imgur.com/4IKJFik.png" height="80%" width="80%" alt="Windows 10 VM"/>
</p>

Congratulations! You have created your first virtual machine within Azure. If you want to save your free $200 credits, make sure you delete ALL resource groups because most of Azure services are pay as you go (unless otherwise stated). Thank you!
