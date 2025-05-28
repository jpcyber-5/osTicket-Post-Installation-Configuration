---

## 🛠️ Post-Installation Configuration

Once osTicket is successfully installed, complete the following configurations to prepare the helpdesk environment for internal use and customer support.

---

### 🔐 Login URLs
- **Admin/Analyst Panel:**  
  `http://localhost/osTicket/scp/login.php`

- **End User Portal:**  
  `http://localhost/osTicket`

---

### 🧭 Agent Panel vs Admin Panel
- **Admin Panel:** Used by system admins to configure osTicket (agents, roles, teams, SLAs, settings).
- **Agent Panel:** Used by support agents to view, manage, and resolve tickets.

---

### 👥 Configure Roles
Group agent permissions with defined roles:
- Navigate to: `Admin Panel → Agents → Roles`
- Create Role: `Supreme Admin`

---

### 🏢 Configure Departments
Control ticket visibility and organize teams:
- Navigate to: `Admin Panel → Agents → Departments`
- Add Department: `SysAdmins`

---

### 🤝 Configure Teams
Teams allow agents from multiple departments to collaborate:
- Navigate to: `Admin Panel → Agents → Teams`
- Add Team: `Online Banking`

---

### 🌐 User Access Settings
Control whether users need to register to submit tickets:
- Navigate to: `Admin Panel → Settings → User Settings`
- ❌ **Uncheck**: "Unregistered users can create tickets"
- ✅ **Enable**: "Require registration and login to create tickets"

---

### 🧑‍💼 Configure Agents (Support Staff)
Add internal users who will manage tickets:
- Navigate to: `Admin Panel → Agents → Add New`
- Add:
  - `Jane` (Department: SysAdmins)
  - `John` (Department: Support)

---

### 🙋‍♂️ Configure Users (Customers)
Add customers who will submit support requests:
- Navigate to: `Agent Panel → Users → Add New`
- Add:
  - `Karen`
  - `Ken`

---

### ⏱️ Configure SLA Plans
Define ticket urgency and response expectations:
- Navigate to: `Admin Panel → Manage → SLA`
- Add:
  - `Sev-A`: Grace Period 1 hour, Schedule 24/7
  - `Sev-B`: Grace Period 4 hours, Schedule 24/7
  - `Sev-C`: Grace Period 8 hours, Business Hours

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

---
