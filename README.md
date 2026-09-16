# Construtora Maciel

![Construtora Maciel](Img/Logotipo.png)

Site institucional desenvolvido para a **Construtora Maciel**, apresentando informações sobre a empresa, seus empreendimentos, imóveis, contatos e oportunidades de trabalho.

---

## 📑 Sumário

- [Sobre o Projeto]
- [Estrutura do Projeto]
- [Páginas]
- [Recursos HTML Utilizados]
- [Multimídia]
- [Formulários]
- [Objetivo]
- [Créditos]

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como atividade acadêmica da **UNIPÊ**, na disciplina de **Desenvolvimento Front-End Para Web**, com o objetivo de aplicar os conhecimentos adquiridos sobre **HTML5** na criação de um site institucional.

O projeto foi desenvolvido utilizando **HTML**, sem a criação de arquivos próprios de CSS ou JavaScript.

O site apresenta informações relacionadas à Construtora Maciel, seus empreendimentos, imóveis, informações institucionais, formas de contato e oportunidades de trabalho.

Também foram utilizados recursos incorporados por meio de `<iframe>`, como **Google Maps** e **YouTube**.

---

## 📁 Estrutura do Projeto

```text
/
├── Html/
│   ├── Home.html
│   ├── Empreendimentos.html
│   ├── RL.html
│   ├── PS.html
│   ├── Chacaras.html
│   ├── Sobrenos.html
│   ├── Contatos.html
│   ├── trabalhe.html
│   ├── politicas.html
│   └── erro.html
│
├── Img/
│   ├── imagens
│   └── pastas dos empreendimentos
│
├── MP4/
│   ├── RL1.mp4
│   ├── Sobrenos.mp4
│   ├── V22Vista.mp4
│   └── ps.mp4
│
├── Audio/
│   └── arquivos de áudio
│
└── README.md
```

---

## 🌐 Páginas

O projeto atualmente possui **10 páginas HTML**, organizadas dentro da pasta `Html/`.

### 🏠 Home

**Arquivo:** `Home.html`

Página inicial do site. Apresenta a Construtora Maciel e fornece acesso às principais áreas do projeto.

### 🏢 Empreendimentos

**Arquivo:** `Empreendimentos.html`

Apresenta os principais empreendimentos disponíveis e direciona o usuário para suas respectivas páginas.

### 🌴 Recanto do Lazer

**Arquivo:** `RL.html`

Página destinada às informações do empreendimento **Recanto do Lazer**, contendo informações, características e imagens.

### 🏘️ Portal do Sol

**Arquivo:** `PS.html`

Página com informações sobre o empreendimento **Portal do Sol**, incluindo conteúdo multimídia e informações sobre o projeto.

### 🌳 Chácaras

**Arquivo:** `Chacaras.html`

Página destinada à apresentação das opções de chácaras, suas características e informações disponíveis.

### 👷 Sobre Nós

**Arquivo:** `Sobrenos.html`

Apresenta informações institucionais sobre a Construtora Maciel, sua história e atuação.

### 📞 Contatos

**Arquivo:** `Contatos.html`

Página destinada ao contato com a empresa, contendo informações de comunicação e formulário.

### 💼 Trabalhe Conosco

**Arquivo:** `trabalhe.html`

Página destinada ao cadastro de pessoas interessadas em oportunidades de trabalho na empresa.

### 📜 Políticas

**Arquivo:** `politicas.html`

Página contendo as políticas e informações relacionadas à utilização do site.

### ⚠️ Erro

**Arquivo:** `erro.html`

Página utilizada para situações de erro ou redirecionamento, principalmente relacionadas aos formulários.

---

## 🧱 Recursos HTML Utilizados

O projeto utiliza diversos recursos do **HTML5**, incluindo elementos semânticos, formulários, multimídia e elementos interativos.

### Estrutura semântica

