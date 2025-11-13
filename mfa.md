![alt text](https://img.icons8.com/?size=32&id=0raNoKwBezGl&format=png ) 
# 🔑 Autenticação Multifator (MFA)

A Autenticação Multifator (MFA) é uma disciplina de segurança cibernética que **verifica a identidade de um usuário** exigindo **pelo menos duas formas distintas de comprovação (fatores)**. O MFA adiciona camadas de proteção além da senha, que é o fator mais vulnerável e a causa mais comum de violações de dados.

O MFA faz parte essencial das estratégias de Gerenciamento de Identidade e Acesso (IAM). Mesmo que um hacker roube uma senha, ele não terá o segundo fator, que é muito mais difícil de ser comprometido.

---

## 🛠️ Tipos de Fatores de Autenticação

Para ser considerada MFA "verdadeira", a autenticação deve usar **pelo menos dois tipos diferentes** de fatores, pois isso exige métodos de ataque separados para cada evidência:

| Tipo de Fator | O que é (Exemplo) | Vulnerabilidade |
| :--- | :--- | :--- |
| **Conhecimento** | Algo que o usuário *sabe* (Senha, PIN, Resposta de segurança). | Mais vulnerável; obtido por phishing, malware ou força bruta. |
| **Posse** | Algo que o usuário *possui* (Smartphone, Token de Hardware, Chave de segurança). Gera tokens de uso único (OTP) ou exige notificação push. | Suscetível a roubo físico ou golpes como clonagem de SIM e ataques de fadiga. |
| **Inerente (Biometria)** | Algo *único ao usuário* (Impressão digital, Reconhecimento facial, Varredura de retina). | Mais difícil de decifrar, mas se comprometido, não pode ser alterado facilmente. |
| **Comportamental** | Algo que o usuário *faz* (Localização, Faixa de IP, Velocidade de digitação). | Pode ser copiado ou falsificado (ex: uso de VPN ou dispositivo confiável roubado). |

---

## 🔬 Conceitos Avançados e Diferenciação

* **MFA Adaptativa (Baseada em Risco):** Utiliza **Inteligência Artificial (IA) e Machine Learning (ML)** para avaliar o risco da tentativa de login em tempo real. Quanto mais arriscada a situação (ex: login de um local incomum), **mais fatores** o usuário deve fornecer. Isso melhora a experiência, exigindo múltiplos fatores apenas em situações confidenciais.
* **MFA Sem Senha:** Elimina o fator "Conhecimento" por ser o mais vulnerável, exigindo apenas fatores de Posse, Inerentes e Comportamentais (ex: Chaves de Acesso FIDO + Biometria).
* **MFA vs. 2FA:** A **Autenticação de Dois Fatores (2FA)** é um **subconjunto da MFA** que usa exatamente dois fatores. A MFA pode usar dois, três ou mais fatores.
* **MFA vs. SSO:** O **Logon Único (SSO)** foca na **conveniência** (usar um login para várias aplicações), enquanto o MFA foca na **segurança**. Eles são complementares, e sistemas SSO modernos geralmente exigem MFA.

---

## 🔗 Source

As informações contidas neste resumo foram compiladas a partir do artigo publicado por **Mattew Kosinski** e **Jim Holdsworth** no **IBM Think**.

* **O que é MFA (autenticação multifator)?:** https://www.ibm.com/br-pt/think/topics/multi-factor-authentication

---  

![alt text](https://img.icons8.com/?size=32&id=NvYRxC2UBsLO&format=png ) 
# 🔑 Multi-Factor Authentication (MFA) 🇺🇸

Multi-Factor Authentication (MFA) is a cybersecurity discipline that **verifies a user's identity** by requiring **at least two distinct forms of proof (factors)**. MFA adds extra layers of protection beyond passwords alone, which are the most vulnerable factor and the most common cause of data breaches.

MFA is an essential part of Identity and Access Management (IAM) strategies. Even if a hacker steals a password, they will not have the second factor, which is much harder to compromise.

---

## 🛠️ Types of Authentication Factors

To be considered "true" MFA, the authentication must use **at least two different types** of factors, as this requires separate attack methods for each piece of evidence:

| Factor Type | What It Is (Example) | Vulnerability |
| :--- | :--- | :--- |
| **Knowledge** | Something the user *knows* (Password, PIN, Security Question). | Most vulnerable; obtained via phishing, malware, or brute-force attacks. |
| **Possession** | Something the user *has* (Smartphone, Hardware Token, Security Key). Generates One-Time Passwords (OTP) or requires a push notification. | Susceptible to physical theft or scams like SIM swapping and fatigue attacks. |
| **Inherence (Biometrics)** | Something *unique to the user* (Fingerprint, Facial features, Retina scan). | Harder to crack, but once compromised, cannot be easily changed. |
| **Behavioral** | Something the user *does* (Location, IP Range, Typing speed). | Can be copied or spoofed (e.g., using a VPN or a stolen trusted device). |

---

## 🔬 Advanced Concepts and Differentiation

* **Adaptive MFA (Risk-Based):** Uses **Artificial Intelligence (AI) and Machine Learning (ML)** to assess the risk of the login attempt in real-time. The riskier the situation (e.g., logging in from an unusual location), the **more factors** the user must provide. This improves the user experience by requiring multiple factors only in sensitive situations.
* **Passwordless MFA:** Eliminates the "Knowledge" factor because it is the most vulnerable, requiring only Possession, Inherence, and Behavioral factors (e.g., FIDO Passkeys + Biometrics).
* **MFA vs. 2FA:** **Two-Factor Authentication (2FA)** is a **subset of MFA** that uses exactly two factors. MFA can require two, three, or more factors.
* **MFA vs. SSO:** **Single Sign-On (SSO)** focuses on **convenience** (using one login for multiple applications), while MFA focuses on **security**. They are complementary, and modern SSO systems often require MFA.

---

## 🔗 Source

The information contained in this summary was compiled from the article published by **Matthew Kosinski** and **Jim Holdsworth** on **IBM Think**.

* **What is MFA (multifactor authentication)?:** https://www.ibm.com/br-pt/think/topics/multi-factor-authentication
