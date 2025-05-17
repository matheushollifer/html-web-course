# 📘 Curso de Desenvolvimento de Páginas Web

Bem-vindo ao repositório oficial da disciplina **Desenvolvimento de Páginas Web**! Este espaço foi criado para oferecer aos alunos uma experiência moderna e interativa no aprendizado de HTML5, com aulas estruturadas, exemplos comentados e exercícios práticos.

---

## ✅ Módulo 1 – Fundamentos do HTML5

### Aula 1.1 – O que é HTML e sua evolução

#### Conteúdo

* HTML é a sigla para **HyperText Markup Language** (Linguagem de Marcação de Hipertexto).
* Sua principal função é **estruturar o conteúdo** das páginas web.
* Não é uma linguagem de programação; é uma **linguagem de marcação**.
* A versão atual é o **HTML5**, que introduziu tags semânticas, suporte a multimídia e APIs modernas para web.

#### Exemplo

```html
<!-- Estrutura básica de uma página HTML5 -->
<!DOCTYPE html>
<html>
<head>
  <title>Minha Primeira Página</title>
  <meta charset="utf-8">
</head>
<body>
  <p>Olá, mundo!</p>
</body>
</html>
```

#### Atividade

Crie um arquivo chamado `index.html` com o conteúdo acima e abra-o no navegador.

---

### Aula 1.2 – Estrutura básica de um documento HTML

#### Conteúdo

* A estrutura mínima de um documento HTML inclui:

  * `<!DOCTYPE html>`: declaração da versão.
  * `<html>`: elemento raiz.
  * `<head>`: metadados (título, codificação, links externos).
  * `<body>`: conteúdo visível da página.

#### Exemplo

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Página Básica</title>
</head>
<body>
  <h1>Estrutura HTML</h1>
  <p>Esta é a estrutura mínima de um documento HTML5.</p>
</body>
</html>
```

#### Atividade

Abra o Sublime Text ou outro editor, digite o código acima, salve como `estrutura.html` e abra no navegador.

---

### Aula 1.3 – Meta tags e SEO básico

#### Conteúdo

* As **meta tags** informam aos navegadores e mecanismos de busca informações sobre a página.
* São inseridas no `<head>` do documento.
* Exemplos:

  * `<meta charset="utf-8">`: define a codificação.
  * `<meta name="description" content="Descrição da página">`
  * `<meta name="keywords" content="html, curso, programação">`
  * `<meta name="author" content="Seu Nome">`

#### Exemplo

```html
<head>
  <meta charset="utf-8">
  <meta name="description" content="Curso introdutório de HTML">
  <meta name="keywords" content="html, web, ifsudeste">
  <meta name="author" content="Rafael Alencar">
  <title>Curso HTML</title>
</head>
```

#### Atividade

Crie uma página com pelo menos 3 meta tags e visualize no navegador. Teste com o modo "Responsivo" nas ferramentas do desenvolvedor.

---

### Aula 1.4 – Novas tags semânticas do HTML5

#### Conteúdo

O HTML5 trouxe novas tags para tornar a estrutura da página **mais significativa**, melhorando **acessibilidade** e **SEO**:

* `<header>`: cabeçalho do site ou seção
* `<nav>`: navegação
* `<main>`: conteúdo principal
* `<section>`: seção genérica de conteúdo
* `<article>`: conteúdo independente (ex: post de blog)
* `<aside>`: conteúdo lateral relacionado
* `<footer>`: rodapé

#### Exemplo

```html
<body>
  <header>
    <h1>Portal Notícias</h1>
    <nav>
      <a href="#">Início</a> |
      <a href="#">Contato</a>
    </nav>
  </header>
  <main>
    <article>
      <h2>Nova biblioteca é inaugurada</h2>
      <p>Texto da notícia...</p>
    </article>
    <aside>
      <p>Publicidade</p>
    </aside>
  </main>
  <footer>
    <p>© 2025 IF Sudeste MG</p>
  </footer>
</body>
```

#### Atividade

Reescreva sua página `index.html` utilizando pelo menos 3 dessas tags semânticas.

---

> 💡 **Dica**: Sempre comente seu código para manter a organização!
>
> ```html
> <!-- Início da navegação -->
> <nav>...</nav>
> ```

---

## 🔗 Referências

* [W3C HTML5](https://www.w3.org/TR/html5/)
* [Tableless – HTML5 Semântico](http://tableless.com.br/html5-estrutura-semantica/)
* Apostilas base: `html.pdf` e `introducao.pdf` (Prof. Rafael Alencar)
