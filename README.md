# 🌐 Portfólio / Currículo Web

Projeto desenvolvido como atividade prática com o objetivo de criar uma página de **Portfólio / Currículo Web** utilizando **HTML5 puro e semântico**. A proposta é demonstrar domínio na organização de informações pessoais, tabelas, formulários e estrutura semântica.

---

## 🎯 Objetivo

Criar uma página HTML limpa, semântica e funcional que reproduza a organização de informações essenciais de um portfólio web, focando nas boas práticas de desenvolvimento front-end.

---

## 📋 Requisitos do Projeto

### 📄 Estrutura & Seções

1. **Cabeçalho & Navegação (`<header>`, `<nav>`)**:
   - Título principal com nome/cargo.
   - Menu de navegação com links internos (âncoras `#id`) para as seções: *Sobre*, *Projetos* e *Contato*.

2. **Seção "Sobre Mim" (`<section id="sobre">`)**:
   - Foto de perfil formatada (dimensões de **150px x 150px**).
   - Texto de apresentação pessoal/profissional.
   - Lista destacando as **Minhas Habilidades**.

3. **Seção "Meus Projetos" (`<section id="projetos">`)**:
   - Tabela organizada contendo 4 colunas: **Projeto**, **Tecnologias**, **Status** e **Link** (com hiperlink funcional).
   - Uso correto das tags de tabela: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` e `<td>`.

4. **Seção "Entre em Contato" (`<section id="contato">`)**:
   - Formulário envelopado na tag `<fieldset>` com a legenda `<legend>Dados do Contato</legend>`.
   - Campos de entrada: Nome, E-mail, Menu suspenso (`<select>`) para Assunto e área de texto (`<textarea>`) para Mensagem.
   - Todos os campos devidamente associados às suas respectivas tags `<label>`.
   - Botão para envio do formulário.

5. **Rodapé (`<footer>`)**:
   - Direitos autorais utilizando caractere especial (`&copy;`).
   - Informações de e-mail e telefone de contato.

---

## 🛠️ Especificações Técnicas & Boas Práticas

- **HTML5 Semântico**: Utilização de tags estruturais como `<header>`, `<nav>`, `<main>`, `<section>`, `<table>`, `<fieldset>` e `<footer>`.
- **Navegação Interna**: Âncoras (`href="#id"`) apontando corretamente para cada seção.
- **Acessibilidade & Usabilidade**: Associação correta entre `<label>` e campos do formulário através do atributo `for`.
- **Imagens**: Foto de perfil dimensionada exatamente em `150px` x `150px`.

---

## 🚀 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
