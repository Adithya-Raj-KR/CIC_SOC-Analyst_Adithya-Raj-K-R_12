# Day 12 – Detection Rules & Use Case Development

## Objective
Understand how SOC analysts create detection rules and build use cases to identify cyber threats proactively.

---

## Detection Rule
A detection rule is a condition used in SIEM to identify suspicious activity.

### Example:
IF failed_login_attempts > 5
FROM same IP
WITHIN 2 minutes
THEN alert: Possible Brute Force Attack

---

##  Use Case
A use case defines what to monitor, how to detect, and how to respond.

### Example: Brute Force Detection
- Data Source: Authentication Logs  
- Condition: Multiple failed logins  
- Logic: >5 attempts in short time  
- Response: Alert + Block IP  

---

## Workflow
Logs → SIEM → Rule → Alert → Investigation → Response  

---

##  MITRE Mapping
- Brute Force → Credential Access  
- Phishing → Initial Access  
- Malware → Execution  

---

## Best Practices
- Reduce false positives  
- Use clear conditions  
- Continuously improve rules  
- Map detections to MITRE  

---

##  Conclusion
This session helped in understanding how detection rules and use cases are used to proactively detect and respond to cyber threats.

---

## Author
**Adithya Raj K R**