Foram utilizados elementos semânticos para organizar o conteúdo das páginas:

- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<article>`
- `<aside>`
- `<footer>`

Esses elementos ajudam na organização e na estruturação semântica do conteúdo.

### Organização de conteúdo

Também foram utilizados elementos como:

- `<figure>`
- `<figcaption>`
- `<fieldset>`
- `<legend>`
- `<details>`
- `<summary>`

---

## 🎬 Multimídia

O projeto possui recursos de áudio, vídeo e imagens.

### Vídeos

Os vídeos locais estão armazenados na pasta `MP4/` e são utilizados através do elemento `<video>`.

Exemplo:

```html
<video controls>
    <source src="../MP4/video.mp4" type="video/mp4">
</video>
```

### Áudios

Os arquivos de áudio estão armazenados na pasta `Audio/` e são utilizados através do elemento `<audio>`.

Exemplo:

```html
<audio controls>
    <source src="../Audio/apresentacao.mp3" type="audio/mpeg">
</audio>
```

### Imagens

As imagens utilizadas no projeto estão organizadas dentro da pasta `Img/`.

Também foram utilizados:

```html
<figure>
    <img src="../Img/imagem.jpg" alt="Descrição da imagem">
    <figcaption>Descrição da imagem</figcaption>
</figure>
```

Além dos arquivos locais, o projeto possui conteúdos incorporados através de `<iframe>`, como mapas do **Google Maps** e vídeos do **YouTube**.

---

## 📝 Formulários

Os formulários foram desenvolvidos utilizando diferentes recursos do HTML5.

Entre os elementos e atributos utilizados estão:

- Campos de texto
- `type="email"`
- `type="tel"`
- `type="date"`
- `type="file"`
- `type="range"`
- `required`
- `placeholder`
- `<datalist>`
- `<select>`
- `<option>`
- `<textarea>`
- `<fieldset>`
- `<legend>`

### Exemplo

```html
<input
    type="email"
    name="email"
    placeholder="Digite seu e-mail"
    required
>
```

Os principais formulários estão presentes nas páginas de **Contatos** e **Trabalhe Conosco**.

---

## 🔖 Recursos de HTML Avançado

O projeto também utiliza diferentes elementos solicitados na atividade de HTML Avançado.

### Elementos de texto

- `<abbr>`
- `<mark>`
- `<blockquote>`
- `<cite>`
- `<del>`
- `<ins>`

### Elementos interativos

- `<details>`
- `<summary>`

### Elementos de progresso

- `<progress>`
- `<meter>`

Esses recursos foram utilizados para melhorar a organização e demonstrar diferentes funcionalidades disponíveis no HTML5.

---

## 🎯 Objetivo

O principal objetivo do projeto é colocar em prática os conhecimentos adquiridos durante a disciplina de **Desenvolvimento Front-End Para Web**, utilizando HTML5 para construir um site institucional.

Entre os objetivos estão:

- Desenvolver páginas utilizando HTML5;
- Utilizar elementos semânticos;
- Criar uma estrutura organizada de páginas;
- Desenvolver navegação entre as páginas;
- Trabalhar com imagens;
- Utilizar áudio e vídeo;
- Criar formulários utilizando recursos avançados do HTML5;
- Utilizar elementos interativos;
- Organizar arquivos em diferentes pastas;
- Aplicar diferentes recursos do HTML5 em um projeto prático.

---

## 🎓 Créditos

**Projeto acadêmico desenvolvido por:**

**Matheus Henrique Alves Da Silva**

**Instituição:** UNIPÊ  
**Disciplina:** Desenvolvimento Front-End Para Web  
**Tecnologia principal:** HTML5

---

## 📌 Observação

O projeto foi desenvolvido com foco no aprendizado e na aplicação prática dos recursos de **HTML5**, mantendo a estrutura compatível com os conhecimentos trabalhados durante a disciplina.

BASE DO README GERADO POR IA.