# osTicket-Post-Installation-Setup

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Setup</h1>
This tutorial outlines the post-installation-setup of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/b2a16688-b648-44ae-9c2c-61b89cf2d2cf" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/e0bfe323-1e90-4767-8ffb-6183fabbefb0" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/0c2e0722-28e8-499e-9382-f6a72d94cc31" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/34d96879-0579-42ec-975d-ab3531cd76b4" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/4524f8dc-6c27-4333-9ce2-a3877d126eba" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/112a64a8-276f-4e09-9205-ad8abf1be239" />

</p>
<p>
Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
* Supreme Admin

</p>
<br />

<p>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/1b13ced8-326f-4848-b5af-a40395ce2488" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/a4a48cd9-d388-4b9a-a96a-730def3b2937" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/c73356bc-5da5-4830-9c5b-6ee4ae7df7a1" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/71edf981-84ac-41bf-a7d5-51c08b1f3c4c" />

</p>
<p>
Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
* SysAdmins
</p>
<br />

<p>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/9dac224a-0c46-419b-bd81-f4e1abe72de1" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/b3d38d08-99ca-42fc-814e-d5d7ba9a3e72" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/b72c8e46-4ff4-43a3-884a-84ef59563643" />

</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
* Online Banking
</p>
<br />

<p>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/ba57f32b-f821-47a8-be96-abd87812395b" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/ff4ca491-77a2-43b0-9456-e6b73384def5" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/ad804d02-d5e1-4d7a-b786-3ebab3effcb0" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/409c6aa5-4c55-4f64-adde-46a6328fd58d" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/c08b1957-ce0f-4a17-8920-8382981c8359" />
<img width="479" alt="image" src="https://github.com/user-attachments/assets/4fe608a6-c8a4-4d05-9cd6-3ea7ad8310a1" />

</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New
* Jane (Dept: SysAdmins)
* John (Dept: Support
</p>
<br />
<p>
<img width="479" alt="image" src="https://github.com/user-attachments/assets/85323827-c3b8-490c-a267-e200275a7426" />
<img width="307" alt="image" src="https://github.com/user-attachments/assets/e36aab15-bcf6-47c8-808e-0d90ceddabd7" />
<img width="307" alt="image" src="https://github.com/user-attachments/assets/ccca74f1-843e-425e-a77e-360b817cd76f" />
<img width="450" alt="image" src="https://github.com/user-attachments/assets/e0af6423-2b35-47c9-b728-a7402b2ff650" />

</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New
* Karen
* Ken
</p>
<br />
<p>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/83369cbd-0bf6-41f0-8f01-709deefb0c47" />
<img width="450" alt="image" src="https://github.com/user-attachments/assets/07b715b8-4f59-44b8-8458-f3bbad9f38c4" />
<img width="450" alt="image" src="https://github.com/user-attachments/assets/71ff1147-a4f7-41b9-b8bb-d5156cefdb62" />
<img width="450" alt="image" src="https://github.com/user-attachments/assets/27124b8a-0ff6-4c59-90fa-8af9fe5bfea9" />

</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA
* Sev-A (Grace Period: 1 hour, Schedule: 24/7)
* Sev-B (Grace Period: 4 hours, Schedule: 24/7)
* Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<br />
<p>
<img width="450" alt="image" src="https://github.com/user-attachments/assets/d6e259ef-d345-4712-ae44-2c078117634a" />
<img width="450" alt="image" src="https://github.com/user-attachments/assets/a61e9be3-954b-4490-bba0-0023b80223ff" />

</p>
<p>
Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics
* Business Critical Outage
* Personal Computer Issues
* Equipment Request
* Password Reset
* Other
</p>

<p>
