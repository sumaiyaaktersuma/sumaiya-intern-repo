# Data Privacy & Confidentiality – Reflection

## Goal
Understand how to handle sensitive data responsibly and follow Focus Bear’s privacy and confidentiality policies.


## Why is this important?
Focus Bear collects and processes personal data (emails, habits, subscription info, device details, etc.) in line with GDPR requirements. Mishandling data can lead to breaches, legal consequences, and loss of trust. As a Cybersecurity Analyst Intern, my role is directly tied to ensuring this data remains secure and protected at all times.

## Research & Learn

**Types of Confidential Data at Focus Bear**  
[Type of data](image-6.png)
- **Identification Data:** Emails, phone numbers, login details (stored securely via Auth0 & Zoho).  
- **Social & Lifestyle Data:** Habits created in the app (double encrypted).  
- **Academic/Professional Data:** Occupation details (stored anonymously).  
- **Commercial/Marketing Data:** Emails/WhatsApp for feature updates (opt-out available).  
- **Technical Data:** Device, OS, crash logs (anonymized).  
- **Financial Data:** Payment info (handled by Stripe, RevenueCat, Paddle).  
- **Special Category Data:** ADHD/health info, religious habits (encrypted & anonymized).  

**Best Practices for Handling Confidential Data**  
- Respect **GDPR principles**: data minimization, purpose limitation, fairness, transparency.  
- Share only with **trusted processors** (e.g., AWS, Stripe, Cloudflare, OpenAI).  
- Always use **secure systems** for access (no personal accounts, MFA required).  
- Store and process only what is **necessary**.  
- Report and document any **suspected breach** immediately to the DPO (by Data).  

**How to Respond to a Data Breach**  
1. Report immediately to **privacy@focusbear.io** or the **DPO (dpo@bydata.eu)**.  
2. Document what happened (time, systems affected, data involved).  
3. Contain the issue (stop sharing/exposure).  
4. Assist with GDPR reporting obligations to Supervisory Authorities.  

## Reflection

**Steps I Can Take to Handle Data Securely in Daily Tasks**  
- Always store files in a company-approved, encrypted location.  
- Verify logs and images again before distributing (deleting user information and tokens).  
- Never send private information across unprotected channels or personal devices.  
- Restrict access to private information by using the **least privilege principle**.  

**Safe Practices for Storage, Sharing & Disposal**  
- **Store:** Encrypted cloud systems (AWS, Auth0, Zoho).  
- **Share:** Only via secure internal channels (GitHub, Slack, encrypted email).  
- **Dispose:** Permanently delete data or anonymize when no longer needed.  
[name](image-7.png)
**Common Mistakes & How to Avoid Them**  
- Unintentionally revealing user information in logs or screenshots => check before sharing.  
- Reused credentials or weak passwords → require MFA and strong passwords.  
When using personal accounts or tools, always use platforms that have been approved.  


## Task

**One Habit I Will Develop:** To make sure no private user information or identifiers are shown, I will **check every screenshot and log before sharing**.  

**One Important Takeaway:**  
I've learned the value of **data minimisation** and **purpose limitation** from the Privacy Policy, which states that only the bare minimum of data required for a certain purpose should be collected and used. I'll put this into practice by constantly anonymizing where feasible and minimising needless data collecting during security testing.
