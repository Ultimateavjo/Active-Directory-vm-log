# Active Directory Home Lab

A hands-on Windows Server and Active Directory project demonstrating core IT support and system administration workflows. The project includes domain configuration, user and organizational unit management, Windows 11 domain integration, departmental file sharing, password resets, and Group Policy configuration.

<h2>Description</h2>

This project demonstrates practical experience building and managing an Active Directory environment using virtual machines. A Windows Server domain controller and a Windows 11 client were configured to simulate a small-business network.

The environment includes organizational units (OUs) for HR, IT, and Finance, with at least two employee accounts in each department. All activities were completed in a personal lab rather than a production business environment.

<br />

<h2>Skills Demonstrated</h2>

- Windows Server installation and configuration
- Active Directory Domain Services installation and domain controller promotion
- Organizational unit, user account, and security group management
- Static IP addressing and client DNS configuration
- Windows 11 domain joining and connectivity testing
- Shared folder creation and group-based access permissions
- Password resets and account administration
- Group Policy creation, linking, and refresh

<h2>Tools and Technologies Used</h2>

- <b>Oracle VirtualBox</b>
- <b>Active Directory Domain Services (AD DS)</b>
- <b>Active Directory Users and Computers</b>

<h2>Environments Used</h2>

- <b>Windows Server 2022</b>
- <b>Windows 11</b>

<h2>Project Walk-Through</h2>

<h3>1. Virtual Machine and Operating System Setup</h3>

<p align="center">
Configuring the Windows Server virtual machine: <br/>
<img src="https://github.com/user-attachments/assets/8cf7ffc8-7df6-4d4d-8d94-ce201ecaa56f" width="80%" alt="Configuring the Windows Server virtual machine in Oracle VirtualBox"/>
<br />
<br />
<p align="center">
Starting the Windows Server installation: <br/>
<img src="https://github.com/user-attachments/assets/9f78863a-fb35-4646-9bd9-73bba3cfa1cc" width="80%" alt="Starting the Windows Server operating system installation"/>
<br />
<br />
<p align="center">
Continuing the operating system installation: <br/>
<img src="https://github.com/user-attachments/assets/d3f0c00e-f74b-4a18-9914-8079b3320120" width="80%" alt="Windows Server installation in progress"/>
<br />
</p>

<h3>2. Server Naming and Identification</h3>

<p align="center">
Renaming the server through system settings: <br/>
<img src="https://github.com/user-attachments/assets/a643ff8c-0d74-4a96-84f0-dac63d028e41" width="80%" alt="Changing the Windows Server computer name"/>
<br />
<br />
<p align="center">
Verifying the server name through Command Prompt: <br/>
<img src="https://github.com/user-attachments/assets/ece1a416-3c70-4717-a295-04776daca649" width="80%" alt="Checking the server computer name in Command Prompt"/>
<br />
</p>

<h3>3. Active Directory Installation and Domain Configuration</h3>

<p align="center">
Starting the Add Roles and Features Wizard: <br/>
<img src="https://github.com/user-attachments/assets/aee2f7e8-1bbd-49d5-9c15-dbb021bc8150" width="80%" alt="Opening the Add Roles and Features Wizard in Windows Server"/>
<br />
<br />
<p align="center">
Selecting role-based or feature-based installation: <br/>
<img src="https://github.com/user-attachments/assets/1b5f3ba6-ba57-45f1-9e12-d0289e1bcb25" width="80%" alt="Selecting the role-based installation option"/>
<br />
<br />
<p align="center">
Selecting Active Directory Domain Services: <br/>
<img src="https://github.com/user-attachments/assets/d47938c7-dee4-4b9c-980f-29e1928ea4f9" width="80%" alt="Selecting the Active Directory Domain Services server role"/>
<br />
<br />
<p align="center">
Installing Active Directory Domain Services: <br/>
<img src="https://github.com/user-attachments/assets/c04c6d34-2eab-4c35-916e-fc1743c97943" width="80%" alt="Installing the Active Directory Domain Services role"/>
<br />
<br />
<p align="center">
Starting domain controller promotion: <br/>
<img src="https://github.com/user-attachments/assets/ad4375ad-1531-4c54-a185-53bf34168e5f" width="80%" alt="Starting the process to promote the server to a domain controller"/>
<br />
<br />
<p align="center">
Configuring the domain name: <br/>
<img src="https://github.com/user-attachments/assets/d035a207-ca00-49bc-ab7e-e5874947ec92" width="80%" alt="Entering the domain name during domain controller configuration"/>
<br />
<br />
<p align="center">
Reviewing the Active Directory database, log, and SYSVOL paths: <br/>
<img src="https://github.com/user-attachments/assets/bc9462ea-61ae-4170-8ceb-d3e562648884" width="80%" alt="Reviewing the default Active Directory storage paths"/>
<br />
<br />
<p align="center">
Reviewing the domain controller configuration: <br/>
<img src="https://github.com/user-attachments/assets/19024e11-a5e2-4a72-8b62-339b21e80448" width="80%" alt="Reviewing domain controller installation settings"/>
<br />
<br />
<p align="center">
Completing the prerequisite check before installation: <br/>
<img src="https://github.com/user-attachments/assets/d01a992a-5626-41e9-a6e7-03277f3021ab" width="80%" alt="Successful prerequisite check for domain controller promotion"/>
<br />
</p>

