# procurar.github.io

Página institucional da organização [Procurar](https://github.com/Procurar),
publicada em <https://procurar.github.io/> pelo GitHub Pages a partir deste
repositório (`main`, raiz).

## Como editar

Site estático, sem build: editar o arquivo e commitar em `main` publica direto.

| Arquivo | O que é |
|---|---|
| `index.html` | a página inteira (uma só, com âncoras `#gargalo`, `#pipeline`, `#inteligencia`, `#jurisprudencia`, `#garantias`, `#operacao`, `#isolamento`, `#direcao`, `#codigo`) |
| `assets/styles.css` | tokens de cor, tipografia, layout e adaptação a telas estreitas |
| `assets/fonts/*.woff2` | Newsreader, Instrument Serif e IBM Plex Mono (subset latino, self-hosted) |
| `assets/seal.svg` | favicon e monograma |
| `assets/og.png` | imagem de compartilhamento (1200×630) |

## Posicionamento

A página apresenta o Procurar como um clone do advogado: o motor (estágios,
artefatos e gates) não tem matéria embutida; o que muda por área são os modelos
de peça e as fontes oficiais. O contencioso trabalhista é o MVP em produção e é
o vertical usado como exemplo concreto nas seções de pipeline e jurisprudência.

Ao mudar o sistema no repositório `engine`, conferir se os números desta página
(estágios, gates, jobs, pacotes de ML, tipos de peça) continuam verdadeiros.

## Rodar localmente

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Licença

AGPL-3.0-or-later.
