![alt text](https://img.icons8.com/?size=32&id=0raNoKwBezGl&format=png ) 

# 🆔 Gerenciamento de Acesso Privilegiado (PAM)

O Gerenciamento de Acesso Privilegiado (PAM) é a disciplina de cibersegurança focada em **governar e proteger contas** que possuem **permissões de acesso maiores** do que as de um usuário padrão. O privilégio elevado pode pertencer a usuários humanos (administradores) ou não humanos (aplicativos, máquinas).

O PAM é um **subconjunto essencial do IAM**, focado em proteção mais rigorosa. Contas privilegiadas são alvos de alto valor para hackers e ameaças internas; o sequestro dessas contas é o vetor de ataque cibernético mais comum atualmente.

---

## 🔑 Três Pilares Essenciais do PAM

As estratégias de PAM combinam processos e ferramentas para controlar a atribuição, acesso e uso dos privilégios, concentrando-se em:

1.  **Gerenciamento de Contas Privilegiadas:** Supervisiona o ciclo de vida dessas contas (criação, provisionamento e descarte). O objetivo é **reduzir o número de contas privilegiadas** e centralizar credenciais em um **cofre de senhas (Vault)** para acesso seguro.
    * *Exemplos:* Contas de administrador de domínio, contas de serviço, contas raiz.
2.  **Gerenciamento de Privilégios:** Implementa modelos de acesso **Just-in-Time (JIT)**, substituindo privilégios permanentes. Os usuários recebem permissões elevadas apenas **pelo tempo limitado e para a tarefa específica** que precisam realizar (Elevação de Privilégio JIT).
3.  **Gerenciamento de Sessões Privilegiadas (PSM):** Monitora ativamente as atividades privilegiadas. As ferramentas PSM **rastreiam e gravam** (logs de eventos e vídeo) tudo o que o usuário faz com o privilégio, auxiliando na detecção de atividades suspeitas e na criação de trilhas de auditoria.

---

## 🛠️ Soluções e Casos de Uso

O PAM é crucial para mitigar riscos, pois violações que utilizam credenciais roubadas estão entre as mais caras. As soluções PAM simplificam o processo e apoiam as seguintes áreas:

* **Redução da Superfície de Ataque:** O uso de **cofres de credenciais** e o modelo de **acesso menos privilegiado** JIT tornam o roubo de contas mais difícil e limitam o movimento lateral dos atacantes.
* **Gerenciamento de Expansão de Identidade:** O PAM controla a explosão de novas **identidades não humanas** (IoT, IA, serviços em nuvem) que possuem altos privilégios e geralmente têm credenciais mal protegidas.
* **Conformidade Regulatória:** As ferramentas de PAM aplicam **privilégios de acesso granulares** e produzem trilhas de auditoria para que as organizações possam comprovar o controle de acesso a dados confidenciais.
* **Gerenciamento de Segredos (DevOps):** Armazena segredos (chaves SSH, APIs) em um cofre centralizado em vez de deixá-los codificados ou em texto simples. As credenciais podem ser **rotacionadas automaticamente** após o uso.
* **PAM e IA:** A tecnologia está incorporando IA para **autenticação baseada em risco** (alterando requisitos de login dinamicamente) e analisando logs de sessão para detectar atividades suspeitas.

---

## 🔗 Source

As informações contidas neste resumo foram compiladas a partir do artigo publicado por **Mattew Kosinski** no **IBM Think**.

* **O que é gerenciamento de acesso privilegiado (PAM)?:** https://www.ibm.com/br-pt/think/topics/privileged-access-management

---

![alt text](https://img.icons8.com/?size=32&id=NvYRxC2UBsLO&format=png ) 

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
