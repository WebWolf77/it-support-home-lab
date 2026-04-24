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
<img width="795" height="633" alt="1" src="https://github.com/user-attachments/assets/fbfa1819-efb2-4fdd-bd23-0c4bb85b6b34" />



### ❌ Initial Tests (IP, Ping, DNS Failure)
<img width="920" height="492" alt="Screenshot_1" src="https://github.com/user-attachments/assets/775b71a8-1407-4495-a3e2-28dadd900e87" />



### ⚙️ Network Adapter Disabled
<img width="785" height="587" alt="Screenshot_2" src="https://github.com/user-attachments/assets/6591da65-f1d4-4986-a525-d08fc85425b5" />


### ✅ Final Verification (Connection Restored)
<img width="925" height="602" alt="Screenshot_3" src="https://github.com/user-attachments/assets/9c49e44d-f53e-4ae2-ab92-c31f3cc7f67d" />





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


