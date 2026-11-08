# about_Thesis

Página pública de apresentação da **Thesis** — plataforma de IA para pesquisadores — feita para os jurados do HackBrasil 2026.

🔗 **Página:** https://medeirosdev.github.io/about_Thesis/
💻 **Código da plataforma:** https://github.com/medeirosdev/Thesis

A página explica o problema que a Thesis resolve, mostra telas reais da plataforma funcionando, como ela funciona,
a arquitetura, o que já está pronto e o roadmap.

## Estrutura

```
index.html            página única (HTML + CSS + JS inline, sem build)
assets/favicon.svg
assets/screens/       capturas reais da plataforma
.nojekyll             publica os arquivos como estão no GitHub Pages
```

## Ver localmente

Abra o `index.html` no navegador, ou:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Publicação

GitHub Pages servindo a branch `main`, pasta raiz (`Settings → Pages → Deploy from a branch → main / (root)`).
