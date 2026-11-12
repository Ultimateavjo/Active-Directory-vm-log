# Active-Directory-vm-log
Active log of creating my own virtual machine with active directory

<h2>Description</h2>
Project consists of a homelab with an active directory that has the system up and running, OU's with two employees each, examples of shared network folders, password resets, group policy applications. Along with a separate Win 11 client attached to the active directory and connected working. 
<br />


<h2>Utilities Used</h2>

- <b>Orcale Box VM</b> 

<h2>Environments Used </h2>

- <b>Windows 22 Server</b>
- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img <img width="1415" height="1677" alt="Imaging into VM" src="https://github.com/user-attachments/assets/8cf7ffc8-7df6-4d4d-8d94-ce201ecaa56f" height="80%" width="80%"/>
 <img width="1135" height="837" alt="install of OS" src="https://github.com/user-attachments/assets/9f78863a-fb35-4646-9bd9-73bba3cfa1cc" height="80%" width="80%"/>
 <img width="1150" height="800" alt="OS install" src="https://github.com/user-attachments/assets/d3f0c00e-f74b-4a18-9914-8079b3320120" />
<br />
<br />
Renaming the Server Computer:  <br/>
<img <img width="1074" height="841" alt="adv setting into naming pc" src="https://github.com/user-attachments/assets/a643ff8c-0d74-4a96-84f0-dac63d028e41" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img width="1078" height="821" alt="cmd to check name of pc" src="https://github.com/user-attachments/assets/ece1a416-3c70-4717-a295-04776daca649" />
<br />
<br />
Installing Active Directory: <br/>
<img width="1074" height="817" alt="step 1 to install AD" src="https://github.com/user-attachments/assets/aee2f7e8-1bbd-49d5-9c15-dbb021bc8150" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img width="810" height="581" alt="ensure role based features is selected for the AD" src="https://github.com/user-attachments/assets/1b5f3ba6-ba57-45f1-9e12-d0289e1bcb25" />
<img width="812" height="563" alt="Selecting AD for the server" src="https://github.com/user-attachments/assets/d47938c7-dee4-4b9c-980f-29e1928ea4f9" />
<img width="1071" height="739" alt="installing the AD" src="https://github.com/user-attachments/assets/c04c6d34-2eab-4c35-916e-fc1743c97943" />
<img width="1072" height="737" alt="how to promote to domain controller" src="https://github.com/user-attachments/assets/ad4375ad-1531-4c54-a185-53bf34168e5f" />
<img width="1071" height="797" alt="naming domain" src="https://github.com/user-attachments/assets/d035a207-ca00-49bc-ab7e-e5874947ec92" />
<img width="1075" height="731" alt="default pathway settings " src="https://github.com/user-attachments/assets/bc9462ea-61ae-4170-8ceb-d3e562648884" />
<img width="1070" height="739" alt="reviewed information" src="https://github.com/user-attachments/assets/19024e11-a5e2-4a72-8b62-339b21e80448" />
<img width="1073" height="739" alt="prerequisites check passed" src="https://github.com/user-attachments/assets/d01a992a-5626-41e9-a6e7-03277f3021ab" />
<br />
<br />
Logging in, setting up Users and OU's :  <br/>
<img width="1072" height="902" alt="domain name listed after install" src="https://github.com/user-attachments/assets/028db894-da5c-45b4-b7d4-2c4d710fc279" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img width="1071" height="824" alt="windows admin tools shown for everything needed for AD" src="https://github.com/user-attachments/assets/7ba5879d-b2fd-4935-80eb-68771c4b305e" />
 <img width="1069" height="839" alt="Affixing a static IP address to the server  " src="https://github.com/user-attachments/assets/3cc75266-4d31-446b-8653-58196e3d19be" />
<img width="1077" height="815" alt="starting point for AD" src="https://github.com/user-attachments/assets/2b692f27-5f57-47c6-9f96-b5c75c5b266e" />
<img width="1070" height="819" alt="Making a user a domain Admin" src="https://github.com/user-attachments/assets/ba602995-a18b-4cbe-b1e2-b2beb68bf940" />
<img width="1069" height="820" alt="Created OU&#39;s and user" src="https://github.com/user-attachments/assets/7841390f-b3b4-4197-982e-5baf1caa6aaa" />
<br />
<br />
Attaching Windows 11 Client:  <br/>
<img width="1067" height="926" alt="created win 11 vm to add to server" src="https://github.com/user-attachments/assets/27d89e72-b72c-4101-a853-5e5571066a3e"height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img width="1072" height="1609" alt="setting up win 11 pc with dns from server ipv4 address" src="https://github.com/user-attachments/assets/ef2ad137-1b93-4cc8-b890-1e5db9649468" />
 <img width="1065" height="733" alt="sent ping to server comp and all packets came back with no loss" src="https://github.com/user-attachments/assets/ef28ca44-eebb-4b2e-a7f7-5692a65f8ada" />
