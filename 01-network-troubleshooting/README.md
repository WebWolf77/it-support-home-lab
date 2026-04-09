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
<img width="962" height="1019" alt="Screenshot_7" src="https://github.com/user-attachments/assets/d80c68cc-03c9-4b15-8893-1e816d30b9ec" />


### Checked IP configuration, Tested connectivity & Checked DNS 
<img width="1012" height="1018" alt="Screenshot_zweite" src="https://github.com/user-attachments/assets/6a37473a-a71a-4e6c-b064-9dce0d2c6107" />


### The network adapter was disabled. Enabling it restores the connection and resolves the issue. 
<img width="1014" height="1020" alt="Screenshot_9" src="https://github.com/user-attachments/assets/c41408f2-de8c-4559-ad3d-71c391542b3b" />


### Final verification of IP configuration and DNS
<img width="1012" height="1021" alt="Screenshot_dritte" src="https://github.com/user-attachments/assets/9d8b1d03-589f-4cfe-93f0-81251f3893c2" />




## 💡 What I learned
- How to diagnose network issues
- Importance of IP and DNS
- Basic troubleshooting workflow
  
---
## 🧠 Troubleshooting Approach
1. Identify the problem
2. Check IP configuration
3. Test connectivity
4. Analyze DNS
5. Apply fix
6. Verify solution


