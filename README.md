<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

---

## 🛠️ Post-Installation Configuration

Once osTicket is successfully installed, complete the following configurations to prepare the helpdesk environment for internal use and customer support.

---

### 🔐 Login URLs
- **Admin/Analyst Panel:**  
  `http://localhost/osTicket/scp/login.php`

- **End User Portal:**  
  `http://localhost/osTicket`
![Screenshot 2025-05-27 205131](https://github.com/user-attachments/assets/e035787a-7e15-4997-9506-61b3b66547ce)
![Screenshot 2025-05-28 152152](https://github.com/user-attachments/assets/047f069d-7723-413a-a6d6-0e1f68f8bd73)
---

### 🧭 Agent Panel vs Admin Panel
- **Admin Panel:** Used by system admins to configure osTicket (agents, roles, teams, SLAs, settings).
- **Agent Panel:** Used by support agents to view, manage, and resolve tickets.


---


### 👥 Configure Roles
Group agent permissions with defined roles:
- Navigate to: `Admin Panel → Agents → Roles`
- Create Role: `Supreme Admin`
![Screenshot 2025-05-28 152331](https://github.com/user-attachments/assets/978ade5f-48e9-4a3f-9703-5d6c62a15c2e)
![Screenshot 2025-05-28 152411](https://github.com/user-attachments/assets/1f5e5d33-dfeb-4184-be41-6248c17322bc)
---

### 🏢 Configure Departments
Control ticket visibility and organize teams:
- Navigate to: `Admin Panel → Agents → Departments`
- Add Department: `SysAdmins`

![Screenshot 2025-05-28 152450](https://github.com/user-attachments/assets/4f058cef-c1ee-44b6-8b07-6e91a38b8e49)
![Screenshot 2025-05-28 152537](https://github.com/user-attachments/assets/3f2e04fe-11a6-4ea0-b148-779245e3bc90)



---

### 🤝 Configure Teams
Teams allow agents from multiple departments to collaborate:
- Navigate to: `Admin Panel → Agents → Teams`
- Add Team: `Online Banking`

![Screenshot 2025-05-28 154553](https://github.com/user-attachments/assets/5c0feeb4-69d1-4c23-b951-ac9c5868d5ef)




---

### 🌐 User Access Settings
Control whether users need to register to submit tickets:
- Navigate to: `Admin Panel → Settings → User Settings`
- ❌ **Uncheck**: "Require registration and login to create tickets"
  
![Screenshot 2025-05-28 152753](https://github.com/user-attachments/assets/12032356-7395-478a-8c28-94c15c486d1e)


---

### 🧑‍💼 Configure Agents (Support Staff)
Add internal users who will manage tickets:
- Navigate to: `Admin Panel → Agents → Add New`
- Add:
  - `Jane` (Department: SysAdmins)
  - `John` (Department: Support)

---![Screenshot 2025-05-28 153239](https://github.com/user-attachments/assets/b5a834d4-2e1e-4d5c-beae-77ee888a6c09)


### 🙋‍♂️ Configure Users (Customers)
Add customers who will submit support requests:
- Navigate to: `Agent Panel → Users → Add New`
- Add:
  - `Karen`

![Screenshot 2025-05-28 153421](https://github.com/user-attachments/assets/0ba09209-15d0-4e4e-a0aa-3e75fa11e325)

---

### ⏱️ Configure SLA Plans
Define ticket urgency and response expectations:
- Navigate to: `Admin Panel → Manage → SLA`
- Add:
  - `Sev-A`: Grace Period 1 hour, Schedule 24/7
  - `Sev-B`: Grace Period 4 hours, Schedule 24/7
  - `Sev-C`: Grace Period 8 hours, Business Hours
 
  
![Screenshot 2025-05-28 153648](https://github.com/user-attachments/assets/a476fd6b-bfe2-47a4-a50e-fd9e8f4dba8b)

---

### 📝 Configure Help Topics
Create predefined topics for users to select when submitting tickets:
- Navigate to: `Admin Panel → Manage → Help Topics`
- Add:
  - `Business Critical Outage`
  - `Personal Computer Issues`
  - `Equipment Request`
  - `Password Reset`
  - `Other`

![Screenshot 2025-05-28 155700](https://github.com/user-attachments/assets/fa7d3ddf-d15a-4da7-b986-f7bfbff5ac5d)

---
