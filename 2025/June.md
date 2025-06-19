# 📘 June 2025 - Daily Log

## 🗓️ June 19, 2025
- ✅ **What I Learned:** Completed the course of "Introduction to Cybersecurity-Cisco"
- 🔗 **Source:** 
- 🕒 **Time Spent:** 
- 📝 **Notes:**


## 🗓️ June 18, 2025
- ✅ **What I Learned:** Vulnerabilities in password based logins
- 🔗 **Source:** 
- 🕒 **Time Spent:** 
- 📝 **Notes:**

  
## 🗓️ June 17, 2025
- ✅ **What I Learned:** Started Course of Application Vulnerabilities
    - Meaning of authentication
    - Difference between authentication and authorization
    - How weak authentication can lead to vulnerabilities
    - The risks and impact of using poor authentication methods
    - Issues with password-based login systems (like brute-force flaws)
- 🔗 **Source:** PortSwigger Web Security Academy | Application Vulnerabilities 
- 🕒 **Time Spent:** 3-4 hours
- 📝 **Notes:**
     - Authentication confirms user identity; authorization gives access.
     - Attackers exploit poor logic in login systems.
     - IP blocking can be bypassed using successful logins in between.
     - Password-based systems need smarter protections (rate-limiting, CAPTCHA, MFA).
     - Used Burp Suite and Python to automate a brute-force bypass.

## 🗓️ June 16, 2025
- ✅ **What I Learned:** Completed the final two modules in the Server-Side Vulnerabilities path:
     - OS Command Injection
     - SQL Injection
- 🔗 **Source:** PortSwigger Web Security Academy (Apprentice Level, 52/52 Labs Completed)
     - Labs related to OWASP Top 10 vulnerabilities
- 🕒 **Time Spent:** ~2 hours
- 📝 **Notes:**
     - In OS Command Injection labs, used command chaining and encoding bypasses to execute system commands remotely. Learned difference between blind and visible injection responses.
     - In SQL Injection labs, bypassed login authentication using SQLi payloads like `administrator'--` and tested multiple encoding and commenting strategies.
     - Reinforced skills in Burp Suite (Proxy, Repeater, and manual payload crafting).
     - Completing this path gave deep practical insight into high-impact server-side vulnerabilities and how they’re exploited in real-world apps.

## 🗓️ June 15, 2025 - On Leave

## 🗓️ June 14, 2025 - On Leave

## 🗓️ June 13, 2025
- ✅ **What I Learned:** Exploited insecure file upload by bypassing MIME type validation to execute a PHP web shell.
- 🔗 **Source:** PortSwigger Web Security Academy
     - Labs related to OWASP Top 10 vulnerabilities
- 🕒 **Time Spent:** ~2.5 hours with multiple failed attempts before success
- 📝 **Notes:**
  - Used Burp Suite to change Content-Type to image/jpeg in a .php upload.
  - Accessed the uploaded file via /files/avatars/exploit.php to read /home/carlos/secret.
  - Learned how weak server-side checks can lead to RCE.
  - Reinforced how dangerous improper file validation can be in real-world apps.
  - Great hands-on learning of file upload exploitation and Burp Repeater manipulation.



## 🗓️ June 12, 2025
- ✅ **What I Learned:**
    - Server-Side Request Forgery (SSRF)
    - SSRF Attack Techniques & Lab Exploitation
    - Unrestricted File Upload Vulnerabilities
    - Remote Code Execution via Web Shells
- 🔗 **Source:** PortSwigger Web Security Academy
     - Labs related to OWASP Top 10 vulnerabilities
- 🕒 **Time Spent:** 2–3 hours
- 📝 **Notes:**
    - Validate MIME type and file content server-side
    - Store uploaded files outside web root
    - SSRF + File Upload often chained for deeper exploitation
    - Tools used: Burp Suite (Proxy, Repeater, Intruder)

  
## 🗓️ June 11, 2025
- ✅ **What I Learned:**
  - Explored **OSWP Top 10** (focus on **Authentication** & **Access Control flaws**)
  - Practiced **username enumeration** via response-based error analysis
  - Performed **password brute-force attacks** using Burp Suite & Python (`requests`)
  - Understood and identified **Horizontal vs Vertical Privilege Escalation**, and **Bypassing 2FA**
  - Set up and used **Burp Suite** for request interception, Intruder, and response analysis
- 🔗 **Source:** PortSwigger Web Security Academy
     - Labs related to OWASP Top 10 vulnerabilities
- 🕒 **Time Spent:** 2–3 hours
- 📝 **Notes:**
  - Authentication & access controls are often misconfigured — easy to exploit with wordlists
  - Response differences are key to enumeration
  - Burp + scripting = powerful combo for automating attacks


## 🗓️ June 10, 2025
- ✅ **What I Learned:** Started a new journey of OWASP Top 10 Vulnerabilities
     - Web application vulnerabilities like Path Traversal, Unprotected Admin Panels, JavaScript Info Disclosure, Insecure Cookie-based Role Control, and Horizontal Privilege Escalation using GUIDs.
     - How to identify and exploit these issues using browser, Burp Suite, and logic-based access tampering.
- 🔗 **Source:** PortSwigger Web Security Academy
     - Labs related to OWASP Top 10 vulnerabilities
- 🕒 **Time Spent:** 3–4 hours
- 📝 **Notes:**
     - Path Traversal: Accessed server files using ../ in parameters
     - Admin Panel Exposure: Found hidden panels via robots.txt and JS
     - Cookie Role Escalation: Modified Admin=false to Admin=true using Burp response editor
     - Privilege Escalation (GUID): Accessed carlos's data by replacing my GUID with his in the URL
     - Importance of server-side access control and not trusting client inputs

  
## 🗓️ June 9, 2025
- ✅ **What I Learned:** 
- 🔗 **Source:** 
- 🕒 **Time Spent:** 
- 📝 **Notes:**
 

## 🗓️ June 8, 2025
- ✅ **Task 1:** Deloitte Australia Cyber Job Simulation on Forage
- ✅ **What I Learned:** Computer Networks, Log Inspection, Web Security
- 🔗 **Source:** Deloitte
- 🕒 **Time Spent:** 50 minutes
- 📝 **Notes:**
  - Completed a job simulation involving reading web activity logs
  - Supported a client in a cyber security breach
  - Answered questions to identify suspicious user activity

