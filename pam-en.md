# 🆔 Privileged Access Management (PAM)

Privileged Access Management (PAM) is the cybersecurity discipline focused on **governing and protecting accounts** that have **higher access permissions** than those of a standard user. Elevated privilege can belong to human users (administrators) or non-human users (applications, machines).

PAM is an **essential subset of IAM**, focused on stricter protection. Privileged accounts are high-value targets for hackers and insider threats; the hijacking of these accounts is currently the most common cyberattack vector.

---

## 🔑 Three Essential Pillars of PAM

PAM strategies combine processes and tools to control how privileges are assigned, accessed, and used, focusing on:

1.  **Privileged Account Management:** Oversees the lifecycle of these accounts (creation, provisioning, and retirement). The goal is to **reduce the number of privileged accounts** and centralize credentials in a **password vault** for secure access.
    * *Examples:* Domain administrator accounts, service accounts, root accounts.
2.  **Privilege Management:** Implements **Just-in-Time (JIT)** access models, replacing perpetual privileges. Users receive elevated permissions only **for the limited time and specific task** they need to perform (JIT Privilege Elevation).
3.  **Privileged Session Management (PSM):** Actively monitors privileged activities. PSM tools **track and record** (event logs and video) everything the user does with the privilege, aiding in the detection of suspicious activities and the creation of audit trails.

---

## 🛠️ Solutions and Use Cases

PAM is crucial for mitigating risks, as breaches using stolen credentials are among the most expensive. PAM solutions simplify the process and support the following areas:

* **Identity Attack Surface Reduction:** The use of **credential vaults** and the JIT **least-privilege model** make credential theft difficult and restrict lateral movement by attackers.
* 
* **Identity Sprawl Management:** PAM controls the explosion of new **non-human identities** (IoT, AI, cloud services) that have high privileges and often have poorly protected credentials.
* **Regulatory Compliance:** PAM tools enforce **granular access privileges** and produce audit trails so organizations can prove access control to sensitive data.
* **Secrets Management (DevOps):** Stores secrets (SSH keys, APIs) in a centralized vault instead of leaving them hardcoded or in plain text. Credentials can be **automatically rotated** after use.
* **PAM and AI:** The technology is incorporating AI for **risk-based authentication** (dynamically changing login requirements) and analyzing session logs to detect suspicious activities.

---

## 🔗 Source

The information contained in this summary was compiled from article published by **Matthew Kosinski** on **IBM Think**.

* **What is Privileged Access Management (PAM)?:** https://www.ibm.com/br-pt/think/topics/privileged-access-management
