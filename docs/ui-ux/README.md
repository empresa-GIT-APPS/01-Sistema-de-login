# 🎨 Design de Interface e Identidade Visual — `/docs/ui-ux`

> **Startup:** Prosa Code  
> **Projeto:** Sistema de Gestão para Sebos e Livrarias  
> **Disciplina:** Programação Orientada a Objetos (POO) — IFCE  
> **Docente:** Prof. Roger Moura Sarmento  

---

## 📝 Descrição e Finalidade

Este diretório armazena todo o ecossistema de **Design de Interface (UI)** e **Experiência do Usuário (UX)** da **Prosa Code**. Aqui estão consolidados a identidade visual, paleta de cores oficial, esboços manuais (*wireframes*), guias gráficos (*mockups*), protótipos interativos e prompts de mídia em *pixel art* botânico/café.

Seu objetivo é garantir a consistência estética e servir de referência direta para a equipe de desenvolvimento front-end durante a implementação das telas em Java Swing.

---

## 🗂️ Estrutura e Conteúdo do Diretório

```text
docs/ui-ux/
├── ✏️ wireframes/          # Esboços e rascunhos manuais
├── 🖼️ mockups/             # Artes em alta fidelidade, logos e paleta
│   ├── LoginDesktop.jpg
│   ├── LoginMobile.jpg
│   ├── SeleçãoAcesso.jpg
│   ├── prosa-code-login.mp4
│   └── README.md
└── 📱 prototypes/          # Protótipos interativos
```

### 📋 Detalhamento dos Arquivos e Subpastas

| Subpasta / Arquivo | Descrição do Recurso | Finalidade / Aplicação |
| :--- | :--- | :--- |
| **`wireframes/EsboçoDaLogo.jpg`** | Rascunho inicial feito à mão do logotipo. | Concepção da identidade da marca. |
| **`wireframes/esboçoBanner.jpg`** | Esboço manual da composição do banner. | Planejamento de layout promocional. |
| **`mockups/BannerOficial.png`** | Banner oficial finalizado da Prosa Code. | Apresentações e cabeçalho de repositório. |
| **`mockups/logo.jpeg`** | Logotipo em alta resolução. | Marca oficial em telas e documentos. |
| **`mockups/paletas.jpeg`** | Guia visual da paleta de cores. | Padronização de cores no Java FX |

---

## 🎨 Especificações de Identidade Visual

### ☕ Paleta de Cores Oficial

A estética do projeto combina o aconchego de um café com a tranquilidade de uma biblioteca botânica. Todas as interfaces Java Swing devem utilizar os códigos hexadecimais abaixo:

| Amostra | Nome da Cor | Código Hex | Aplicação no Sistema |
| :---: | :--- | :--- | :--- |
| 🟪 | **Roxo Profundo** | `#27081D` | Bordas principais, textos de alto contraste e fundos escuros. |
| 🍷 | **Vinho Madeira** | `#47232C` | Estantes de livros, botões primários e detalhes de madeira. |
| 🌿 | **Verde Muted** | `#66997B` | Ramos, folhas de fundo e elementos botânicos secundários. |
| 🍃 | **Verde Suave** | `#A4CA8B` | Caixas de entrada (inputs), ícones e destaques de foco. |
| 🍵 | **Verde Pastel** | `#D2E7AA` | Fundo geral de telas (*background*) e botões claros. |

---

## 🚀 Recomendações para a Equipe de Desenvolvedores

1. **Fidelidade Visual (Front-end):** Os desenvolvedores responsáveis pela interface (**Agatha** e **Eduardo**) devem utilizar o arquivo `mockups/paletas.jpeg` e a prototipagem em `prototypes/preview_login.html` como guia obrigatório para configurar cores e fontes.
2. **Padrão de Pixel Art (16-bits):** Caso precise adicionar novos componentes visuais, garanta que mantenham contornos nítidos e a estética retro/botânica do projeto.
3. **Inclusão de Novos Artefatos:** Ao criar novas telas ou esboços manuais, salve os arquivos na subpasta correspondente (`wireframes/`, `mockups/` ou `prototypes/`) e atualize as tabelas deste `README.md`.
