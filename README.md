<p align="center">
<img src="https://i.imgur.com/XyR16JJ.jpg" alt="osTicket logo"/>
</p>

<h1>Virtual Machines - Creating & Deployment using Microsoft Azure</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/WQ3rhfs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click  Resource Group
</p>
<br />

<p>
<img src="https://i.imgur.com/juutfKz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click create new Resource Group
</p>
<br />

<p>
<img src="https://i.imgur.com/XU8ueOc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Give your Resource Group a name, and choose your Region (**Note: remember to ensure that your machines are all on the same network), then click review + create.
</p>
<br />

<img src="https://i.imgur.com/7pVTvhT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You should see validation passed after clicking review + create
</p>

<img src="https://i.imgur.com/RpeCt0G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go back into Resource Groups to ensure that the Resource Group you just created in showing up.
</p>

<img src="https://i.imgur.com/ImP529a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Virtual Machines 
</p>

<img src="https://i.imgur.com/v8faFsZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Create Azure Virtual Machine
</p>

<img src="https://i.imgur.com/o8EeRJo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Under Resource Group Select the Resource Group that you just created a few moments ago.
</p>

<img src="https://i.imgur.com/Aq7NtFd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Name your Virtual Machine
Choose the region (**Remember it has to be the same as the Resource Group you created earlier)
Click the drop-down menu next to Security Type and select “Standard”
</p>

<img src="https://i.imgur.com/F2b16Ki.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
For this example, we are setting up the first Virtual Machine using Windows 10
Select Windows 10
</p>

<img src="https://i.imgur.com/oIwwSBq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create an administrator account (Write this down on a notepad you will need this to log into your Virtual Machine)
</p>

<img src="https://i.imgur.com/TB9X1Gl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Ensure that RDP 3389 is selected next to “Select inbound ports” (This will probably already be preselected for you)
</p>

<img src="https://i.imgur.com/vqjqM91.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Make sure this box is checked
</p>

<img src="https://i.imgur.com/LZXCcBz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Check this box to ensure that these are deleted also when you delete everything to ensure that you won’t be accumulating charges.

  Click Create
</p>


<img src="https://i.imgur.com/2d9DQZY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create your second Virtual Machine in Azure
Select the same Resource Group that you created earlier
</p>

<img src="https://i.imgur.com/KKJWwiE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Name your Virtual Machine
Select the same region that you selected for VM1 and the Resource Group you created earlier
For this example select Ubuntu Server instead of Windows 10
</p>

<img src="https://i.imgur.com/tiSkS8f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Create a username and password (Remember them)
</p>

<img src="https://i.imgur.com/sydRDBb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Make sure that your Virtual Network for your second Virtual Machine is on the same network as your first one so they can communicate with each other.
Click Create
</p>

<img src="https://i.imgur.com/Az7jFOq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/GXi7a5S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Double-check both Virtual Machines to make sure that the following are the same:

Virtual Network

Location

Resource Group
</p>

<img src="https://i.imgur.com/cbFYH84.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
If you’re using a MAC download Microsoft Remote Desktop from the Appstore
</p>

<img src="https://i.imgur.com/uaiMkpd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Add PC
</p>

<img src="https://i.imgur.com/ihMXrsm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Enter the Public IP Address from your first Virtual Machine
</p>

<img src="https://i.imgur.com/lvQrWv4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Add in Microsoft Remote Desktop App
</p>

<img src="https://i.imgur.com/GsSQn49.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Enter the username and password you created earlier for your first Virtual Machine

</p>

<img src="https://i.imgur.com/0RIqfGA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
You will see this popup
Click Continue
</p>

<img src="https://i.imgur.com/kA1wM0P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
You should see this screen after you logged in to your first Virtual Machine
Once you’re into your first virtual machine, click Microsoft Edge (an internet browser)
</p>

<img src="https://i.imgur.com/9fRAKVk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Start without data
</p>

<img src="https://i.imgur.com/RRufBoF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Next click confirm and start browsing
</p>


<img src="https://i.imgur.com/hOsckgO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Type in “install wireshark “ in google.com
Download Windows Installer (for windows since your first Virtual Machine is running Windows 10)
</p>

<img src="https://i.imgur.com/rbBESpZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Open File
</p>

<img src="https://i.imgur.com/hetAFrh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Next

</p>

<img src="https://i.imgur.com/qKAvHGg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click noted
Then click next
</p>

<img src="https://i.imgur.com/aVdvDWO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Next until you get to the next screen
</p>

<img src="https://i.imgur.com/2s4W7Aw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click next 
</p>

<img src="https://i.imgur.com/9tFTjMP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Next
Click Install
Click “I Agree”
</p>

<img src="https://i.imgur.com/NjXXhB3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Click Finish
</p>

<img src="https://i.imgur.com/9GU0M01.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Open Wireshark and click Ethernet
</p>

<img src="https://i.imgur.com/h11Q1AC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Then click the blue fin at the top left
</p>

<img src="https://i.imgur.com/jsiDntX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/Xe6kLRM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://i.imgur.com/Y0ommgH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Ping your second virtual machine by typing in “ping” and your second virtual machine's private IP address
You should see something sent and received under ping statistics to ensure it worked correctly.
</p>





