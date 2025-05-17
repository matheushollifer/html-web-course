# 📥 Módulo 4 – Formulários e Interatividade

Neste módulo, vamos aprender a criar formulários HTML para entrada de dados, explorar diferentes tipos de campos (`input`), aplicar validação básica e melhorar a acessibilidade dos formulários.

---

## Aula 4.1 – Campos de Formulário Básicos

### Conteúdo

* `<form>`: elemento que agrupa os campos.
* `<input>`: campo de entrada.
* `<label>`: legenda associada a um campo.
* `<textarea>`: área de texto de várias linhas.
* `<select>` e `<option>`: menus suspensos.

### Exemplo

```html
<form action="#" method="post">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome"><br>

  <label for="mensagem">Mensagem:</label><br>
  <textarea id="mensagem" name="mensagem" rows="4" cols="30"></textarea><br>

  <label for="curso">Curso:</label>
  <select id="curso" name="curso">
    <option value="html">HTML</option>
    <option value="css">CSS</option>
    <option value="js">JavaScript</option>
  </select>

  <br><br>
  <input type="submit" value="Enviar">
</form>
```

### Atividade

Crie um formulário com pelo menos 3 campos diferentes e um botão de envio.

---

## Aula 4.2 – Validação nativa do HTML5

### Conteúdo

* Atributos de validação:

  * `required`: campo obrigatório.
  * `minlength`, `maxlength`: número mínimo/máximo de caracteres.
  * `pattern`: expressão regular.
  * `type`: define o tipo de dado e ativa validações automáticas.

### Exemplo

```html
<form>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required><br>

  <label for="senha">Senha (mín. 6 caracteres):</label>
  <input type="password" id="senha" name="senha" minlength="6" required><br>

  <input type="submit" value="Entrar">
</form>
```

### Atividade

Crie um formulário de login com validação de email e senha obrigatória com no mínimo 6 caracteres.

---

## Aula 4.3 – Novos Tipos de Input

### Conteúdo

Novos tipos adicionados ao HTML5 permitem controle e validação automática:

* `email`, `tel`, `url`, `number`, `range`, `date`, `time`, `color`, etc.

### Exemplo

```html
<form>
  <label for="data">Data:</label>
  <input type="date" id="data" name="data"><br>

  <label for="cor">Cor favorita:</label>
  <input type="color" id="cor" name="cor"><br>

  <label for="nivel">Nível de satisfação:</label>
  <input type="range" id="nivel" name="nivel" min="0" max="10">
</form>
```

### Atividade

Experimente pelo menos 4 tipos de `input` diferentes em um formulário. Teste no navegador e observe o comportamento de cada campo.

---

## Aula 4.4 – Acessibilidade em Formulários e ARIA Básico

### Conteúdo

* Sempre utilize `<label>` associado ao campo (`for` ↔ `id`).
* Campos devem ter textos descritivos e ordem lógica.
* Use `fieldset` e `legend` para agrupar campos.
* Atributos ARIA (opcional, introdução): `aria-label`, `aria-required`, etc.

### Exemplo

```html
<form>
  <fieldset>
    <legend>Dados Pessoais</legend>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" aria-required="true"><br>
  </fieldset>
</form>
```

### Atividade

Crie um formulário acessível contendo:

* Campo obrigatório com `required` e `aria-required`.
* `label` claro e vinculado.
* Agrupamento com `fieldset` e `legend`.

---

> 💡 Dica: Valide seus formulários com ferramentas como [https://wave.webaim.org](https://wave.webaim.org) para verificar acessibilidade.

---

## ✅ Resumo do Módulo 4

* Formulários são a principal forma de interação com o usuário.
* HTML5 oferece recursos poderosos de validação automática.
* A acessibilidade deve sempre ser considerada na criação de interfaces.

> 📝 Em breve: como organizar projetos e aplicar boas práticas com GitHub e PWA!