<h3>4. Organizational Units and User Administration</h3>

Created organizational units for HR, IT, and Finance, with at least two employee accounts in each department.

<p align="center">
Viewing the domain sign-in screen after installation: <br/>
<img src="https://github.com/user-attachments/assets/028db894-da5c-45b4-b7d4-2c4d710fc279" width="80%" alt="Windows Server sign-in screen displaying the configured domain"/>
<br />
<br />
<p align="center">
Accessing Windows administrative tools: <br/>
<img src="https://github.com/user-attachments/assets/7ba5879d-b2fd-4935-80eb-68771c4b305e" width="80%" alt="Windows administrative tools available for domain management"/>
<br />
<br />
<p align="center">
Opening Active Directory Users and Computers: <br/>
<img src="https://github.com/user-attachments/assets/2b692f27-5f57-47c6-9f96-b5c75c5b266e" width="80%" alt="Initial view of Active Directory Users and Computers"/>
<br />
<br />
<p align="center">
Creating departmental organizational units and user accounts: <br/>
<img src="https://github.com/user-attachments/assets/7841390f-b3b4-4197-982e-5baf1caa6aaa" width="80%" alt="Departmental organizational units and employee accounts in Active Directory"/>
<br />
<br />
<p align="center">
Demonstrating Domain Admins group membership using a lab IT account: <br/>
<img src="https://github.com/user-attachments/assets/ba602995-a18b-4cbe-b1e2-b2beb68bf940" width="80%" alt="Adding a lab IT account to the Domain Admins group"/>
<br />
</p>

<h3>5. Server Network Configuration</h3>

<p align="center">
Assigning a static IP address to the server: <br/>
<img src="https://github.com/user-attachments/assets/3cc75266-4d31-446b-8653-58196e3d19be" width="80%" alt="Configuring a static IPv4 address on the Windows Server"/>
<br />
</p>

<h3>6. Windows 11 Client and Domain Integration</h3>

<p align="center">
Preparing the Windows 11 client virtual machine: <br/>
<img src="https://github.com/user-attachments/assets/27d89e72-b72c-4101-a853-5e5571066a3e" width="80%" alt="Windows 11 client virtual machine prepared for domain integration"/>
<br />
<br />
<p align="center">
Configuring the client to use the domain controller as its DNS server: <br/>
<img src="https://github.com/user-attachments/assets/ef2ad137-1b93-4cc8-b890-1e5db9649468" width="80%" alt="Setting the Windows 11 client DNS server to the domain controller IP address"/>
<br />
<br />
<p align="center">
Testing connectivity to the server with ping: <br/>
<img src="https://github.com/user-attachments/assets/ef28ca44-eebb-4b2e-a7f7-5692a65f8ada" width="80%" alt="Successful ping test from the client to the Windows Server with no packet loss"/>
<br />
<br />
<p align="center">
Entering the domain name to join the client: <br/>
<img src="https://github.com/user-attachments/assets/80dacf6a-d490-4269-b5c8-332029377caa" width="80%" alt="Entering domain information on the Windows 11 client"/>
<br />
<br />
<p align="center">
Adjusting Windows Server inbound firewall settings during connectivity troubleshooting: <br/>
<img src="https://github.com/user-attachments/assets/592ad7e9-023f-465a-acac-8bda6840afc7" width="80%" alt="Adjusting inbound firewall settings on the Windows Server in the lab"/>
<br />
<br />
<p align="center">
Confirming the client joined the domain: <br/>
<img src="https://github.com/user-attachments/assets/24314316-f50a-4190-b692-36ebbff1ef7a" width="80%" alt="Confirmation that the Windows 11 client joined the domain"/>
<br />
<br />
<p align="center">
Viewing the domain sign-in option on the client: <br/>
<img src="https://github.com/user-attachments/assets/5e9ebb0a-ce80-4fc4-b1a2-60c13788986b" width="80%" alt="Windows 11 sign-in screen showing the domain sign-in option"/>
<br />
<br />
<p align="center">
Signing in to the client with a domain user account: <br/>
<img src="https://github.com/user-attachments/assets/429898a7-e37f-496e-b57b-ec8ee88e1923" width="80%" alt="Domain user signed in to the Windows 11 client"/>
<br />
<br />
<p align="center">
Moving the client computer account into the designated computer OU: <br/>
<img src="https://github.com/user-attachments/assets/cc14e272-31c1-4790-b786-3b1b80edd789" width="80%" alt="Moving the Windows 11 computer account into an organizational unit"/>
<br />
<br />
<p align="center">
Adding a description to the client computer account: <br/>
<img src="https://github.com/user-attachments/assets/e808dc71-3256-46a5-a1c4-7b1f56984dfb" width="80%" alt="Adding a descriptive label to the client computer account in Active Directory"/>
<br />
</p>

