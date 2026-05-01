# DVWA SQL Injection Lab

## 🎯 Objective
To identify and exploit SQL Injection vulnerability using DVWA.

## 🛠 Tools Used
- DVWA (Damn Vulnerable Web Application)
- Browser
- Burp Suite (optional)

## 🧪 Steps Performed
1. Opened DVWA SQL Injection module
2. Entered payload in input field
3. Observed database response

## 💣 Payload Used
1' OR '1'='1

## ✅ Result
- Application returned all user records
- Authentication bypass achieved

## ⚠ Impact
- Unauthorized access
- Data leakage
- Database compromise

## 🔐 Prevention
- Use prepared statements
- Input validation
- Parameterized queries
