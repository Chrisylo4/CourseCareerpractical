# CourseCareerpractical
Project Title:
Creating a Resource Group and Virtual Machine in Azure & Logging in to that account

Project Summary:
This project demonstrates how to create an Azure Resource Group and a Virtual Machine using the Azure portal

Languages Used:
Azure PowerShell 

Environments Used:
Azure Portal 
Windows 10 or Windows Server 

Technology/Applications/Services Used:
Microsoft Azure 
Azure Resource Manager 
Azure Virtual Machines 



Start off by Logging in to Microsoft Azure on the top right
![image](https://github.com/user-attachments/assets/16afb44b-3f9c-47f0-9213-8a7f249043a6)

First we have to create a resource group. At the top of the page, in the search bar, type out resource group and go ahead and click "Reource Groups"
![image](https://github.com/user-attachments/assets/3e95fec3-07ff-4db4-a4ef-32754b58078b)

Once you are in, you can go ahead and click create down below in the middle or on the top left, click create.
![image](https://github.com/user-attachments/assets/9885bc93-5d68-45da-a631-473007228b7d)

You will need to use whatever subscription you have via your azure account to begin making a resource group or work on must stuff on azure.
Name your Resrouce Group something Unique to what you will be using it for.
And use the region you are currently in
![image](https://github.com/user-attachments/assets/3110c78c-42f0-4455-a92d-08e93fd58aa2)

Once you fill in that information, you can go ahead and click Review + Create at the bottom left of the page
![image](https://github.com/user-attachments/assets/335e0020-a5ac-47f1-ba87-9f0857aa09c7)

Now that we have our Resource Group, we can move on to creating our Virtual Machine.

Once again we are going to use the Search bar at the top and type in Virtual Machine, and go ahead and click "Virtual Machines"
![image](https://github.com/user-attachments/assets/66bf5184-3ce9-4394-8d9e-48da80f5f411)

Once we are in the Virtual Machine Page, go ahead and click create in the middle of the mage or at the top left
![image](https://github.com/user-attachments/assets/5047cc9d-3cbb-47ff-88ec-3996c00d94d8)

We are going to proceed to click Azure Virtual Machine
![image](https://github.com/user-attachments/assets/2e4979ba-9cfa-41d0-a24e-19fac5f94d22)

In the first section of information, we are going to use the Subscription that you have or want to use depending on how many you have.
Use the Resource Group that we just made to create the Virtual Machine.
Give your Virtual Machine Name something Unique as per what you are making it for.
Region once again similar to the area you are in or going to be using it for. (Sometimes there will be more options to your region like EAST US 2, to choose from if EAST US option gives you an error later in creating the virtual machine)
You can start off by clicking Zone 1 in availability zone as most of the time this will work when creating our server.
Image Section all depends on what Windows you want to use, we are going to use Windows 10 pro version
![image](https://github.com/user-attachments/assets/1947e8d3-90a5-4e66-8aca-c9b0a57492d0)

Size Depends on how much workload that you want to run. The size that you choose then determines factors such as processing power, memory, and storage capacity. 
Create a Username and password that you wont forget! (Can type it into a note)
![image](https://github.com/user-attachments/assets/e9c82176-f74f-4840-8087-68121bb0ca08)
After filling in all that information you can proceed to click the create button at the bottom.

Azure will take some time to create the Virtual Machine 
![image](https://github.com/user-attachments/assets/1278c3e1-c3b2-45ed-bdb1-7e7a927cee29)
Once the Virtual Machine has been created, you will go back to the search bar at the top and type in "Virtual Machine" and head back to the Virtual Machine Page where you will now see your created Virtual Machine once it is finished being made.
![image](https://github.com/user-attachments/assets/8edf16a6-3481-40e4-8dc2-68a2d54b50c9)

Go ahead and click on your virtual machine so we can see all the information regarding our VM 
To Log in to your Virtual Machine now, find where it says "Public IP Address" ![image](https://github.com/user-attachments/assets/ec11412c-51ab-4f3a-8ad7-1dda10b981bd)

Go ahead and copy the Ip Address, and we are going to use that Address and input it to Remote Desktop Connection.

Use your search bar at the bottom and type in "Remote Desktop Connection"
![image](https://github.com/user-attachments/assets/05c5a39a-71df-4a66-ba67-ab52a2a70826)
Click Remote Deskstop connection and you should have a small box, Put the Ip Address that we just copied into the Computer Tab and Click Connect
![image](https://github.com/user-attachments/assets/1c3161e3-c4c9-437d-ab33-d9b5a50c0162)

You should have now been taken to another box to input your credentials, which was the Username and Password we input when creating the Virtual Machine, go ahead and type that in
![image](https://github.com/user-attachments/assets/aa023342-1d6f-4cfe-888c-60699607f205)

After clicking Ok, our Virtual Machine will start to load
![image](https://github.com/user-attachments/assets/d11e096a-06e9-4474-800d-4c649e76537f)

And that is how you create a Virtual Machine using Microsoft Azure.




