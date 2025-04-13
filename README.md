# Python SIEM Log Analyzer

A log analysis tool that scans Linux system logs (e.g., `auth.log`) to detect suspicious activities such as failed SSH login attempts, brute-force attacks, and privilege escalation attempts. Built for entry-level SIEM use cases and security operations automation.

---

## 🔍 Features

- Parses system logs for:
  - Failed SSH logins
  - Brute force detection (multiple failed logins from one IP)
  - Root access attempts
- Outputs JSON alert summaries
- Easy to extend with more detection rules
- Beginner-friendly and SOC-relevant

---

## 📁 Project Structure

