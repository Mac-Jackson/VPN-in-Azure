<p align="center">
<img src="https://github.com/user-attachments/assets/62ccef8e-885d-491d-821a-b8555a416e67" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>

 

<h2>Description</h2>
In this project, I create an Azure VM (Virtual Machine) where I download, install, and use a free VPN (Virtual Private Network) called ProtonVPN. <br />
<br />
VPNs (Virtual Private Networks) allow you to connect to a network through encrypted tunnels, enhancing security. Two common ways VPNs are used are for companies to allow for remote work and access different content that otherwise would be unavailable without a VPN.  
<br/>


<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Walk-through:</h2>

<p align="center">
First, I will create an Azure VM: <br/>
<img src="https://github.com/user-attachments/assets/5d673ee1-4958-4494-9165-6a0dec01c263" height="80%" width="80%" alt="Setting Up in Azure"/> 
<br />
<br />
<img src="https://github.com/user-attachments/assets/7f4fd035-bb0b-4df8-96e2-f98304c42aac" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />
<br />
While that's creating, I will navigate to this website https://whatismyipaddress.com to get my IP address and location. I will write this down in my notepad so that I can observe the changes later when we connect to our VM:  <br/>
<img src="https://github.com/user-attachments/assets/2d93157e-3c3f-4d74-baa5-5bde805dda05" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />
<br />
Next, I'll connect to the VM I just created using Remote Desktop Connection:  <br/>
<img src="https://github.com/user-attachments/assets/79a21d70-b17a-41af-9c11-3776d195d3c0" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />
<br />
Once I'm connected to my VM, I will navigate to the same IP website, then observe and note the different IPs and locations since I set this VM up to be in Canada. (This RDP connection is like a VPN connection in the sense that there is a tunnel connecting my physical computer to the VM in a different location entirely):  <br/>
<img src="https://github.com/user-attachments/assets/a2fed50f-e792-4f24-b160-216ce317e298" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />
<br />
Now, I can head over to ProtonVPN and sign up for a free account:  <br/>
<img src="https://github.com/user-attachments/assets/9f10551a-46d5-47a8-9a49-6c2b6197da4c" height="80%" width="80%" alt="Setting Up in Azure"/> 

<br />
<br />
After I made my account, I can now download the Windows version in the downloads tab:  <br/>
<img src="https://i.imgur.com/KYdNGNv.png" height="80%" width="80%" alt="Setting Up in Azure"/> 
<br />
<br />
The download will start, and then I'll install the VPN client. It will then have a pop-up for me to sign in with my ProtonVPN account I just made:  <br/>
<img src="https://i.imgur.com/8Kn8q2w.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
After I sign in, it will take me to the homepage where I can start a VPN connection:  <br/>
<img src="https://i.imgur.com/cup7xHR.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I'll click on "Quick Connect," and it will choose and start a VPN connection for me:
<img src="https://i.imgur.com/uMCJ8Px.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now, if I go back to the IP address website and refresh the page, it shows me that I am in Romania instead of Canada, and I have another different IP address:  <br/>
<img src="https://i.imgur.com/bmCGOuW.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Also, while connected to the VPN, I can go to different sites like www.google.com and www.netflix.com to see the difference compared to if I were on these sites within my physical computer browser:  <br/>
<img src="https://i.imgur.com/AlHOv92.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/UrfIVcB.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />

<h2> The Setup and Use of Proton is now Complete!</h2>

<b> We've downloaded, installed, and used a free VPN called ProtonVPN! We observed the changes in our IP address and location and saw some possibilities, like accessing different content using a VPN! </b>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
