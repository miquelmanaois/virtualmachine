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
<img src="https://i.imgur.com/Cxy8NM7.png" height="50%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/f1eRIx4.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Create Resource Group</h3>

- Go to search bar at the top and search "resource group"
- Select create resource group
- You will then need to name the resource group and select the region 
- Select review + create
    - For the example, we will be using RG-Lab-1 for the name and (US) West 3 for the region

<p align="center">
<img src="https://i.imgur.com/SGY8EwH.png" height="50%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/tSKUJHX.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>

<h3>Step 3: Create a storage Account</h3>

- Go to search bar and search "storage account"
- Select Create storage account
- You will need to select the resource group, the region, and create a name for the storage group
    - For the example we will name the storage group rglab1
    - Use same resource group and region as step 2
- Select review, then create.

<p align="center">
<img src="https://i.imgur.com/Ed9wc2j.png" height="50%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/7ryNBQg.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>


<h3>Step 4: Create Virtual Machine</h3>
     
- Go to search bar and search "virtual machine"
- Select create, then select Azure virtual machine
- You will need to select the resource group, the region, and create a name for the virtual machine
    - For the example we will name the virtual machine virtualmachine
    - Use same resource group and region as step 2/3

<p align="center">
<img src="https://i.imgur.com/doboysy.png" height="65%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yM3IRWC.png" height="65%" width="45%" alt="Azure Free Services"/>
</p>
 



* You will then need to select image and size
    - For image we will use Windows 10 Pro
    - For size, select see all sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use labuser
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/QhE5p74.png" height="60%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/I5yvFc4.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>
 
     

<h3>Step 5: Connect to Virtual Machine</h3>

- First you will need to find the Public IP address of your virtual machine
   - Select the virtual machhine we created in step and the IP address will be on the right hand side 
   - Copy the IP address

<p align="center">
<img src="https://i.imgur.com/nOv1FP1.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open application and click add PC
   - Paste IP address and select Add
   - Double click on the virtual machine and enter username and password from step 4
   - Click continue
   

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


<p align="center">
<img src="https://i.imgur.com/SGY8EwH.png" height="50%" width="45%" alt="Azure Free Account"/> <img src="https://i.imgur.com/tSKUJHX.png" height="50%" width="45%" alt="Azure Free Services"/>
</p>
