# Network Troubleshooting Lab

## 🎯 Scenario
User reports: "No internet connection"

## 🔍 Steps Taken

### 1. Checked IP configuration
Used:
ipconfig

Result:
No valid IP address

### 2. Tested connectivity
ping 8.8.8.8

Result:
Request timed out

### 3. Checked DNS
nslookup google.com

Result:
DNS resolution failed

## 🛠️ Solution
- Found that network adapter was disabled
- Enabled network adapter


## ✅ Result
- Internet connection restored
- Successful ping to google.com

## 📸 Screenshots
### Network disabled 
<img width="1070" height="1021" alt="Screenshot_1" src="https://github.com/user-attachments/assets/34c5337a-8fc2-40ee-96d8-174e7681f749" />

### Checked IP configuration Tested connectivity Checked DNS 
<img width="1088" height="1013" alt="Screenshot_2" src="https://github.com/user-attachments/assets/0fe99541-f9f0-4328-a2c9-ce2bcbf53a04" />

### The network adapter was disabled. Enabling it restores the connection and resolves the issue. 
<img width="1091" height="1020" alt="Screenshot_3" src="https://github.com/user-attachments/assets/6161f620-56ad-4e41-b429-0f4358d96c14" />

### Last check IP configuration & checked DNS 
<img width="1090" height="1013" alt="Screenshot_4" src="https://github.com/user-attachments/assets/99a4f4a7-6a8f-414a-9eec-6344cfc0bdde" />



## 💡 What I learned
- How to diagnose network issues
- Importance of IP and DNS
- Basic troubleshooting workflow
