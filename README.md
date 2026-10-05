# 🔐 01 - Sistema de Login e Autenticação

[![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![JavaFX](https://img.shields.io/badge/GUI-JavaFX%20%2F%20CSS-blue?style=for-the-badge&logo=java&logoColor=white)](https://openjfx.io/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow?style=for-the-badge)](#)

> **Projeto Final de Programação Orientada a Objetos (POO) – 2026.2**  
> **Professor:** Roger Moura Sarmento.
> **Instituição:** Instituto Federal de Educação, Ciência e Tecnologia do Ceará (IFCE).
> **Startup:** Prosa Code.

---

## 📝 Descrição

O **Sistema de Login** é o primeiro módulo obrigatório desenvolvido pela nossa Startup (**Prosa Code**) na disciplina de Programação Orientada a Objetos (POO). 

A aplicação tem como finalidade realizar a autenticação inicial do usuário através de uma interface gráfica construída em **JavaFX** (FXML e CSS) com estilização em *pixel art* botânico/café. Após a verificação correta das credenciais, o sistema redireciona o usuário para a **Tela de Seleção de Módulos**, a partir da qual será possível acessar futuramente a *Agenda de Contatos* (`02-agenda-contatos`) e o *Projeto Livre* (`03-projeto-livre`), ou retornar à tela de login.

---

## 🎯 Funcionalidades

-  🔑 **Tela de Login:** Interface gráfica JavaFX (FXML/CSS) para inserção de usuário e senha.
-  🛡️ **Validação de Credenciais:** Autenticação local verificando o usuário padrão (`root`) e senha (`toor`).
-  ⚠️ **Tratamento de Erros:** Exibição de alertas visuais e mensagens estilizadas caso o usuário ou senha estejam incorretos.
-  🎛️ **Tela de Seleção de Módulos:** Menu principal exibido após o login bem-sucedido.
-  🔄 **Navegação e Retorno:** Botão "Voltar" na Tela de Seleção que encerra o menu e reabre a tela de login.
-  🔗 **Atalhos de Integração:** Botões preparados para integração com os repositórios `02-agenda-contatos` e `03-projeto-livre`.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem de Programação:** Java
- **Interface Gráfica (GUI):** JavaFX
- **Paradigma:** Programação Orientada a Objetos (POO)
- **Gerenciamento de Versão:** Git & GitHub (Fluxo de Branches e Pull Requests)

---

## 📂 Organização do Projeto

A estrutura de diretórios deste repositório segue rigorosamente o padrão adotado pela nossa Startup, conforme orientado no Guia de Organização do GitHub (Versão 2.0)

```text
🔐 01-sistema-login/
├── 📖 README.md
├── ⚖️ LICENSE
├── 🚫 .gitignore
├── 💻 databases/
│
├── 💻 src/
│
├── 🎨 resources/
│   ├── 🔹 icons/
│   └── 🖼️ images/
│
├── 📚 docs/
│   ├── 📐 uml/
│   ├── 🎨 ui-ux/
│   │   ├── ✏️ wireframes/
│   │   ├── 🖼️ mockups/
│   │   └── 📱 prototypes/
│   ├── 📊 diagrams/
│   └── 📑 presentations/
│
└── 🧰 support/
    ├── 📄 documents/
    ├── 🎥 videos/
    ├── 📚 tutorials/
    └── 🔗 references/
