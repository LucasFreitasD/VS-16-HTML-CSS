# 📑 Apresentação — Projeto HTML & CSS: Task 02

## 👋 Introdução

Neste exercício, o objetivo foi criar um site com **três páginas**: `index.html`, `menu1.html` e `menu2.html`, utilizando **tags semânticas do HTML5** e estilização com **CSS externo**. O layout deveria seguir a estrutura proposta pela professora com as cores azul, preto e branco (em homenagem ao Grêmio), contendo menus de navegação, imagens, listas e um formulário estilizado.

---

## ✨ Estrutura do Projeto

Os arquivos foram organizados na pasta `Task02/` da seguinte forma:

```
Task02/
├── index.html
├── menu1.html
├── menu2.html
└── styles.css
```

O arquivo CSS (`styles.css`) é compartilhado entre todas as páginas para garantir a uniformidade visual.

---

## 🏗️ Estrutura Semântica

Cada página possui a seguinte estrutura semântica básica:

```html
<header>...</header>
<nav>...</nav>
<main>...</main>
<footer>...</footer>
```

### Header

Contém o título principal com fundo azul e texto branco.

### Nav

Menu com links para as três páginas, usando uma lista não ordenada com fundo preto e links em branco.

### Main

Conteúdo principal da página, com fundo branco e textos em preto. O conteúdo varia conforme a página:

- **Home:** mensagem de boas-vindas, imagem, formulário e lista.
- **Menu 1:** imagem ilustrativa e lista de opções.
- **Menu 2:** imagem ilustrativa e lista ordenada com etapas.

### Footer

Rodapé com texto simples, fundo azul e texto branco.

---

## 🎨 Cores e Estilo

As cores usadas foram inspiradas no Grêmio:

- Azul (`#007BFF`) no header e footer.
- Preto (`#000000`) no menu.
- Branco (`#ffffff`) no main.

### Trecho do CSS principal:

```css
header {
  background-color: #007BFF;
  color: white;
  text-align: center;
  padding: 20px;
}

nav {
  background-color: #000000;
}

main {
  background-color: #ffffff;
  padding: 20px;
  min-height: 400px;
  color: #000;
}

footer {
  background-color: #007BFF;
  color: white;
  text-align: center;
  padding: 10px;
}
```

---

## 📄 Páginas

### 🏠 Home (`index.html`)

- Boas-vindas
- Imagem
- Formulário com campos de nome e email
- Lista não ordenada com 3 itens

### 📋 Menu 1 (`menu1.html`)

- Imagem ilustrativa
- Lista de 3 opções

### 📝 Menu 2 (`menu2.html`)

- Imagem ilustrativa
- Lista ordenada com 3 etapas

---

## 🌟 Conclusão

Este projeto ajudou a praticar o uso de **tags semânticas do HTML5**, a criação de um layout consistente com múltiplas páginas, e a aplicação de um tema de cores personalizado com **CSS externo**. O resultado é um site bem estruturado, com menus funcionais e conteúdo organizado, seguindo o layout solicitado pela professora com as cores do Grêmio.

