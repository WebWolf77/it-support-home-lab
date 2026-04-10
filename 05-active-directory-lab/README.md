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
<img width="1032" height="1019" alt="Screenshot_25" src="https://github.com/user-attachments/assets/808468a2-2395-4980-be7a-7af442ed17d6" />



---

### 2. Install Active Directory Domain Services

* Opened Server Manager
* Clicked **Add Roles and Features**
* Selected **Active Directory Domain Services**
* Installed required features

📸
AD Install
<img width="1047" height="1019" alt="Screenshot_1" src="https://github.com/user-attachments/assets/5e89e5af-3703-458d-98c3-7ba193907df9" />
<img width="1045" height="1019" alt="Screenshot_2" src="https://github.com/user-attachments/assets/c0be6bf9-6ebd-4060-839f-c87a42d0f889" />
<img width="1046" height="1017" alt="Screenshot_3" src="https://github.com/user-attachments/assets/2042fd17-6220-4621-baf6-b1b5d51ab1bb" />



---

### 3. Promote Server to Domain Controller

* Clicked **Promote this server to a domain controller**
* Selected **Add a new forest**
* Domain name: `company.local`

📸
Promote DC
<img width="1049" height="1020" alt="Screenshot_4" src="https://github.com/user-attachments/assets/9f695a82-ba0c-4e48-bb1c-848e68d0303b" />
<img width="1048" height="1018" alt="Screenshot_6" src="https://github.com/user-attachments/assets/febed1b7-7c3f-4128-b79e-2dfc5f8a0a8e" />



---

### 4. Configure Domain Controller

* Set DSRM password
* Used default DNS settings
* Completed setup

📸
DSRM Password
<img width="1046" height="1022" alt="Screenshot_7" src="https://github.com/user-attachments/assets/25533be4-685b-4c09-991e-13bb2167b2f4" />
<img width="1045" height="1019" alt="Screenshot_8" src="https://github.com/user-attachments/assets/c7e9bbe1-cfa3-4f45-be21-f48c4c634103" />
<img width="1052" height="1020" alt="Screenshot_9" src="https://github.com/user-attachments/assets/4aeea7c3-1be1-40ac-a5c6-7242f314cccd" />

---

### 5. Complete Installation & Restart

* Verified settings
* Passed prerequisite check
* Installed and restarted server
  
📸
Restart
<img width="1046" height="1020" alt="Screenshot_11" src="https://github.com/user-attachments/assets/2ad59e9f-e324-4daf-8ed1-95b1f080e208" />

<img width="1048" height="1020" alt="Screenshot_12" src="https://github.com/user-attachments/assets/7905be36-7697-472b-bdff-78a7401ff7c4" />

<img width="1049" height="1016" alt="Screenshot_13" src="https://github.com/user-attachments/assets/d9ad4573-ae0b-4108-96d4-9168e97bd104" />


---

### 6. Login to Domain

* Logged in as:
  `COMPANY\Administrator`
📸
Admin Login

<img width="1048" height="1019" alt="Screenshot_14" src="https://github.com/user-attachments/assets/991b13de-d32d-401b-a39e-5f735d5616cb" />

---

### 7. Create Organizational Unit (OU)

* Opened **Active Directory Users and Computers**
* Right click → New → Organizational Unit
* Name: `IT`

📸
Create OU IT

<img width="1046" height="1017" alt="Screenshot_15" src="https://github.com/user-attachments/assets/523966df-269d-4822-ae2f-321501caecf8" />

<img width="1047" height="1019" alt="Screenshot_16" src="https://github.com/user-attachments/assets/bc8b4d4d-2a04-43ab-966c-c4ce68c8dee1" />

<img width="1043" height="1019" alt="Screenshot_17" src="https://github.com/user-attachments/assets/6cde73bf-f8e7-4f85-b38a-1c16f8c63b09" />


---

### 8. Create Test User

* Inside IT OU → New → User
* Name: Test User
* Username: `test.user`
* Set password
  
📸
Create User
<img width="1051" height="1022" alt="Screenshot_18" src="https://github.com/user-attachments/assets/d842cf0e-d4a8-447e-8c94-a44823a7b2a4" />

<img width="1047" height="1019" alt="Screenshot_19" src="https://github.com/user-attachments/assets/484dd421-fe19-48aa-b46a-9b3efd5e8057" />

<img width="1052" height="1021" alt="Screenshot_20" src="https://github.com/user-attachments/assets/556cb78a-fb15-4507-b5d3-d331246ea045" />


---

### 9. Configure Group Policy

* Opened **Group Policy Management**
* Edited Default Domain Policy
* Enabled:
  **Allow log on locally → Domain Users + Administrators**
  
📸
Group Policy

<img width="1030" height="1022" alt="Screenshot_23" src="https://github.com/user-attachments/assets/e124c213-8255-4452-91d1-962b197a3e79" />


---

### 10. Apply Group Policy

Command used:

```
gpupdate /force
```

📸
GPUpdate
<img width="1033" height="1019" alt="Screenshot_26" src="https://github.com/user-attachments/assets/d76bfdfb-ad26-4885-a00d-ecd8e39863da" />

---

### 11. Test User Login

* Logged in with:
  `COMPANY\test.user`
* Login successful

📸
User Login

<img width="1051" height="1018" alt="Screenshot_21" src="https://github.com/user-attachments/assets/2ce2d8cb-ec0d-4100-8a42-884b00da9c63" />

<img width="1026" height="1018" alt="Screenshot_24" src="https://github.com/user-attachments/assets/3507a53c-0cbf-4c96-aa25-463d94d20d08" />


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
