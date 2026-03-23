<h1>MICROSOFT ENTRA ID IAM LAB</h1>

<h2>Description</h2>
Built and configured a Microsoft Entra ID tenant to simulate enterprise identity and access management environments
Implemented Multi-Factor Authentication (MFA) and Conditional Access policies to secure user sign-ins
<br />

<h2>Tools Used</h2>

- <b>Oracle VirtualBox, Win 11 Enterprise, MS Authenticator, Azure</b> 

<h2>Environments Used</h2>

- <b>Windows 11 Enterprise Iso</b>

<h2>Program walk-through:</h2>
<p align="center">
Go to portal.azure.com, microsoft Entra ID and create a User. Enter principal Name, Display name, Keep the account enabled, create or generate a password <br/>
<img src="https://i.imgur.com/dR6prQ0.png" height="80%" width="80%" alt="create a user"/>
<br />
<br />
Check Device join permissions. Go to Entra ID > Devices, Device settings, Find "users may join devices to Microsoft Entra ID", Set to all":  <br/>
<img src="https://imgur.com/6vGFUiz.png" height="80%" width="80%" alt="Entra join"/>
<br />
<br />
Enable Security Defaults. Go to Entra ID > Overview, Properties, Manage security Defaults, Set Security Defaults to Enabled, save <br/>
<img src="https://imgur.com/g5hI5oL.png" height="80%" width="80%" alt="Security Defaults"/>
<br />
<br />
Install the Microsoft Authenticator app from the app store on your cellphone <br/>
<img src="https://imgur.com/aN62JFa.png" height="80%" width="80%" alt="Authenticator app"/>
<br />
<br />
Download VirtualBox @ virtualbox.org/wiki/Downloads. Downlaod the platform package for your OS. I'm running windows. <br/>
<img src="https://imgur.com/H84RkCV.png" height="80%" width="80%" alt="Virtualbox"/>
<img src="https://imgur.com/EHDeHxY.png" height="80%" width="80%" alt=WIN11"/>
<br />
<br />
Create the VM. Click New, Name your VM, Select the windows ISO File, set memory, CPU, Hard disk <br/>
<img src="https://imgur.com/y6OiPom.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join the VM to Entra. Inside the VM, Open settings, accounts, connect, Click "join this device to Microsoft Entra", Enter the lab user email, password, approve the sign in on your phone, confirm the organization, click join <br/>
<img src="https://imgur.com/peSUR2h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Verify the Device in Entra<br/>
<img src="https://imgur.com/lsBL02X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
