

<h1 align="center">🌐 Aulas de HTML</h1>
<h2 align="center">Base para o Desenvolvimento Web</h2>

O repositório contém tudo o que você precisa para começar a aprender HTML, a linguagem de marcação que estrutura o conteúdo da web. 🌟

## 📚 **Índice**

- [📚 **Índice**](#-índice)
- [📝 **Introdução ao HTML**](#-introdução-ao-html)
- [🏷️ **Tags Básicas**](#️-tags-básicas)
- [🏗️ **Estrutura de um Documento HTML**](#️-estrutura-de-um-documento-html)
- [✍️ **Formatação de Texto**](#️-formatação-de-texto)
- [📋 **Listas**](#-listas)
- [🔗 **Links e Imagens**](#-links-e-imagens)
- [🏛️ **HTML Semântico**](#️-html-semântico)
- [🗃️ **Tabelas**](#️-tabelas)
- [📝 **Formulários**](#-formulários)
- [🚀 **Próximos Passos**](#-próximos-passos)
- [📚 **Recursos Adicionais**](#-recursos-adicionais)

## 📝 **Introdução ao HTML**

O HTML (HyperText Markup Language) é a linguagem padrão para criar páginas web. Ele utiliza "tags" para estruturar o conteúdo que será exibido em um navegador.

## 🏷️ **Tags Básicas**

- `<html>`: Define o início e o fim de um documento HTML.
- `<head>`: Contém metadados como o título da página.
- `<title>`: Define o título da página que aparece na aba do navegador.
- `<body>`: Contém o conteúdo visível da página.

## 🏗️ **Estrutura de um Documento HTML**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha Primeira Página</title>
</head>
<body>
  <h1>Olá, Mundo!</h1>
  <p>Bem-vindo ao meu site.</p>
</body>
</html>
```

## ✍️ **Formatação de Texto**

- **Negrito**: `<strong>` ou `<b>`
- _Itálico_: `<em>` ou `<i>`
- ~Riscado~: `<s>`

## 📋 **Listas**

- **Ordenada**: `<ol>`
- **Não Ordenada**: `<ul>`
- **Item de Lista**: `<li>`

## 🔗 **Links e Imagens**

- **Link**: Para criar links clicáveis, usamos a tag `<a>` (âncora). Aqui está um exemplo:

  ```html
  <a href="https://exemplo.com">Clique aqui</a>
  ```

  - O atributo `href` indica o destino do link.
  - Você pode usar links tanto para outras páginas da web quanto para seções da mesma página.

- **Imagens**: Para adicionar uma imagem, usamos a tag `<img>`. Exemplo:

  ```html
  <img src="caminho/para/imagem.jpg" alt="Descrição da imagem">
  ```

  - O atributo `src` especifica o caminho da imagem.
  - O atributo `alt` fornece uma descrição alternativa da imagem (importante para acessibilidade).

## 🏛️ **HTML Semântico**

O HTML semântico melhora a acessibilidade e SEO das páginas, pois utiliza tags que descrevem claramente o significado do conteúdo. Exemplos de tags semânticas incluem:

- **`<header>`**: Usada para definir o cabeçalho de uma página ou seção.
- **`<nav>`**: Contém links de navegação, como menus.
- **`<section>`**: Define seções temáticas do documento.
- **`<article>`**: Representa um conteúdo independente e autoexplicativo (como posts de blog ou artigos de notícias).
- **`<footer>`**: Contém o rodapé da página.

Exemplo de uso de HTML semântico:

```html
<header>
  <h1>Bem-vindo ao Meu Blog</h1>
  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section>
  <article>
    <h2>Primeiro Post</h2>
    <p>Este é o conteúdo do meu primeiro post.</p>
  </article>
</section>

<footer>
  <p>&copy; 2024 Meu Blog</p>
</footer>
```

## 🗃️ **Tabelas**

```html
<table>
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Maria</td>
    <td>30</td>
  </tr>
</table>
```

## 📝 **Formulários**

```html
<form action="/submit">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome">
  <input type="submit" value="Enviar">
</form>
```

## 🚀 **Próximos Passos**

- Experimente criar sua própria página HTML.
- Explore novas tags e atributos.
- Pratique, pratique, pratique! 

## 📚 **Recursos Adicionais**

- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3Schools - HTML](https://www.w3schools.com/html/)
- [Curso em Vídeo - HTML5](https://www.cursoemvideo.com/curso/html5-css3-modulo1/)

---

Aproveite a jornada! 🚀
