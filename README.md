# Bash sem aperreio

Site Quarto da aula introdutória de Bash para o PPGMM.

## Conteúdo

- `index.qmd`: página inicial
- `roteiro.qmd`: roteiro prático completo
- `slides.qmd`: apresentação Reveal.js
- `_quarto.yml`: configuração do site

## Visualização local

```bash
quarto preview
```

## Publicação

O fluxo em `.github/workflows/publish.yml` renderiza o projeto e publica o conteúdo no GitHub Pages a cada atualização da branch `main`.

Depois do primeiro envio, configure o repositório em **Settings → Pages → Source → GitHub Actions**.

## Licença e atribuição

O material adapta [Bare Bones Bash](https://github.com/BareBonesBash/barebonesbash.github.io), de James A. Fellows Yates e Thiseas C. Lamnidis, sob a licença [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
