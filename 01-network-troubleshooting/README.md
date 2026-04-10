# Network Troubleshooting Lab

## 🎯 Scenario
User reports: "No internet connection"

## 🔍 Steps Taken

### 1. Check IP Configuration
**Command:**
```bash
ipconfig
```

**Result:**
- No valid IP address detected  

---

### 2. Test Network Connectivity
**Command:**
```bash
ping 8.8.8.8
```

**Result:**
- Request timed out  
- 100% packet loss  

---

### 3. Check DNS Resolution
**Command:**
```bash
nslookup google.com
```

**Result:**
- DNS server not responding  
- Name resolution failed  

---

## 🛠️ Root Cause
- The **network adapter was disabled**

---

## 🔧 Solution
- Opened **Network Connections**  
- Right-clicked Ethernet adapter  
- Clicked **Enable**

---

## 📈 Result
- Internet connection restored  
- Valid IP address assigned  
- Successful ping to google.com  

--

## 📸 Screenshots
### 🔌 Network Status – Not Connected
<img width="962" height="1019" alt="Screenshot_7" src="https://github.com/user-attachments/assets/d80c68cc-03c9-4b15-8893-1e816d30b9ec" />


### ❌ Initial Tests (IP, Ping, DNS Failure)
<img width="1012" height="1018" alt="Screenshot_zweite" src="https://github.com/user-attachments/assets/6a37473a-a71a-4e6c-b064-9dce0d2c6107" />


### ⚙️ Network Adapter Disabled
<img width="1014" height="1020" alt="Screenshot_9" src="https://github.com/user-attachments/assets/c41408f2-de8c-4559-ad3d-71c391542b3b" />


### ✅ Final Verification (Connection Restored)
<img width="1012" height="1021" alt="Screenshot_dritte" src="https://github.com/user-attachments/assets/9d8b1d03-589f-4cfe-93f0-81251f3893c2" />




## 💡 Key Learnings
- How to troubleshoot network issues step-by-step  
- Importance of IP configuration and DNS  
- How to identify the root cause quickly  

---

## 🧠 Troubleshooting Methodology
1. Identify the problem  
2. Check IP configuration  
3. Test connectivity  
4. Analyze DNS  
5. Identify root cause  
6. Apply fix  
7. Verify solution  

---

## 🚀 Why This Project Matters
This lab demonstrates:
- Real-world IT support troubleshooting  
- Use of essential networking tools (`ipconfig`, `ping`, `nslookup`)  
- Logical problem-solving approach used in Helpdesk roles  


