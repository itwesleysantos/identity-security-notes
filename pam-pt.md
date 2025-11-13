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
