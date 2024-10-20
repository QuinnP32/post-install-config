## osTicket Post-Installation Configuration

### Introduction
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket Post-Installation Configuration</h1>
<p>This tutorial provides a step-by-step guide to configuring your osTicket instance after installation for optimal functionality.</p>

### Access URLs
* **Admin/Analyst Login:** http://localhost/osTicket/scp/login.php
* **End Users:** http://localhost/osTicket

### Configuration Steps
#### 1. Roles and Permissions
* **Configure Roles:** Admin Panel -> Agents -> Roles. Create roles like "Ultimate Admin" to define permissions.

![image](https://github.com/user-attachments/assets/4f6af205-afee-4e65-a05a-9f9702476d5e)

* **Configure Departments:** Admin Panel -> Agents -> Departments. Create departments like "SysAdmins", "Help Desk", and "Networking" to categorize tickets.

![image](https://github.com/user-attachments/assets/42553631-b806-430c-a3ce-42e6136e1e8f)

* **Configure Teams:** Admin Panel -> Agents -> Teams. Create teams to group agents from different departments.

![image](https://github.com/user-attachments/assets/14f94c3b-ee3b-4d9b-b76f-5f8e33069790)

#### 2. User Management
* **Allow Public Ticket Creation:** Admin Panel -> Settings -> User Settings. Uncheck "Unregistered users can create tickets".

![image](https://github.com/user-attachments/assets/3b42e967-0a27-49b5-a407-b16e7a99bdb7)

* **Configure Agents:** Admin Panel -> Agents -> Add New. Add agents like Jane (Dept: SysAdmins) and John (Dept: Support).

![image](https://github.com/user-attachments/assets/38f0e393-1da0-4139-8c67-cad22239f064)

* **Configure Users:** Agent Panel -> Users -> Add New. Add users like Karen and Ken.

![image](https://github.com/user-attachments/assets/bdc8d56e-3c02-49a7-ab39-c550c2b50505)

#### 3. SLA Configuration
* **Create SLAs:** Admin Panel -> Manage -> SLA. Create SLAs like Sev-A (1 hour), Sev-B (4 hours), and Sev-C (8 hours, business hours).

![image](https://github.com/user-attachments/assets/be15206f-a66c-4bfc-863a-1d2e145af1a9)

#### 4. Help Topics
* **Configure Help Topics:** Admin Panel -> Manage -> Help Topics. Add topics like "Business Critical Outage", "Personal Computer Issues", etc.

![image](https://github.com/user-attachments/assets/d169a61e-0376-419c-b508-5ccc25b77fca)

**FIN!**
