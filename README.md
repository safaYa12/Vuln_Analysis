# Vuln_Analysis
# 🌐 Web Application Security Assessment — Nikto Scan

This repository documents my task on performing a **web application vulnerability scan** using **Nikto**, analyzing the scan results, and providing actionable recommendations to address potential security issues.

---

## ✅ Task Objectives

1. **Scan the Web Application**
   - Conducted a **comprehensive scan** of the target web application using the **Nikto** tool.
   - Nikto is an open-source web server scanner that checks for:
     - Dangerous files/CGIs
     - Outdated server software
     - Common misconfigurations
     - Default files or credentials

   **Command Example:**
   ```bash
   nikto -h http://target-webapp.com
