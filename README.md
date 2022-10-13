<h1><p align="center">
  Nessus Home Lab  <p align="left"><img src="https://user-images.githubusercontent.com/114441952/195536965-778fb5c3-9e25-4fdd-9856-bd70cb1a4c24.png" width="200"></h1>
  
<h2>Description</h2>
I used Nessus Essentials to do vulnerability scanning and culnerability remediation. I used Nessus Essentials on a local VM, using VMware Workstation, to run a credentialed scans to discover vulnerabilities, remediate some of the vulnerabilities, then rescaned to verify the redemediation. 

</br>

<h2>Languages and Utilities Used</h2>
 - <b>Nessus Essentials:<br>
 - Windows 10:<br>
 - VMware Workstation:

</b> 

<h2>Lab walk-through:</h2>
<p align="center">
Find out the Nesses Target IP address
<img src="https://user-images.githubusercontent.com/114441952/195543401-dc2fba8b-f8ac-48d5-93b5-9db938cbd8e5.png"/>

<p align="center">
Configured the firewall profiles for connectivity with the Nessus host to Nesses Target
<img src="https://user-images.githubusercontent.com/114441952/195543559-f68a3bf1-7902-4afe-aaa2-75743b939fa0.png"/>

<p align="center">
Used Nessus Essential for a non-credentialed scan on the target
<img src="https://user-images.githubusercontent.com/114441952/195550442-f478a02d-d2a0-46e9-80b1-a9852ea0cfbb.png"/>

<p align="center">
Inspected the vulnerabilities of the completed non-credentialed scan 
<img src="https://user-images.githubusercontent.com/114441952/195550565-cd566dc1-c645-4e89-a0d4-ec7017962996.png"/>

<p align="center">
Enabled Automatic for Remote Registry to allow the scanner to connect and search the registry during the credentialed scan
<img src="https://user-images.githubusercontent.com/114441952/195550736-e8741d55-5e97-4038-9ac1-5bc33beb671d.png"/>

<p align="center">
Ran another scan but this time with credentials on the target
<img src="https://user-images.githubusercontent.com/114441952/195550813-0b6e19bf-ba7d-4dea-ba54-bf632f2a2bfe.png"/>

<p align="center">
Installed an old version of Firefox on the Nessus Target and ran another credentialed scan
<img src="https://user-images.githubusercontent.com/114441952/195551169-a80bb2f1-4d3f-4d0d-b633-e7c6ab645048.png"/>


<p align="center">
Lastly I did some remediations by uninstalling firefox and updating Windows on the VM
<img src="https://user-images.githubusercontent.com/114441952/195551220-9888237f-2dbe-4f4a-8e0a-3f9e13c405dc.png"/>

