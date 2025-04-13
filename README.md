# Python SIEM Log Analyzer

A log analysis tool built with python that scans Linux system logs (e.g., `auth.log`) to detect suspicious activities such as failed SSH login attempts, brute-force attacks, and privilege escalation attempts. Built for SIEM use cases and security operations automation.

---

## 🔍 Features

- Parses system logs for:
  - Failed SSH logins
  - Brute force detection (multiple failed logins from one IP)
  - Root access attempts
- Outputs JSON alert summaries
- Easy to extend with more detection rules
  
---

## 📁 Project Structure
python-siem-log-analyzer/ ├── analyzer.py # Main script to parse logs and generate alerts ├── sample_logs/ # Contains sample Linux logs for testing ├── reports/ # Output folder for alert reports ├── README.md # Project documentation ├── requirements.txt # Python dependencies └── .gitignore # Excludes logs and reports from Git

---


---

## 🚀 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/python-siem-log-analyzer.git
   cd python-siem-log-analyzer
   ````
2. **Install dependencies:**
  ```bash
  pip install -r requirements.txt
   ````
3. **Prepare the log file: Ensure that you have a sample log file in the sample_logs/ directory, such as auth.log, containing SSH login attempts.**
4. **Run the script:**
  ```bash
  python analyzer.py
 ```
5. **Check the output: Once the script finishes, it will generate JSON summaries of failed login attempts and suspicious activities in the reports/ directory.**

Author: Samuel Ogunlusi 

