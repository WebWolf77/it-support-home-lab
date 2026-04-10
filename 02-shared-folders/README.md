# 📂 Shared Folder Lab

## 🎯 Scenario

A user needs access to a shared folder to view and edit files over the network.

---

## 🛠️ Steps Taken

### 1. Created the folder

📸 Screenshot:
<img width="991" height="1016" alt="Screenshot_esrte" src="https://github.com/user-attachments/assets/99af88e0-7239-4318-b267-386b571ec1b4" />


👉 A folder named **Shared Folder** was created on the desktop.

---

### 2. Opened sharing settings

📸 Screenshot:
<img width="994" height="1013" alt="Screenshot_5zweite" src="https://github.com/user-attachments/assets/bbfc65ab-f983-459a-9147-6b08bfc6f6b3" />


👉 Opened the folder by double-clicking it, then right-clicked and selected **“Properties / Eigenschaften”**.
Navigated to the **“Sharing / Freigabe”** tab and clicked on **“Advanced Sharing / Erweiterte Freigabe”** to configure the folder sharing settings.

---

### 3. Configured permissions

📸 Screenshot:
<img width="963" height="1017" alt="Screenshot_1" src="https://github.com/user-attachments/assets/a4ae17e0-dec4-43d6-a347-0989ff41f67e" />


👉 The **Everyone (Jeder)** group was added and granted:

* Read / Lesen
* Change / Ändern
* Full Control / Vollzugriff

💡 Interpretation:
All users can access and modify files in the shared folder.

---

### 4. Verified folder is shared

📸 Screenshot:
<img width="963" height="1019" alt="Screenshot_6" src="https://github.com/user-attachments/assets/9dcd2cfa-23c6-470d-be08-311b8e915b34" />


👉 The folder is now successfully shared on the network.

---

### 5. Accessed the shared folder

📸 Screenshot:
<img width="959" height="1020" alt="Screenshot_5" src="https://github.com/user-attachments/assets/9db89703-34fa-468c-bc36-90cd88aa78bd" />


👉 The shared folder is visible via `\\localhost`, confirming network access.

---

### 6. Tested write access

📸 Screenshots:
<img width="995" height="957" alt="Screenshot_2" src="https://github.com/user-attachments/assets/e2daf0c1-16cd-46cd-a709-55467faf9b9c" />
<img width="995" height="1015" alt="Screenshot_4" src="https://github.com/user-attachments/assets/67f594fc-ac3f-495d-bd3d-f23f9ec88ca4" />


👉 A test file was created inside the shared folder by right-clicking in the folder, selecting **“New / Neu”** → **“Text Document / Textdokument”**, and naming it **“test”**.

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
