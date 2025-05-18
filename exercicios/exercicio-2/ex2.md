# 📝 Exercício 2 – Formulário de Contato HTML5

## 🎯 Objetivo

Desenvolver um formulário de contato (`contato.html`) usando **HTML5** e validação nativa, garantindo acessibilidade e usabilidade.

---

## 📋 Requisitos Obrigatórios

✅ Seu formulário deve conter:

1. **Campo Nome**:

   * `<input type="text" id="nome" name="nome" required>`
2. **Campo Email**:

   * `<input type="email" id="email" name="email" required>`
3. **Campo Telefone** (opcional):

   * `<input type="tel" id="telefone" name="telefone">`
4. **Campo Mensagem**:

   * `<textarea id="mensagem" name="mensagem" required minlength="20"></textarea>`
5. **Botão de Envio**:

   * `<button type="submit">Enviar</button>`
6. Uso de `<label>` para cada campo, associado com `for` e `id`.
7. Agrupamento semântico usando `<fieldset>` e `<legend>`.

---

## ✅ Critérios de Avaliação

| Critério                              | Peso |
| ------------------------------------- | ---- |
| Presença e funcionamento de validação | 30%  |
| Estrutura acessível (labels e aria)   | 20%  |
| Uso de fieldset/legend corretamente   | 15%  |
| Mensagens nativas de validação        | 20%  |
| Código limpo e indentado              | 15%  |

---

## 📦 Entrega

* Salve como `contato.html`.
* Faça commit no GitHub ou compartilhe via Google Drive.
* Envie o link conforme as orientações.

---

> 💡 **Dica:** Use o console do navegador para testar as validações e o atributo `required`.
>
> 💡 Para verificar acessibilidade, experimente navegar apenas com o teclado e verifique se os campos recebem foco corretamente.
