# dvwa-vapt-project
Web Application Penetration Testing using DVWA &amp; OWASP ZAP

# 🔐 DVWA Web Application Security Testing Project

## 📌 Overview

This project demonstrates **Web Application Penetration Testing** using **DVWA (Damn Vulnerable Web Application)** and **OWASP ZAP**.
The goal is to identify and exploit vulnerabilities from the **OWASP Top 10**.

---

## 🛠️ Tools Used

* DVWA (Vulnerable Web App)
* OWASP ZAP (Security Scanner)

---

## ⚙️ Methodology

1. Setup DVWA in local environment (XAMPP)
2. Performed **Spidering** using OWASP ZAP
3. Conducted **Active Scan**
4. Identified vulnerabilities from alerts
5. Manually validated SQL Injection and XSS

---

## 🔍 Vulnerabilities Demonstrated

### 💉 SQL Injection

* **Payload:** `1' OR '1'='1`
* **Impact:** Unauthorized access to database, data leakage

![SQL Injection](Snapshots/sql.jpg)

---

### ⚡ Cross-Site Scripting (XSS)

* **Payload:** `<script>alert('XSS')</script>`
* **Impact:** Execution of malicious JavaScript in user browser

![XSS](Snapshots/xss.jpg)

---

## 📊 Scan Report

[Download OWASP ZAP Report](Scanning_Report.pdf)

---

## 🚨 Key Findings

* Application is vulnerable to **SQL Injection**
* Improper input validation leads to **XSS attacks**
* Security controls are weak at low security level

---

## ⚠️ Disclaimer

This project was performed in a **controlled lab environment (DVWA)** for educational purposes only.
No real-world systems were targeted.
