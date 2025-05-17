# 🚀 Módulo 5 – Boas Práticas e PWA

Neste módulo, vamos abordar a organização de projetos web, uso do GitHub, práticas de performance e uma introdução ao desenvolvimento de aplicações web progressivas (PWA).

---

## Aula 5.1 – Organização de Projetos e GitHub

### Conteúdo

* Estrutura básica recomendada:

  ```
  projeto/
  ├── index.html
  ├── css/
  │   └── style.css
  ├── js/
  │   └── script.js
  ├── assets/
  │   └── imagens/
  └── README.md
  ```
* Nomeação clara de arquivos e pastas.
* Comentários no código.
* Uso do Git:

  * `git init`, `git add`, `git commit`, `git push`
* Criação de repositório no GitHub.
* Publicação com **GitHub Pages**.

### Atividade

Crie um repositório com estrutura organizada, publique sua página no GitHub Pages e compartilhe o link com a turma.

---

## Aula 5.2 – Performance e Otimização

### Conteúdo

* **Boas práticas de performance:**

  * Minimizar imagens e CSS.
  * Usar imagens nos tamanhos adequados (`.webp` recomendado).
  * Carregar scripts no final da página (`<script>` antes de `</body>`).
  * Usar `meta viewport` para responsividade.

### Exemplo

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="js/script.js" defer></script>
```

### Atividade

Otimize uma página existente usando `defer` para o JS, compressão de imagens e inclusão de `viewport`.

---

## Aula 5.3 – Introdução a Progressive Web Apps (PWA)

### Conteúdo

* **O que é uma PWA?**

  * Site que se comporta como aplicativo.
  * Funciona offline, instala no dispositivo e envia notificações.

* **Elementos principais de uma PWA:**

  * `manifest.json`: metadados da aplicação.
  * `service-worker.js`: permite funcionamento offline e cache.

### Exemplo – manifest.json básico

```json
{
  "name": "Meu App Web",
  "short_name": "AppWeb",
  "start_url": "/index.html",
  "display": "standalone",
  "background_color": "#ffffff",
  "theme_color": "#1a73e8",
  "icons": [
    {
      "src": "icons/icon-192.png",
      "sizes": "192x192",
      "type": "image/png"
    }
  ]
}
```

### Exemplo – service-worker.js simples

```js
self.addEventListener('install', function(e) {
  e.waitUntil(
    caches.open('versao-1').then(function(cache) {
      return cache.addAll([
        '/',
        '/index.html',
        '/css/style.css',
        '/js/script.js'
      ]);
    })
  );
});
```

### Atividade

Adicione um `manifest.json` simples e registre um `service-worker.js` em seu projeto. Teste no navegador Chrome em modo mobile.

---

## ✅ Resumo do Módulo 5

* Mantenha seu projeto limpo e bem organizado.
* Use Git e GitHub para versionamento e publicação.
* Aplique boas práticas para carregamento rápido e responsividade.
* Aprenda o básico de PWA para deixar seu site mais moderno e funcional.

> 💡 Para saber mais sobre PWAs: [https://web.dev/progressive-web-apps/](https://web.dev/progressive-web-apps/)
