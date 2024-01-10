<h1>Active Directory Virtual Lab</h1>

<h2>Description</h2>
In this Project I created a virtaul lab using Oracle VirtualBox. I created my first virtual machine which acted as my domain controller. I gave the first virtual machine 2 network adapters, one network was used to connect to the outside internet, and the other was used to connect to the virtual box private network that will be used for the clients. Then I installed windows server 2019 and assigned IP adressing for the internal network. After I got IP adressing working I named the server then installed active directory and created the domaiin. Then I configured NAT and routing so the clients on the private network could use the internet through the domain controller. Next I setup a DHCP on the domain controller so my virtual windows machine can automatically get an IP address. I also ran a powershell script that automatically created 1,000 users in active directory. Then I created my second virtual machine with Windows 10 installed which was connected to the private virtual box network. Finally I joined this virtual machine to the domain and logged into it with one of the domain accounts. <br />

<h2>Environments Used</h2>

- Windows 10
- Server 2019 ISO
- Oracle VirtualBox

<h2>Project Walkthrough:</h2>

<p align="center">
Setting up IP addressing: <br/> 
<img src="https://i.imgur.com/aJ1zz1d.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<img src="https://i.imgur.com/Guj2uDJ.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br /> 
Setting up DHCP: <br/>
<img src="https://i.imgur.com/z0DxalW.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br />
Adding the Users: <br/> 
<img src="https://i.imgur.com/uqW79GG.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br /> 
Powershell Script I used: <br/>
<img src="https://i.imgur.com/W0hZoKe.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br />
Some extra imagages to help visualize what I did: <br/>
<img src="https://i.imgur.com/xppIvmF.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br />
<img src="https://i.imgur.com/YkuY5vS.png" height="80%" Width="80%" alt="Disk Sanitization STEPS"/>
<br />
<br />
