<h1>Using Service Principal Identity to List AD Roles</h1>

<!--
 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)
 --!>

<h2>Description</h2>
In this hands-on lab, you are tasked with gathering the role definitions and role assignments for your organization. You do not have access to the portal, so you must collect this information via SSH connection, by using a Linux VM and a service principal. Once access to the Azure subscription has been gained, use the Azure CLI to collect the required information, and output to a file so you can email it to your manager.
<br />
<br />
You have been given login credentials to a Linux VM and a service principal. Connect to the VM with the credentials, and using the service principal, access the Azure subscription.
<br />
Once you have gained access to the Azure subscription, perform the steps listed in the objectives to complete this hands-on lab.
<br />

<h2>Languages and/or Utilities Used</h2>

- <b>Azure CLI</b> 


<h2>Environments Used </h2>

- <b>Azure</b>

<h2>Walkthrough:</h2>

<p align="center">

<b>Log in to Azure using the Service Principal</b>
<br/>
<br/>
- Once connected to the Linux VM, perform the az login command with the --service-principal flag to login to the Azure account.
<br/>
<img src="https://i.imgur.com/RGNpD69.jpg" height="80%" width="80%" alt="1.1"/>
<br />
<br />

<b>List the Role Definitions and Role Assignments</b>
<br />
<br />
- Navigate to the group created.
<br />
- Enter the Azure CLI command to list the role assignments and append the output to the same file.
<br/>
<img src="https://i.imgur.com/qUuI38q.jpg" height="80%" width="80%" alt="2.1"/>
<br />
<br />
<img src="https://i.imgur.com/0JL3U39.jpg" height="80%" width="80%" alt="2.2"/>
<br />
<br />
<img src="https://i.imgur.com/xlkZChU.jpg" height="80%" width="80%" alt="2.3"/>
<br />
<br />
<img src="https://i.imgur.com/ISmY9te.jpg" height="80%" width="80%" alt="2.4"/>
<br />
<br />
<img src="https://i.imgur.com/QkunPmC.jpg" height="80%" width="80%" alt="2.5"/>
<br />
<br />
<img src="https://i.imgur.com/T79nz62.jpg" height="80%" width="80%" alt="2.6"/>
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
