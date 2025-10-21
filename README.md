# Repositório direcionado a receber atividades de Autoria Web

# 2º Bimestre — HTML e CSS Intermediário e Montagem

Este bimestre tem como foco **estruturar páginas completas**, **organizar o conteúdo de forma semântica** e **iniciar a estilização com CSS externo**.  
Cada atividade deve ser entregue no formato indicado (HTML e/ou CSS), respeitando o modelo de organização e envio descrito abaixo.

---

## 🧭 Organização e Entrega das Atividades

#### 1. Cada aluno deve **criar uma branch específica para o bimestre**, com o nome: _bimestre-2_

#### 2. Dentro dessa branch, cada atividade deverá ser salva dentro de uma **pasta nomeada conforme o padrão**:

- /Atividade 1
- /Atividade 2
- /Atividade 3
- /...

> Exemplo: a primeira atividade deve ficar em `/Atividade 1/estrutura-basica.html`

#### 3. Cada pasta deve conter:

- Os arquivos `.html` e `.css` (quando aplicável);
- Um arquivo `README.md` descrevendo o que foi feito (breve resumo em 3–5 linhas).

#### 4. Após concluir a atividade:

- Faça o **commit** dos arquivos;
- Faça o **push** para a branch `bimestre-2` no GitHub;
- Envie o link da pasta correspondente no **Google Sala de Aula**.

---

## Atividades

### 🟢 AS1 – Estruturando Cabeçalho e Rodapé

**Tema:** Estrutura de Página  
**Explicação:**  
Toda página precisa de um **cabeçalho (header)** com título e navegação, e um **rodapé (footer)** com créditos ou contatos. Isso ajuda a dar estrutura e lógica visual ao site.

**Objetivo:** Criar uma estrutura de site com cabeçalho e rodapé.  
**Instruções:**

- Crie `estrutura-basica.html`;
- Use `<header>`, `<main>` e `<footer>`.
- Coloque o nome do site no cabeçalho e um texto no corpo.

**Entrega:** `/Atividade 1/estrutura-basica.html`

---

### 🟢 AS2 – Primeira Tabela

**Tema:** Organização de Dados  
**Explicação:**  
As **tabelas** organizam informações em linhas e colunas — como planilhas. Elas são ideais para dados organizados, como preços ou notas.

**Objetivo:** Entender e aplicar a estrutura de tabelas no HTML.  
**Instruções:**

- Crie `minha-tabela.html`;
- Crie uma tabela com 3 colunas e 5 linhas;
- Use `<th>` e `<td>` corretamente.

**Entrega:** `/Atividade 2/minha-tabela.html`

---

### 🟡 AM1 – Tabela de Horários

**Tema:** Tabelas Avançadas  
**Explicação:**  
Tabelas mais elaboradas usam `colspan` e `rowspan` para unir células, o que permite mostrar horários ou blocos de tempo de forma mais clara.

**Objetivo:** Criar uma tabela mais complexa.  
**Instruções:**

- Crie `tabela-horarios.html`;
- Use `<thead>`, `<tbody>`, `<tfoot>`;
- Aplique `colspan` e `rowspan`.

**Entrega:** `/Atividade 3/tabela-horarios.html`

---

### 🟡 AM2 – Formulário de Contato

**Tema:** Coleta de Informações  
**Explicação:**  
Um **formulário** é o meio pelo qual os usuários enviam dados — como mensagens, cadastros ou dúvidas.

**Objetivo:** Criar um formulário simples e funcional.  
**Instruções:**

- Crie `form-contato.html`;
- Inclua nome, e-mail e mensagem;
- Adicione botão de envio.

**Entrega:** `/Atividade 4/form-contato.html`

---

### 🔴 AC1 – Página Institucional

**Tema:** Estrutura Completa de Site  
**Explicação:**  
Uma **página institucional** reúne o que você aprendeu: estrutura, navegação e estilo visual. É uma página modelo de empresa, escola ou projeto.

**Objetivo:** Criar uma página de apresentação completa.  
**Instruções:**

- Crie `pagina-institucional.html` e `style.css`;
- Use `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`;
- Aplique estilos no CSS (cores, fontes, margens).

**Entrega:** `/Atividade 5/` com os arquivos `.html` e `.css`

---

### 🟢 AS3 – Navegação Interna

**Tema:** Âncoras e Navegação Interna  
**Explicação:**  
Links internos (`<a href="#id">`) permitem rolar até partes específicas da mesma página. É comum em páginas longas com seções de conteúdo.

**Objetivo:** Criar uma página com links internos.  
**Instruções:**

- Crie `navegacao.html`;
- Crie 3 seções: Início, Sobre e Contato;
- Use IDs e links internos.

**Entrega:** `/Atividade 6/navegacao.html`

---

### 🟢 AS4 – Página com Seções Semânticas

**Tema:** HTML Semântico  
**Explicação:**  
O **HTML semântico** usa tags com significado, como `<header>` ou `<article>`, facilitando o entendimento do conteúdo por navegadores e leitores de tela.

**Objetivo:** Aplicar as principais tags semânticas.  
**Instruções:**

- Crie `semantica.html`;
- Use `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`.

**Entrega:** `/Atividade 7/semantica.html`

---

### 🟡 AM3 – Formulário de Cadastro Completo

**Tema:** Tipos de Campos em Formulários  
**Explicação:**  
Os formulários podem ter campos como botões de opção, seletores e caixas de seleção. Cada tipo de entrada serve para um tipo de dado.

