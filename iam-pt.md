# 🆔 Gerenciamento de Identidade e Acesso (IAM)

O Gerenciamento de Identidade e Acesso (IAM) é uma disciplina de cibersegurança crucial que lida com a **proteção de identidades digitais** e o controle das permissões de acesso dos usuários em um sistema de TI. O objetivo é garantir que apenas as **pessoas (ou máquinas) certas** acessem os recursos certos, no momento correto.

Com o aumento do trabalho remoto, da computação em nuvem e da Inteligência Artificial (IA), a superfície de ataque cresceu, e o IAM se tornou essencial: 30% dos ataques cibernéticos envolvem roubo de contas válidas.

---

## 🔑 Quatro Pilares Essenciais do IAM

As implementações eficazes de IAM se apoiam em quatro componentes interligados:

1.  **Administração (Ciclo de Vida):** Processo de **criar, manter, e descartar** identidades digitais (usuários humanos e não humanos) em um banco de dados central. Define quem e o que está no sistema e seus direitos básicos.
2.  **Autenticação:** Processo que **verifica a identidade do usuário** ao fazer login. Métodos avançados como a **Autenticação Multifactor (MFA)** são cruciais para aumentar a segurança, exigindo mais de uma credencial (ex: senha + código do celular).
3.  **Autorização:** Após a autenticação, este processo **concede o nível apropriado de acesso** ao recurso. É geralmente baseado no princípio do **privilégio mínimo**, onde o usuário só recebe as permissões estritamente necessárias para o trabalho (ex: Controle de Acesso Baseado em Função - RBAC).
4.  **Auditoria:** O monitoramento contínuo das atividades dos usuários para **garantir a conformidade regulatória** e identificar se invasores ou usuários autorizados estão abusando de seus privilégios.

---

## 🛠️ Soluções e Tecnologias-Chave

As ferramentas de IAM buscam simplificar e automatizar o controle de acesso por meio de diversas soluções:

* **Logon Único (SSO):** Permite que o usuário acesse múltiplos aplicativos com **apenas um conjunto de credenciais**.
* **Autenticação Adaptativa (Baseada em Risco):** Usa **IA e Machine Learning (ML)** para analisar o contexto do login (local, dispositivo) e exigir mais fatores de autenticação se o risco for maior.
* **Controle de Acesso (Diferentes Frameworks):** Além do RBAC, existem o **MAC** (obrigatório, baseado em níveis de confiança) e o **ABAC** (baseado em atributos de usuário, objeto e ação).
* **Gerenciamento de Acesso Privilegiado (PAM):** Ferramentas específicas para proteger as **contas de maior risco** (administradores), utilizando cofres e protocolos de acesso just-in-time.
* **Federação de Identidade:** Permite que sistemas diferentes compartilhem informações de identidade (ex: usar login do Google em um novo aplicativo).
* **IDaaS (Identity as a Service):** Soluções de IAM baseadas em nuvem (SaaS), ideais para redes complexas e distribuídas.

---

## 🔬 IAM e o Cenário Futuro

* **Malha de Identidade (Identity Fabric):** Organizações estão investindo em arquiteturas que **unificam todos os sistemas de identidade** em uma rede integrada, usando ferramentas holísticas de IAM para simplificar a gestão e fortalecer a segurança.
* **IAM e IA:** A IA (especialmente a IA generativa) aumenta o número de **identidades não humanas** na rede (Agentes de IA), tornando o PAM essencial para proteger essas novas contas. Por outro lado, a IA é usada positivamente em ferramentas IAM para análise de risco, controle de conformidade e verificação de usuários.
  
---

## 🔗 Source

As informações contidas neste resumo foram compiladas a partir do artigo publicado por **Mattew Kosinski** e **Amber Forrest** no **IBM Think**.

* **O que é IAM (Identity and Acess Management)?:** https://www.ibm.com/br-pt/think/topics/identity-access-management
