# 📚 Documentação Técnica do Projeto — `/docs` (01-Sistema de Login)

> **Startup:** Prosa Code  
> **Projeto:** 01-sistema-login (Módulo de Autenticação e Controle de Acesso)  
> **Disciplina:** Programação Orientada a Objetos (POO) — IFCE  
> **Docente:** Prof. Roger Moura Sarmento  

---

## 📝 Descrição e Finalidade

Este diretório concentra toda a documentação técnica, especificações de requisitos, modelagem de dados UML, prototipagem de UI/UX e materiais de apresentação do subprojeto **01-sistema-login**.

O **Módulo de Login** é a porta de entrada da aplicação **Prosa Code**, sendo responsável por autenticar usuários, validar credenciais no banco de dados MySQL, gerenciar sessões e redirecionar a navegação para os subsistemas autorizados (Agenda de Contatos / Aplicação Principal). A documentação aqui presente orienta a equipe na transição dos conceitos visuais em *pixel art* botânico/café para o código Java Swing.

---

## 🗂️ Estrutura e Conteúdo do Diretório

```text
docs/
├── 📐 uml/                  # Diagramas da arquitetura POO de Autenticação
├── 🎨 ui-ux/                # Design de interface e identidade visual
│   ├── ✏️ wireframes/      # Rascunhos manuais das telas
│   │   ├── LoginDesktop.jpg
│   │   ├── LoginMobile.jpg
│   │   ├── SeleçãoAcesso.jpg
│   │   ├── prosa-code-login.mp4
│   │   └── README.md
│   ├── 🖼️ mockups/         # Layouts em alta fidelidade e guias
│   └── 📱 prototypes/      # Protótipo web interativo e prompts
├── 📊 diagrams/             # Fluxogramas de decisão e validação de acesso
└── 📑 presentations/        # Slides e roteiros de apresentação do módulo
