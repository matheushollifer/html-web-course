# 🧱 Módulo 2 – Elementos de Conteúdo

Neste módulo, exploraremos os elementos fundamentais que compõem o conteúdo visível de uma página HTML. Você aprenderá a utilizar textos, listas, imagens e links de forma correta e acessível.

---

## Aula 2.1 – Textos, Parágrafos e Cabeçalhos

### Conteúdo

* `<p>`: parágrafos de texto.
* `<h1>` a `<h6>`: títulos e subtítulos em diferentes níveis hierárquicos.
* `<strong>`, `<em>`, `<mark>`, `<small>`, `<del>`, `<ins>`, `<sub>`, `<sup>`: elementos de marcação textual.

### Exemplo

```html
<h1>Curso de HTML</h1>
<h2>Módulo 2 – Texto</h2>
<p>Aprendemos a marcar <strong>trechos importantes</strong> e <em>termos em destaque</em>.</p>
<p>Nota: H<sub>2</sub>O é água. E = mc<sup>2</sup></p>
```

### Atividade

Crie um artigo com título, subtítulo, parágrafos, e destaque palavras com `<strong>`, `<em>` e `<mark>`.

---

## Aula 2.2 – Listas Ordenadas e Não Ordenadas

### Conteúdo

* `<ul>`: lista não ordenada (com marcadores).
* `<ol>`: lista ordenada (com números).
* `<li>`: item de lista.

### Exemplo

```html
<h2>Lista de Compras</h2>
<ul>
  <li>Arroz</li>
  <li>Feijão</li>
  <li>Batata</li>
</ul>

<h2>Passos para criar uma página</h2>
<ol>
  <li>Abrir o editor</li>
  <li>Criar o arquivo .html</li>
  <li>Salvar e abrir no navegador</li>
</ol>
```

### Atividade

Crie uma página com uma lista ordenada e uma lista não ordenada.

---

## Aula 2.3 – Links e Navegação

### Conteúdo

* `<a href="">`: ancora um link.
* Atributos: `href`, `target="_blank"`, `title`.
* Pode envolver textos ou imagens.

### Exemplo

```html
<p>Acesse o <a href="https://www.w3schools.com" target="_blank" title="W3Schools">site de referência</a>.</p>
```

### Atividade

Adicione pelo menos três links à sua página, incluindo um externo e dois internos (mesmo documento com `#id`).

---

## Aula 2.4 – Imagens e Acessibilidade

### Conteúdo

* `<img src="" alt="">`: exibe uma imagem.
* Atributos importantes:

  * `src`: caminho da imagem.
  * `alt`: descrição para leitores de tela.
  * `width` e `height`: tamanhos personalizados.

### Exemplo

```html
<img src="logo.png" alt="Logo do curso" width="200">
```

### Acessibilidade

* O atributo `alt` é **obrigatório** para acessibilidade e SEO.

### Atividade

Insira uma imagem com `alt` adequado e ajuste o tamanho com `width` e `height`.

---

> 💡 Dica: Combine `<a>` com `<img>` para criar links clicáveis em imagens:
>
> ```html
> <a href="index.html">
>   <img src="logo.png" alt="Voltar para a página inicial">
> </a>
> ```

---

## ✅ Resumo do Módulo 2

* Utilize títulos e parágrafos para organizar seu conteúdo.
* Use listas para sequências e agrupamentos.
* Crie links funcionais com `<a>` e mantenha imagens acessíveis com `alt`.

> 📝 Na próxima aula veremos como agrupar conteúdos com `<div>`, `<span>`, e como montar tabelas HTML!
