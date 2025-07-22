
# 📑 Apresentação — Projeto HTML: Estrutura Básica

## 👋 Introdução

Neste exercício, o objetivo foi criar um arquivo chamado `index.html` para colocar em prática os principais elementos do HTML.  
O desafio era dividido em 4 partes: Estrutura básica e textos, Listas, Links e imagens, e Tabelas.  
Vou explicar como cada parte foi feita e o que cada elemento representa.

## ✨ Parte 1: Estrutura Básica e Textos

Comecei criando um arquivo chamado `index.html`, usando a estrutura padrão de um documento HTML5:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Exercício HTML</title>
</head>
<body>
</body>
</html>
```

Essa estrutura define o tipo do documento, a linguagem, o título da aba do navegador e o corpo do conteúdo.

### Títulos
Adicionei três títulos para organizar a página:
- `<h1>` com o texto **"Minha Página Pessoal"** (título principal).
- `<h2>` com o texto **"Sobre mim e um pouco mais"** (subtítulo).
- `<h3>` com o texto **"Bem-vindo(a)!"** (título menor para abrir o conteúdo).

### Parágrafos
Depois, escrevi um parágrafo explicando a função da tag `<p>`:
> A tag `<p>` serve para escrever parágrafos e deixar o texto organizado e legível para quem lê.

Adicionei outro parágrafo com uma quebra de linha forçada usando `<br/>`:
> Este é um parágrafo com uma quebra de linha no meio<br/> para exemplificar a tag.

### Containers
Usei um `<div>` para criar um container com a frase:
> Este é um container de bloco — ótimo para separar conteúdos em seções.

E dentro de um parágrafo, usei um `<span>` para destacar a palavra “inline” com uma cor diferente:
> O elemento <span style="color: blue;">inline</span> aparece no meio do parágrafo só para destacar uma palavra.

Por fim, coloquei uma linha horizontal `<hr/>` para separar as seções.

## 📋 Parte 2: Listas

Adicionei um título `<h3>` chamado **"Coisas que eu gosto e preciso fazer"** para a seção.

### Lista Ordenada
Criei uma lista ordenada com 4 hobbies:
```html
<ol>
  <li>Ouvir música</li>
  <li>Andar de carro e moto</li>
  <li>Jogar videogame</li>
  <li>Aprender algo novo</li>
</ol>
```

### Lista Não Ordenada
Uma lista não ordenada com 3 tarefas para hoje:
```html
<ul>
  <li>Terminar a task de HTML</li>
  <li>Arrumar o cano do poço</li>
</ul>
```

### Lista de Definição
E uma lista de definição com 2 termos sobre desenvolvimento web:
```html
<dl>
  <dt>API</dt>
  <dd>Conjunto de regras que permitem que sistemas diferentes “conversem” entre si.</dd>
  <dt>Framework</dt>
  <dd>Um conjunto de ferramentas que ajuda a desenvolver aplicações mais rápido e de forma padronizada.</dd>
</dl>
```

## 🔗 Parte 3: Links e Imagens

Adicionei um título `<h3>` chamado **"Links e Imagens"** para a seção.

### Link Externo
Criei um link para um site de notícias (Quatro Rodas), com `target="_blank"` para abrir em nova aba:
```html
<a href="https://quatrorodas.abril.com.br/" target="_blank">Confira as últimas notícias da revista Quatro Rodas</a>
```

### Link Interno
Coloquei também um link interno com `href="#"` simulando voltar ao topo:
```html
<a href="#">Voltar ao topo</a>
```

### Imagem
Adicionei uma imagem com URL externa, definindo tamanho e texto alternativo:
```html
<img src="https://roryhenderson.com/wp-content/uploads/2023/10/1-scaled.jpg" alt="Mercedes Benz SL65 AMG Black Edition" width="300" height="200">
```

E coloquei essa imagem dentro de um link para que ela fosse clicável:
```html
<a href="https://www.quatrorodas.abril.com.br/" target="_blank">
  <img src="..." alt="..." width="300" height="200">
</a>
```

## 📊 Parte 4: Tabelas

Adicionei um título `<h3>` chamado **"Minhas Tabelas"**.

### Tabela de Informações Pessoais
```html
<table border="1">
  <caption>Informações Pessoais</caption>
  <tr>
    <th>Nome</th>
    <th>E-mail</th>
    <th>Cidade</th>
  </tr>
  <tr>
    <td>Lucas Dutra</td>
    <td>lucas@dbccompany.com.br</td>
    <td>Gravataí</td>
  </tr>
  <tr>
    <td>Cristina Jung</td>
    <td>cristina.jung@dbccompany.com.br</td>
    <td>Porto Alegre</td>
  </tr>
</table>
```

### Tabela com `colspan`
```html
<table border="1">
  <tr>
    <th>Produto</th>
    <th>Preço</th>
  </tr>
  <tr>
    <td>Monitor AOC 144hz</td>
    <td>R$ 800,00</td>
  </tr>
  <tr>
    <th colspan="2">Preços sujeitos a alteração</th>
  </tr>
</table>
```

### Tabela com `rowspan`
```html
<table border="1">
  <tr>
    <th>Categoria</th>
    <th>Item</th>
    <th>Preço</th>
  </tr>
  <tr>
    <td rowspan="2">Livros</td>
    <td>HTML & CSS</td>
    <td>R$ 80,00</td>
  </tr>
  <tr>
    <td>Cosmos - Carl Sagan</td>
    <td>R$ 90,00</td>
  </tr>
</table>
```

## 🌟 Conclusão

Esse exercício ajudou a entender a estrutura básica de uma página HTML, como organizar textos, listas, links, imagens e tabelas.  
Aprendi a usar os atributos especiais como `colspan` e `rowspan`, e como deixar uma página mais clara e organizada.