<img width="1058" height="877" alt="inputting infomation to add comp to domain" src="https://github.com/user-attachments/assets/80dacf6a-d490-4269-b5c8-332029377caa" />
<img width="1407" height="1147" alt="changed firewall settings to allow inbound traffic so the client machine can connect" src="https://github.com/user-attachments/assets/592ad7e9-023f-465a-acac-8bda6840afc7" />
<img width="1053" height="907" alt="Added win 11 pc to domain" src="https://github.com/user-attachments/assets/24314316-f50a-4190-b692-36ebbff1ef7a" />
<img width="1022" height="839" alt="Win 11 PC showing it is signed into the domain at the bottom" src="https://github.com/user-attachments/assets/5e9ebb0a-ce80-4fc4-b1a2-60c13788986b" />
<img width="1028" height="846" alt="Employee Fully Added to the doamin" src="https://github.com/user-attachments/assets/429898a7-e37f-496e-b57b-ec8ee88e1923" />
<img width="1048" height="595" alt="Moving win 11 PC to proper domain" src="https://github.com/user-attachments/assets/cc14e272-31c1-4790-b786-3b1b80edd789" />
<img width="1049" height="461" alt="Adding description to client machine" src="https://github.com/user-attachments/assets/e808dc71-3256-46a5-a1c4-7b1f56984dfb" />
<br />
<br />
Creating Shared Folder:  <br/>
<img width="1070" height="875" alt="Initial shared folder" src="https://github.com/user-attachments/assets/b16f877d-7c1d-46fc-a2b0-c908649d87f5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img width="1073" height="878" alt="Shared Folders for each dept  " src="https://github.com/user-attachments/assets/1df14fbb-1459-4d06-8d6a-d78d16397ca9" />
<img width="1068" height="878" alt="Creating Groups in OU&#39;s to match shared folder names" src="https://github.com/user-attachments/assets/bf78f5c8-fe1f-4ec9-9d23-912f19bbb226" />
<img width="1054" height="876" alt="Adding the security Group to the shared folder  " src="https://github.com/user-attachments/assets/0ab3d2f0-3727-4e20-8bc9-ae57b579dfab" />
<img width="496" height="562" alt="Giving members of the Human Resources the ability to modify in this folder" src="https://github.com/user-attachments/assets/9dd54d7b-e4c1-41be-a1b3-2c62789fa993" />
<img width="1067" height="880" alt="Using the disable inherited permission button to disallow people from other depts to enter" src="https://github.com/user-attachments/assets/f355020e-cadf-43e0-bdd8-3c5106ba5f1a" />
<img width="1061" height="879" alt="After getting rid of inherited permission, also took out regular uses from the permission entry" src="https://github.com/user-attachments/assets/bcad303b-76b2-42ba-87cc-62e23b048209" />
<img width="1071" height="879" alt="Giving share permission from the parent folder to everyone who should have domain access" src="https://github.com/user-attachments/assets/175742b1-c872-49a2-8e73-f42668029a66" />
<img width="1046" height="801" alt="Typing path for network folder" src="https://github.com/user-attachments/assets/f8135716-37f8-4794-8d47-e6c6e4325406" />
<img width="1043" height="821" alt="Fully created and pinned network folder" src="https://github.com/user-attachments/assets/60edc700-6df0-4b13-b643-3e90690be8c0" />
<img width="1074" height="1771" alt="Created folder in win 11 client and it shows in win ser 22" src="https://github.com/user-attachments/assets/400a82ae-3337-43df-b87b-7b2e95e1ee4b" />
<br />
<br />
Group Policy creation and Enforecment:  <br/>
<img width="1054" height="1685" alt="Account is locked before re-enabling" src="https://github.com/user-attachments/assets/70c22a27-c2df-4c66-812b-c85f4c19460c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img width="1071" height="823" alt="options for password definitions" src="https://github.com/user-attachments/assets/340a7033-cabf-44cd-9fc0-c3959c352294" />
<img width="1069" height="820" alt="Rules for password set" src="https://github.com/user-attachments/assets/b4fc2e0d-c54e-49cc-b7bf-0bcca710b7b0" />
<img width="1067" height="815" alt="attaching new GPO to domain" src="https://github.com/user-attachments/assets/47b753fc-f41d-4821-8547-ad8e4d158539" />
<img width="1073" height="848" alt="updating group policy through powershell for all users in the domain" src="https://github.com/user-attachments/assets/1c3ede80-db77-4ef5-93d4-f0c25f363b55" />
<img width="1073" height="813" alt="group policy pushed through" src="https://github.com/user-attachments/assets/9a57f7f0-977b-439b-84c0-6e1432780068" />

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
