# 🔍 Python SIEM Log Analyzer  

A simple Python tool to **detect hacker attacks** in server logs. Perfect for cybersecurity beginners!  

## 🛡️ What It Detects  
- **Brute-force attacks** (Multiple failed logins)  
- **SQL injection attempts** (e.g., `' OR 1=1--`)  
- **Suspicious IPs** (Optional: Add IP blacklists)  

## 🖥️ How to Use  
1. **Install Python** (if you haven’t):  
   - Download: [python.org](https://www.python.org/downloads/)  

2. **Run the analyzer**:  
   ```bash
   python log_analyzer.py /var/log/auth.log
