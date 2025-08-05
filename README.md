🛡️ Cyber Security Internship – Task 2 
📌 Task Title: Analyze a Phishing Email Sample

🎯 Objective
Identify phishing characteristics in a suspicious email sample using basic analysis tools and techniques.

🧰 Tools Used
- Email client (for viewing sample email)
- Free online header analyzer: [MXToolbox](https://mxtoolbox.com)
- Markdown editor (for report formatting)

📥 Sample Email Overview
- **Subject Line**: “Your Account Has Been Suspended – Immediate Action Required”
- **Sender Address**: `support@paypa1.com`
- **Date Received**: August 5, 2025
- **Attachments**: `Account_Verification.pdf`
- **Links Included**: `http://secure-paypa1.com/login`

🔍 Phishing Indicators Identified
1. Spoofed Sender Address
- Sender uses `paypa1.com` instead of the legitimate `paypal.com`.
- This is a classic example of domain spoofing.

2. Header Discrepancies
- Header analysis reveals:
  - SPF/DKIM authentication failed
  - Routing through suspicious servers
  - “Return-Path” does not match sender domain

 3. Suspicious Links
- Hovering over the login link reveals a mismatched domain: `secure-paypa1.com`
- Not associated with PayPal

 4. Urgent Language
- Phrases like “Immediate Action Required” and “Your account will be permanently suspended” are designed to create panic

 5. Spelling and Grammar Errors
- Examples:
  - “Your account has been suspend due to suspicious activity.”
  - “Please verify your informations.”

 6. Malicious Attachment
- PDF file named `Account_Verification.pdf` urges the user to open and fill in credentials
- Legitimate companies rarely ask for sensitive info via attachments

---

🧠 Summary of Phishing Traits

| Indicator                      | Description                                                |
|-------------------------------|-------------------------------------------------------------|
| Spoofed Email Address         | `support@paypa1.com` mimics PayPal                          |
| Header Authentication Failure | SPF/DKIM failed; suspicious routing                         |
| Mismatched URLs               | Hover reveals fake login domain                             |
| Threatening Language          | Urgency and fear tactics used                               |
| Grammar Errors                | Multiple spelling and syntax mistakes                       |
| Malicious Attachment          | PDF requesting sensitive information                        |

✅ Recommendations
- Do not click on any links or download attachments
- Report the email to your IT/security team
- Block the sender and mark the email as phishing
- Educate users on identifying spoofed domains and urgent language

📚 Key Concepts Covered
- Phishing
- Email spoofing
- Header analysis
- Social engineering
- Threat detection


