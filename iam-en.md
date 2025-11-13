# 🆔 Identity and Access Management (IAM)

Identity and Access Management (IAM) is a critical cybersecurity discipline that deals with the **protection of digital identities** and the control of user access permissions within an IT system. The goal is to ensure that only the **right people (or machines)** access the right resources, at the right time.

With the rise of remote work, cloud computing, and Artificial Intelligence (AI), the attack surface has expanded, and IAM has become essential: 30% of cyberattacks involve the theft of valid accounts.

---

## 🔑 Four Essential Pillars of IAM

Effective IAM implementations rest on four interconnected components:

1.  **Administration (Lifecycle):** The process of **securely creating, maintaining, and retiring** digital identities (human and non-human users) in a central database. It defines who and what is in the system and their basic rights.
2.  **Authentication:** The process that **verifies the user's identity** upon login. Advanced methods like **Multi-Factor Authentication (MFA)** are crucial for increasing security, requiring more than one credential (e.g., password + phone code).
3.  **Authorization:** After authentication, this process **grants the appropriate level of access** to a resource. It is typically based on the **principle of least privilege**, where the user only receives the permissions strictly necessary to perform their job (e.g., Role-Based Access Control - RBAC).
4.  **Auditing:** The continuous monitoring of user activities to **ensure regulatory compliance** and identify whether attackers or authorized users are abusing their privileges.

---

## 🛠️ Key Solutions and Technologies

IAM tools seek to simplify and automate access control through various solutions:

* **Single Sign-On (SSO):** Allows the user to access multiple applications with **only one set of login credentials**.
* **Adaptive Authentication (Risk-Based):** Uses **AI and Machine Learning (ML)** to analyze the context of a login (location, device) and require more authentication factors if the risk is higher.
* **Control of Access (Different Frameworks):** In addition to RBAC, there is **MAC** (mandatory, based on clearance levels) and **ABAC** (based on user, object, and action attributes).
* **Privileged Access Management (PAM):** Specific tools to protect **highest-risk accounts** (system administrators), using vaults and just-in-time access protocols.
* **Identity Federation:** Allows disparate systems to share identity information (e.g., using a Google login for a new application).
* **IDaaS (Identity as a Service):** Cloud-based IAM solutions (SaaS), ideal for complex and distributed networks.

---

## 🔬 IAM and the Future Landscape

* **Identity Fabric:** Organizations are investing in architectures that **unify all identity systems** into an integrated network, using holistic IAM tools to simplify management and strengthen security.
* **IAM and AI:** AI (especially generative AI) increases the number of **non-human identities** on the network (AI Agents), making PAM essential for protecting these new accounts. Conversely, AI is used positively in IAM tools for risk analysis, compliance control, and user verification.

---

## 🔗 Source

The information contained in this summary was compiled from article published by **Matthew Kosinski** and **Amber Forrest** on **IBM Think**.

* **What is IAM (Identity and Access Management)?:** https://www.ibm.com/br-pt/think/topics/identity-access-management
