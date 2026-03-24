# PocketCardsApp-Docs

Este repositorio contem a documentacao publica e as paginas HTML do projeto PocketCards.

Neste momento, a docs inclui uma pequena presenca web para apresentar a app, explicar como contribuir e disponibilizar a politica de privacidade do projeto.

## Paginas incluidas

- `index.html`
  Homepage de apresentacao da app.
- `contribute.html`
  Pagina com orientacoes para contribuir para o projeto.
- `politicas.html`
  Pagina de politica de privacidade.

## Recursos visuais

Os assets principais usados pelas paginas ficam em:

- `Res/icon.png`
- `Res/banner.png`
- `Res/Prints/`

Estes recursos sao usados na identidade visual da homepage e das restantes paginas.

## Objetivo deste repositorio

Separar a documentacao publica do codigo da aplicacao Android, permitindo:

- manter uma landing page simples para o PocketCards
- publicar documentacao estatica facilmente
- evoluir paginas institucionais sem mexer diretamente na app

## Publicacao

Este repositorio esta preparado para ser usado com hosting estatico, como GitHub Pages.

Para pre-visualizar localmente, basta abrir os ficheiros HTML no browser ou servir a pasta com um servidor estatico simples.

Exemplo com Python:

```bash
cd PocketCardsApp-Docs
python -m http.server 8000
```

Depois abre:

```text
http://localhost:8000
```

## Relacao com o projeto principal

Codigo da app Android:

- `https://github.com/ProjetosLendarios/PocketCards-App`

Este repositorio contem apenas a parte documental e visual publica do projeto.

## Estrutura

- `index.html`
- `contribute.html`
- `politicas.html`
- `Res/`
- `LICENSE`

## Licenca

Consulta o ficheiro `LICENSE` deste repositorio para detalhes.
