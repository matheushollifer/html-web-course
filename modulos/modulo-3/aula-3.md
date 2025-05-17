# 🧩 Módulo 3 – Estrutura e Layout

Neste módulo, vamos aprender a organizar e estruturar visualmente o conteúdo da página utilizando agrupadores genéricos (`div` e `span`), elementos de separação (`hr`, `br`) e a construção de tabelas semânticas com HTML.

---

## Aula 3.1 – Agrupamentos com `<div>` e `<span>`

### Conteúdo

* `<div>`: bloco genérico usado para agrupar elementos em seções.
* `<span>`: agrupador inline usado para destacar partes de texto.
* Muito usados com CSS para estilização.

### Exemplo

```html
<div>
  <h2>Seção de Destaque</h2>
  <p>Este conteúdo está dentro de uma <strong>div</strong>.</p>
</div>

<p>O preço é <span style="color: green; font-weight: bold;">R$ 49,90</span></p>
```

### Atividade

Crie uma página com duas `div`s representando seções distintas e use `span` para destacar palavras dentro de um parágrafo.

---

## Aula 3.2 – Quebras e Separadores

### Conteúdo

* `<br>`: quebra de linha. Evite uso excessivo.
* `<hr>`: linha horizontal usada como separador de seções.

### Exemplo

```html
<p>Primeira linha<br>Segunda linha</p>

<hr>

<h2>Nova Seção</h2>
```

### Atividade

Crie uma página com pelo menos duas seções separadas por `<hr>` e um parágrafo com uma quebra de linha.

---

## Aula 3.3 – Tabelas Semânticas para Dados

### Conteúdo

* Elementos de tabela:

  * `<table>`: inicia a tabela.
  * `<thead>`: cabeçalho da tabela.
  * `<tbody>`: corpo da tabela.
  * `<tfoot>`: rodapé da tabela.
  * `<tr>`: linha.
  * `<th>`: célula de cabeçalho (negrito e centralizado).
  * `<td>`: célula de dado.

### Exemplo

```html
<table border="1">
  <thead>
    <tr>
      <th>Produto</th>
      <th>Preço</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Notebook</td>
      <td>R$ 3.200,00</td>
    </tr>
    <tr>
      <td>Mouse</td>
      <td>R$ 79,90</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Valores sujeitos a alteração</td>
    </tr>
  </tfoot>
</table>
```

### Atividade

Crie uma tabela com pelo menos 3 colunas e 3 linhas. Utilize `<thead>`, `<tbody>` e `<tfoot>`.

---

> 💡 Dica: Use CSS para aplicar estilos como `border-collapse`, `text-align`, `padding`, etc., e melhorar a aparência das suas tabelas.

---

## ✅ Resumo do Módulo 3

* `div` e `span` ajudam a estruturar e personalizar áreas específicas da página.
* `hr` e `br` facilitam a separação e formatação simples.
* Tabelas são úteis para apresentar dados tabulados com clareza e semântica.

> 📝 Em breve: formulários, campos e validação nativa com HTML5 no próximo módulo!
