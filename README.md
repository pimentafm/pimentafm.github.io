# pimentafm.github.io

Personal portfolio / landing page for **Fernando Martins Pimenta** — Geospatial Solutions Architect.

🔗 **Live:** https://pimentafm.github.io

## Sobre

Site estático single-page (HTML/CSS/JS, zero dependências) hospedado no GitHub Pages,
com estética high-tech (globo geoespacial em canvas, boot sequence, HUD). Destaca os
**feitos & conquistas** — publicações peer-reviewed, livro técnico, datasets de escala
nacional e reconhecimentos — além de bio e stack tecnológica.

### Seções
- **whoami** — bio real (via Lattes/Escavador) + métricas de impacto
- **Trajetória & Formação** — timeline de experiência (EMBRAPA → UFV → GE21 → PhDSoft → Solutis/Serasa) + formação acadêmica (USP, UFV, UFSJ, Full Cycle)
- **Feitos & Impacto** — cards de conquistas (pesquisa, plataforma OBahia, BHALU, Arctic Code Vault, badges)
- **Publicações & Pesquisa** — timeline de artigos reais (via ORCID) com links DOI
- **Stack** — ferramentas e tecnologias

Dados de carreira/formação: arrays `experience` e `education` no `<script>` do `index.html`.

## Estrutura

```
.
├── index.html    # Página completa (estilos e scripts inline)
├── .nojekyll     # Desabilita o processamento Jekyll no GitHub Pages
└── README.md
```

## Deploy

1. Crie um repositório chamado **`pimentafm.github.io`** na sua conta GitHub.
2. Faça o push destes arquivos para a branch `main`:

   ```bash
   git init
   git add .
   git commit -m "feat: initial GitHub Pages portfolio"
   git branch -M main
   git remote add origin https://github.com/pimentafm/pimentafm.github.io.git
   git push -u origin main
   ```

3. Em **Settings → Pages**, defina *Source* como `Deploy from a branch` → `main` / `root`.
4. O site ficará disponível em `https://pimentafm.github.io` em alguns minutos.

## Personalização

- **Feitos:** edite o array `feitos` no `<script>` ao final do `index.html`.
- **Publicações:** edite o array `pubs` (dados vindos do ORCID) — cada item vira um link DOI.
- **Cores:** ajuste as variáveis CSS em `:root` (tema, acentos, glow).
- **Textos e links:** editáveis diretamente no HTML.

---

Built with ◆ &amp; deployed on GitHub Pages.
