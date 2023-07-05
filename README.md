API Security Testing Checklist

This checklist created based on [OWASP Top 10 API Security Risks – 2023](https://owasp.org/API-Security/editions/2023/en/0x11-t10/) and can be used as a guidance during Pentest an API. 

---
#### API1 - Broken Object Level Authorization

- [ ] Test Insecure Direct Object Reference (IDOR)
- [ ] Test Randomly Generated GUIDs as Object
Identifiers for User Requests
 
---
#### API2 - Broken Authentication
- [ ] Test Default Credentials
- [ ] Test Weak Lock Out Mechanism
- [ ] Test Bypassing Authentication Schema
- [ ] Test Weak Password Policy
- [ ] Test Credential Recovery or Forget Password
- [ ] Test Anti Brute-Force Mechanism Implementation

---
#### API3 - Broken Object Property Level Authorization
- [ ] Test Sensitive Data Exposure on Properties of an Object 
---

#### API4 - Unrestricted Resource Consumption
- [ ] Test Execution Timeouts
- [ ] Test Maximum Upload File Size
- [ ] Test Number of Operations to Perform in a Single API Client Request
- [ ] Test Number of Records Per Page to Return in a Single Request-Response
- [ ] Test Rate Limit Implementation
---

#### API5 - Broken Function Level Authorization
- [ ] Test Bypassing Authorization Schema
- [ ] Test Privilege Escalation
- [ ] Test HTTP Method Modification
---
#### API6 - Unrestricted Access to Sensitive Business Flows
- [ ] Test Business Logic Data Validation
- [ ] Test Ability to Forge Requests
- [ ] Test Circumvention of Work Flows
---
#### API7 - Server Side Request Forgery	Server-Side
- [ ] Test Fetching Remote Resources
- [ ] Test User Supplied URL
- [ ] Test HTTP Redirection
- [ ] Test URL Schemes and Ports
---
#### API8 - Security Misconfiguration
- [ ] Test HTTP Methods
- [ ] Test Transport Layer Security (TLS) Settings
- [ ] Test Cross-Origin Resource Sharing (CORS) Policy
- [ ] Test Stack Traces
- [ ] Test Improper Error Handling
- [ ] Test Security or Cache Control Directives
- [ ] Test Cloud Storage
- [ ] Test File Permission
- [ ] Test HTTP Strict Transport Security

---
#### API9 - Improper Inventory Management
- [ ] Test API Environment
- [ ] Test API version
- [ ] Test Network Access to the API
- [ ] Test Sensitive Data Flow
- [ ] Test API Documentation

---
#### API10 - Unsafe Consumption of APIs
- [ ] Test Data Encryption on the Network
- [ ] Test Timeout Implementation
- [ ] Test Rate Limit Implementation
- [ ] Test Request Redirection
- [ ] Test Data Validation & Sanitation


### To Do : 

- Create guidance for each checklist
- Create checklist on spread sheet

### Contribution

Please contribute to this project by :
1. Forking this repository
2. Creating some changes
3. Submitting pull request