**Objetivo:** Criar um formulário de cadastro completo.  
**Instruções:**

- Crie `cadastro.html`;
- Adicione campos: nome, e-mail, senha, cidade e estado;
- Use `<select>`, `<option>`, `<input type="radio">`, `<input type="checkbox">`.

**Entrega:** `/Atividade 8/cadastro.html`

---

### 🟡 AM4 – Estilizando Formulários

**Tema:** CSS em Formulários  
**Explicação:**  
O CSS melhora a aparência dos formulários, destacando campos e botões de forma elegante e legível.

**Objetivo:** Aplicar CSS em formulários e botões.  
**Instruções:**

- Crie `form-estilizado.html` e `form.css`;
- Use seletores de foco (`:hover`, `:focus`);
- Estilize inputs, botões e espaçamentos.

**Entrega:** `/Atividade 9/` com os arquivos `.html` e `.css`

---

### 🔴 AC2 – Mini Landing Page Semântica

**Tema:** Landing Pages e Semântica  
**Explicação:**  
Uma **landing page** é uma página de apresentação visual e organizada. A **semântica** torna o código mais claro e bem estruturado para leitura e SEO.

**Objetivo:** Montar uma landing page com estrutura semântica e CSS.  
**Instruções:**

- Crie `index.html` e `style.css`;
- Estruture a página com cabeçalho, seções e rodapé;
- Adicione imagens, listas e formulário;
- Aplique estilos de cores e fontes.

**Entrega:** `/Atividade 10/` com os arquivos `.html` e `.css`

---

**📤 Entrega no Google Sala de Aula**

1. Faça o **commit** e o **push** para a branch `bimestre-2`.
2. Copie o link da pasta correspondente à atividade no GitHub.
3. Envie o link no campo de **entrega da atividade** no Google Sala de Aula.
4. O nome do link deve conter seu nome e número da atividade.
   > Exemplo: `joaosilva-atividade-4`.

---

## 1º Bimestre

### Atividade 1 - Simples (montagem de estrutura HTML)

> Entrega para: 04/07
<<<<<<< HEAD
> Esta atividade tem por objetivo organizar o uso do Github, enviando uma tarefa com a organização do repositório inicial.
> Aqui será necessário usar:

=======

Esta atividade tem por objetivo organizar o uso do Github, enviando uma tarefa com a organização do repositório inicial.
Aqui será necessário usar:
>>>>>>> 0c5f537d357653c2726054444a6404c2823f79b8
- estrutura básica do HTML
- listas
- titulos
- Github (fork, branch, add, commit, push, pull request)

<<<<<<< HEAD
=======
---

### Atividade 2 - Simples
> Entrega para: 15/09

**Título:** Minha Primeira Página Estruturada  
**Objetivo:** Praticar o uso de títulos, parágrafos, listas e links em uma única página. 
**Descrição:**  
- Crie um arquivo chamado `primeira-estrutura.html`.  
- Estruture o documento corretamente com `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.  
- No corpo da página insira:  
  - Um título `<h1>` com o nome de um hobby que você gosta.  
  - Um parágrafo `<p>` explicando por que você gosta desse hobby.  
  - Uma lista não ordenada `<ul>` com **3 itens** relacionados ao hobby.  
  - Um link `<a>` que leve para um site relacionado ao tema.  

---

### Atividade 3 - Media
> Entrega para: 19/09

**Título:** Lista de Compras  
**Objetivo:** Trabalhar listas ordenadas e não ordenadas.  
**Descrição:**  
- Crie um arquivo chamado `lista-compras.html`.  
- Estruture o documento corretamente.  
- No corpo da página insira:  
  - Um título `<h2>` chamado “Lista de Compras”.  
  - Uma lista **não ordenada** (`<ul>`) com pelo menos 8 itens de supermercado.  
  - Uma lista **ordenada** (`<ol>`) mostrando os 5 primeiros passos para preparar uma refeição simples.  

---

### Atividade 4 - Média (montagem de estrutura HTML)
> Entrega para: 23/09

**Título:** Página de Links Favoritos  
**Objetivo:** Trabalhar com links e imagens.  
**Descrição:**  
- Crie um arquivo chamado `meus-links.html`.  
- Estruture o documento corretamente.  
- No corpo da página insira:  
  - Um título `<h2>` “Meus Links Favoritos”.  
  - Uma lista de 5 links (`<a>`) para sites que você costuma acessar.  
  - Insira uma imagem (`<img>`) representando um desses sites, com `alt` preenchido corretamente.  

---

### Atividade 5 - Complexa (montagem de estrutura HTML)
> Entrega para: 30/09

**Título:** Mini Currículo Online  
**Objetivo:** Criar uma página completa usando diversos elementos básicos.  
**Descrição:**  
- Crie um arquivo chamado `mini-curriculo.html`.  
- Estruture o documento corretamente.  
- O corpo da página deve conter:  
  - Um título principal `<h1>` com seu nome.  
  - Uma imagem (`<img>`) sua ou de um avatar.  
  - Uma seção `<div>` chamada “Sobre mim” com um parágrafo descrevendo você.  
  - Uma seção “Formação” usando uma **lista ordenada** para mostrar seu histórico escolar.  
  - Uma seção “Habilidades” usando uma **lista não ordenada** com ao menos 5 habilidades.  
  - Uma lista de **links externos** para redes sociais ou sites relacionados.  

---

## 2º Bimestre

>>>>>>> 0c5f537d357653c2726054444a6404c2823f79b8
## 3º Bimestre

## 4º Bimestre
