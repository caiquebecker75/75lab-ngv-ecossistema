# NGV Ecossistema — Ecossistema em Movimento

Apresentação do stand NGV Ecossistema na Abradilan Conexão Farma, por 75 LAB.

Original publicado em https://casedeck.com.br/75lab-ngv-ecossistema/ (o primeiro commit deste repositório é a cópia fiel desse arquivo).

## Estrutura

```
index.html          página única com todo o HTML, CSS e JS
favicon.svg
assets/img/         renders, planta e peças promocionais (numerados na ordem em que aparecem)
assets/fonts/       Inter e Poppins (woff2)
```

No original, imagens e fontes vinham embutidas em base64 dentro do `index.html` (3,3 MB). Aqui foram extraídas para `assets/`, então o HTML ficou com ~100 KB e dá para editar texto e trocar imagens diretamente.

## Slides

| # | id | conteúdo |
|---|----|----------|
| 1 | `capa` | Ecossistema em Movimento |
| 2 | `manifesto` | manifesto |
| 3 | `conceito` | Um ecossistema revela sua força quando suas partes se conectam |
| 4 | `stand` | 40 m² que funcionam como percurso, não como caixa |
| 5 | `jornada` | Três momentos, uma só narrativa |
| 6 | `dentro` | O que o visitante encontra a cada passo |
| 7 | `tres-d` | Entre no stand antes da feira (navegação 3D em projetos.75lab.com.br) |
| 8 | `planta` | Os 40 m², área por área |
| 9 | `planta-baixa` | O desenho, sem intermediários |
| 10 | `atmosfera` | A identidade NGV, construída em três dimensões |
| 11 | `pecas` | A marca continua depois da feira |
| 12 | `fecho` | fechamento |
| 13 | `obrigado` | obrigado |

## Pré-visualizar

Abra o `index.html` por um servidor local (as imagens usam caminhos relativos), por exemplo:

```
npx serve .
```
