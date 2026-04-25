# 🖥️ Active Directory Lab (Windows Server 2022)

## 🎯 Project Overview

This project demonstrates the setup and configuration of an Active Directory Domain Controller in a virtual environment using VirtualBox.
It includes domain creation, user management, and Group Policy configuration.

---

## 🛠️ Technologies Used

* Windows Server 2022
* Oracle VirtualBox
* Active Directory Domain Services (AD DS)
* Group Policy Management

---

## 🔧 Lab Setup & Configuration

### 1. Install Windows Server 2022

* Created a Virtual Machine in VirtualBox
* Installed Windows Server 2022

📸
Server Install 
<img width="1020" height="725" alt="Screenshot_25" src="https://github.com/user-attachments/assets/d1007b5c-448e-42eb-afcd-fb511b40dc17" />




---

### 2. Install Active Directory Domain Services

* Opened Server Manager
* Clicked **Add Roles and Features**
* Selected **Active Directory Domain Services**
* Installed required features

📸
AD Install
<img width="1010" height="725" alt="Screenshot_1" src="https://github.com/user-attachments/assets/a6e7ff2b-bb9b-4651-9fd5-327b0e9e9853" />

<img width="947" height="664" alt="Screenshot_2" src="https://github.com/user-attachments/assets/62adf4dd-6711-40da-bf94-ce114657672b" />

---
<img width="868" height="620" alt="Screenshot_3" src="https://github.com/user-attachments/assets/cf5f47cb-2edf-4be8-aae1-871ee665e271" />




---

### 3. Promote Server to Domain Controller

* Clicked **Promote this server to a domain controller**
* Selected **Add a new forest**
* Domain name: `company.local`

📸
Promote DC
<img width="987" height="670" alt="Screenshot_4" src="https://github.com/user-attachments/assets/fb7df02d-70af-40e3-8af8-c44c3da45c21" />

<img width="824" height="596" alt="Screenshot_6" src="https://github.com/user-attachments/assets/349df6ef-464e-4612-9029-d90031dd64dd" />




---

### 4. Configure Domain Controller

* Set DSRM password
* Used default DNS settings
* Completed setup

📸
DSRM Password
<img width="831" height="609" alt="Screenshot_7" src="https://github.com/user-attachments/assets/3060ddff-ee0d-4d26-a59e-cb7decee76d6" />

<img width="823" height="608" alt="Screenshot_8" src="https://github.com/user-attachments/assets/0d405aba-b0a0-44d2-8a90-70da0aa50bbb" />

---
<img width="800" height="592" alt="Screenshot_9" src="https://github.com/user-attachments/assets/cd36ab62-1392-4d97-9c9b-f1277eae08b5" />


---

### 5. Complete Installation & Restart

* Verified settings
* Passed prerequisite check
* Installed and restarted server
  
📸
Restart
<img width="810" height="591" alt="Screenshot_11" src="https://github.com/user-attachments/assets/d93c6082-1afb-48f3-a780-fc7a69aeaa3d" />


<img width="797" height="597" alt="Screenshot_12" src="https://github.com/user-attachments/assets/5f7f5249-f71c-4f1f-b9cb-c062c6ed7b84" />

---
<img width="952" height="653" alt="Screenshot_13" src="https://github.com/user-attachments/assets/bb66c70b-1e23-4fc1-ad0e-f0380d3f75b8" />



---

### 6. Login to Domain

* Logged in as:
  `COMPANY\Administrator`
📸
Admin Login

<img width="995" height="733" alt="Screenshot_14" src="https://github.com/user-attachments/assets/9ddd11bd-7390-4cb8-abd7-e813a0a41738" />


---

### 7. Create Organizational Unit (OU)

* Opened **Active Directory Users and Computers**
* Right click → New → Organizational Unit
* Name: `IT`

📸
Create OU IT

<img width="987" height="713" alt="Screenshot_15" src="https://github.com/user-attachments/assets/1eaa7a88-9d83-4b59-a5f0-7c208b0fabd0" />

---
<img width="851" height="605" alt="Screenshot_16" src="https://github.com/user-attachments/assets/28f11d1b-d6f0-424f-8151-577a8b229ee9" />

---
<img width="807" height="617" alt="Screenshot_17" src="https://github.com/user-attachments/assets/ac875606-93a3-47dc-be51-d49b00572d5c" />



---

### 8. Create Test User

* Inside IT OU → New → User
* Name: Test User
* Username: `test.user`
* Set password
  
📸
Create User
<img width="857" height="655" alt="Screenshot_18" src="https://github.com/user-attachments/assets/19a9eac6-9b52-440a-be13-0c5e38e6b497" />


<img width="651" height="609" alt="Screenshot_19" src="https://github.com/user-attachments/assets/5e119de5-5d27-4bba-8988-a2797746a346" />

---
<img width="878" height="621" alt="Screenshot_20" src="https://github.com/user-attachments/assets/e8dae308-5e84-438c-a045-f3761b894192" />



---

### 9. Configure Group Policy

* Opened **Group Policy Management**
* Edited Default Domain Policy
* Enabled:
  **Allow log on locally → Domain Users + Administrators**
  
📸
Group Policy

<img width="847" height="625" alt="Screenshot_23" src="https://github.com/user-attachments/assets/ec9715f0-0611-4a3f-bdd6-3cdbecf30eb8" />



---

### 10. Apply Group Policy

Command used:

```
gpupdate /force
```

📸
GPUpdate
<img width="719" height="573" alt="Screenshot_26" src="https://github.com/user-attachments/assets/dbc0a713-0d32-4d5f-9bba-9ffc065412d7" />


---

### 11. Test User Login

* Logged in with:
  `COMPANY\test.user`
* Login successful

📸
User Login

<img width="991" height="722" alt="Screenshot_21" src="https://github.com/user-attachments/assets/aa545b18-6e74-467a-b48d-7c011b9b96be" />

---
<img width="1009" height="724" alt="Screenshot_24" src="https://github.com/user-attachments/assets/a22b9988-b625-4081-8524-92f3329df6ed" />



---

## 🧪 Result

* Domain Controller successfully configured
* Organizational Unit created
* User authentication working
* Group Policy applied correctly

---

## 💡 Skills Gained

* Active Directory setup & configuration
* Domain Controller deployment
* User & OU management
* Group Policy configuration
* Troubleshooting login issues

---

## 🚀 Future Improvements

* Join a client machine to the domain
* Configure DNS & DHCP
* Create multiple users and groups
* Apply advanced Group Policies
