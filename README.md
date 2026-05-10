# DVWA SQL Injection Vulnerability Assessment

## Overview
This project demonstrates the identification and exploitation of a **SQL Injection vulnerability** in the **Damn Vulnerable Web Application (DVWA)** using **Kali Linux**.

The objective of this project is to understand how improper input validation can lead to database compromise and unauthorized data access.

---

## Project Information

| Category | Details |
|----------|----------|
| Application | DVWA (Damn Vulnerable Web Application) |
| Platform | Kali Linux |
| Database | MariaDB |
| Vulnerability | SQL Injection |
| Security Level | Low |
| Testing Type | Web Application Penetration Testing |

---

## Objective
- Understand SQL Injection vulnerabilities
- Perform vulnerability assessment in DVWA
- Exploit insecure SQL queries
- Learn secure coding and remediation techniques
- Create professional VAPT documentation

---

## Tools Used
- Kali Linux
- DVWA
- MariaDB
- Firefox Browser
- Burp Suite (Optional)

---

## Vulnerability Description

SQL Injection occurs when user-controlled input is directly included in SQL queries without proper sanitization or validation.

Attackers can manipulate backend database queries to:
- Access sensitive information
- Bypass authentication
- Dump database contents
- Modify or delete records

---

## Lab Setup

```bash
OS: Kali Linux
Target: DVWA
URL: http://127.0.0.1/dvwa
Database: MariaDB