<h3>7. Departmental Shared Folders and Access Permissions</h3>

Created departmental shared folders and security groups, configured folder permissions, and tested file access from the Windows 11 client.

<p align="center">
Creating the initial shared folder structure: <br/>
<img src="https://github.com/user-attachments/assets/b16f877d-7c1d-46fc-a2b0-c908649d87f5" width="80%" alt="Creating the initial shared folder structure on the server"/>
<br />
<br />
<p align="center">
Creating shared folders for each department: <br/>
<img src="https://github.com/user-attachments/assets/1df14fbb-1459-4d06-8d6a-d78d16397ca9" width="80%" alt="Departmental shared folders on the Windows Server"/>
<br />
<br />
<p align="center">
Creating departmental security groups: <br/>
<img src="https://github.com/user-attachments/assets/bf78f5c8-fe1f-4ec9-9d23-912f19bbb226" width="80%" alt="Creating Active Directory security groups for departmental folder access"/>
<br />
<br />
<p align="center">
Adding a security group to the folder permissions: <br/>
<img src="https://github.com/user-attachments/assets/0ab3d2f0-3727-4e20-8bc9-ae57b579dfab" width="80%" alt="Assigning a departmental security group to shared folder permissions"/>
<br />
<br />
<p align="center">
Assigning Modify permissions to the HR group: <br/>
<img src="https://github.com/user-attachments/assets/9dd54d7b-e4c1-41be-a1b3-2c62789fa993" width="80%" alt="Assigning Modify permissions to the Human Resources security group"/>
<br />
<br />
<p align="center">
Disabling permission inheritance for departmental access configuration: <br/>
<img src="https://github.com/user-attachments/assets/f355020e-cadf-43e0-bdd8-3c5106ba5f1a" width="80%" alt="Disabling inherited permissions on a departmental folder"/>
<br />
<br />
<p align="center">
Reviewing and removing unwanted permission entries: <br/>
<img src="https://github.com/user-attachments/assets/bcad303b-76b2-42ba-87cc-62e23b048209" width="80%" alt="Reviewing folder permissions after converting inherited entries"/>
<br />
<br />
<p align="center">
Configuring share permissions on the parent folder: <br/>
<img src="https://github.com/user-attachments/assets/175742b1-c872-49a2-8e73-f42668029a66" width="80%" alt="Configuring parent folder share permissions for domain access"/>
<br />
<br />
<p align="center">
Accessing the network folder from the Windows 11 client: <br/>
<img src="https://github.com/user-attachments/assets/f8135716-37f8-4794-8d47-e6c6e4325406" width="80%" alt="Entering the network folder path on the Windows 11 client"/>
<br />
<br />
<p align="center">
Pinning the network folder for convenient access: <br/>
<img src="https://github.com/user-attachments/assets/60edc700-6df0-4b13-b643-3e90690be8c0" width="80%" alt="Network folder accessible and pinned in File Explorer"/>
<br />
<br />
<p align="center">
Verifying that a folder created from the client appears on the server: <br/>
<img src="https://github.com/user-attachments/assets/400a82ae-3337-43df-b87b-7b2e95e1ee4b" width="80%" alt="Folder created through the Windows 11 client visible on the Windows Server"/>
<br />
</p>

<h3>8. Account Administration and Group Policy</h3>

Practiced account administration and configured a domain-linked Group Policy Object (GPO) for password settings.

<p align="center">
Reviewing a locked user account during account administration: <br/>
<img src="https://github.com/user-attachments/assets/70c22a27-c2df-4c66-812b-c85f4c19460c" width="80%" alt="Locked user account shown during account administration"/>
<br />
<br />
<p align="center">
Reviewing available password policy settings: <br/>
<img src="https://github.com/user-attachments/assets/340a7033-cabf-44cd-9fc0-c3959c352294" width="80%" alt="Password policy settings in Group Policy Management Editor"/>
<br />
<br />
<p align="center">
Configuring password policy requirements: <br/>
<img src="https://github.com/user-attachments/assets/b4fc2e0d-c54e-49cc-b7bf-0bcca710b7b0" width="80%" alt="Configuring password requirements in Group Policy"/>
<br />
<br />
<p align="center">
Linking the Group Policy Object to the domain: <br/>
<img src="https://github.com/user-attachments/assets/47b753fc-f41d-4821-8547-ad8e4d158539" width="80%" alt="Linking the configured Group Policy Object to the domain"/>
<br />
<br />
<p align="center">
Running a Group Policy refresh command on the server: <br/>
<img src="https://github.com/user-attachments/assets/1c3ede80-db77-4ef5-93d4-f0c25f363b55" width="80%" alt="Running a Group Policy refresh command in Windows PowerShell"/>
<br />
<br />

Reviewing the Group Policy update result: <br/>
<img src="https://github.com/user-attachments/assets/9a57f7f0-977b-439b-84c0-6e1432780068" width="80%" alt="Group Policy update result displayed after the refresh"/>
<br />
</p>
