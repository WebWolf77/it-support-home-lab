# 📂 Shared Folder Lab

## 🎯 Scenario

A user needs access to a shared folder to view and edit files over the network.

---

## 🛠️ Steps Taken

### 1. Created the folder

📸 Screenshot:
<img width="875" height="640" alt="Screenshot_1" src="https://github.com/user-attachments/assets/606f576d-750f-4dfc-9f4f-be650a6be360" />



👉 A folder named **Shared Folder** was created on the desktop.

---

### 2. Opened sharing settings

📸 Screenshot:
<img width="620" height="627" alt="Screenshot_2" src="https://github.com/user-attachments/assets/b67c4235-5d95-4c09-9c3f-9b13a91d7a06" />



👉 Opened the folder by double-clicking it, then right-clicked and selected **“Properties”**.
Navigated to the **“Sharing”** tab and clicked on **“Advanced Sharing”** to configure the folder sharing settings.

---

### 3. Configured permissions

📸 Screenshot:
<img width="695" height="636" alt="Screenshot_3" src="https://github.com/user-attachments/assets/ac8e1e07-cd3e-4cbe-9623-83a2e9880882" />



👉 The **Everyone** group was added and granted:

* Read 
* Change 
* Full Control 

💡 Interpretation:
All users can access and modify files in the shared folder.

---

### 4. Verified folder is shared

📸 Screenshot:
<img width="656" height="632" alt="Screenshot_4" src="https://github.com/user-attachments/assets/f0dd7389-9eb6-4d24-851f-56d133f69a34" />



👉 The folder is now successfully shared on the network.

---

### 5. Accessed the shared folder

📸 Screenshot:
<img width="887" height="278" alt="Screenshot_5" src="https://github.com/user-attachments/assets/ac78c27a-25f5-4ca3-9470-b1b7fe9bf3c7" />



👉 The shared folder is visible via `\\localhost`, confirming network access.

---

### 6. Tested write access

📸 Screenshots:
<img width="880" height="665" alt="Screenshot_6" src="https://github.com/user-attachments/assets/ab207613-37e7-4e3e-b889-d4e174b5a605" />


---
<img width="842" height="646" alt="Screenshot_7" src="https://github.com/user-attachments/assets/1122770c-d1d0-413f-9b81-de65cb2cee7f" />



👉 A test file was created inside the shared folder by right-clicking in the folder, selecting **“New”** → **“Text Document”**, and naming it **“test”**.

---

## ✅ Result

* Shared folder configured successfully
* Network access working
* Read and write permissions verified

---

## 💡 What I Learned

* How to configure shared folders in Windows
* How to manage permissions (Read / Write / Full Control)
* How to test access using `\\localhost`
* Basic file sharing concepts

## 🧠 Troubleshooting Approach

1. Identified the problem
2. Checked folder sharing status
3. Configured permissions
4. Tested access
5. Verified functionality
   

---
