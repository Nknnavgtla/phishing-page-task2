# <h2>Phishing-page-task2</h2>
# 🔐 Phishing Email & Website Analysis – Task 2
Objective:
To analyze a phishing webpage and demonstrate how credentials can be harvested using spoofed login pages.

🧪 Sample Used:
Fake Gmail login page generated using Zphisher on Kali Linux.

<img width="1911" height="930" alt="image" src="https://github.com/user-attachments/assets/7be3cec5-cd82-4420-9a31-dba1115b2f4f" />

---
# 🛡️ Phishing Attack Analysis – Fake Google Login Page
- I Used The Kali Linux In VMWare 
- In That I Used Termainal And
- I Used that zphisner And I Identifies the Phising page
- what else i identified Is ::>
### 🔍 **Phishing Indicators Identified**

| **Indicator**          | **Description**                                                                                                                               |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| **URL Mismatch**       | The page is hosted at `127.0.0.1:8080` instead of the official `accounts.google.com`. This is a clear sign of a spoofed or fake login portal. |
| **Design Imitation**   | The attacker has replicated Google's sign-in UI almost perfectly to deceive users into believing it's legitimate.                             |
| **Email Harvesting**   | Submitted credentials (email and password) are being silently stored in local files such as `auth/ip.txt` and `auth/usernames.dat`.           |
| **No Secure Socket Layer Certificate** | The phishing site does **not** use HTTPS. Lack of SSL encryption is a strong warning sign for users.                                          |
| **Social Engineering** | Users are pressured or manipulated into entering credentials under false pretenses, such as urgency or account risk.                          |

---

### ⚠️ **Conclusion**

This is a textbook example of a phishing attack using a cloned login interface to **harvest user credentials**. The attacker’s goals typically include:

* 🎯 **Credential Theft**: To hijack email or service accounts.
* 🔓 **Unauthorized Access**: To sensitive platforms (email, cloud storage, banking, etc.).
* 🔁 **Attack Chaining**: Using stolen credentials for password resets, identity theft, or launching broader attacks.

---

### 💡 **Security Tips**

* **Always check the URL** before entering credentials.
* Look for the **lock icon (HTTPS)** in the address bar.
* **Never trust** login pages served from local IPs or unfamiliar domains.
* Use **multi-factor authentication (MFA)** to protect your accounts.
* When in doubt, **contact IT/security teams** before proceeding.

---

> ✅ **Stay alert, stay secure. Phishing only works when we let our guard down.**
⚠️ Conclusion:
This demonstrates a typical phishing attack using fake login pages. Attackers use such tactics to:

Steal credentials

Gain unauthorized access to email accounts

Launch further attacks (e.g., password resets, identity theft)

🧰 Tools Used:
Kali Linux
Zphisher

<br>

Use This Website To Find Out The Phishing Website.
```
Localhost (127.0.0.1) for demonstration

- 🧪 VirusTotal Scan
A VirusTotal scan was performed on the phishing webpage HTML file used in this task.

🔗 - VirusTotal Report Link : [View Report](https://www.virustotal.com/gui/file/your-report-link-here)

The scan results confirmed that the file/page mimics a known phishing pattern. Multiple engines detected it as a phishing attempt.
