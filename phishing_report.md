## 📨 Email Header Analysis (Using MXToolbox)

**From**: "PayPal Support" <support@paypa1.com>  
**Subject**: Urgent: Account Suspension Notice

##  Suspicious Link Analysis

**URL Scanned**: http://paypal.verify-update-security.com/

**Tool Used**: VirusTotal (https://www.virustotal.com/)

###  Findings:
- **0/97 antivirus engines** flagged it as malicious
- **Trustwave** vendor flagged it as **Suspicious**
- The domain is clearly **not an official PayPal site**
- URL structure and purpose are **typical of phishing sites**


**Tool Used**: [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)

###  Findings:
- ⚠️ **Spoofed Email**: Domain `paypa1.com` is fake (pretending to be `paypal.com`)
- ⚠️ **Urgent Language**: "Urgent: Account Suspension Notice" — pressurizes the reader
- ❌ **Missing SPF/DKIM** authentication results — not a trusted sender
- ⚠️ **Phishing Link**: `http://paypal.verify-update-security.com` is a fake PayPal subdomain

###  Conclusion:
The email shows clear signs of phishing: spoofed domain, no authentication, fake links, and urgency. This email should not be trusted.
