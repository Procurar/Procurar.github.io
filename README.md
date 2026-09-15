# procurar.github.io

Página institucional da [Procurar](https://github.com/Procurar), publicada em
<https://procurar.github.io/> pelo GitHub Pages a partir deste repositório
(`main`, raiz).

## A tese da página

Um **clone do advogado, por escritório**. O que o sistema aprende — modelos de
peça, teses, treinamento e acervo — pertence a cada cliente; a engenharia que
sustenta o clone é a mesma. Trabalhista é o vertical do MVP, não o escopo.

Não publicar aqui: estágios, artefatos internos, nomes de gates e qualquer
número de inventário do motor. Isso é know-how, não argumento de venda.

## Como editar

Site estático, sem build e sem JavaScript: editar e commitar em `main` publica.

| Arquivo | O que é |
|---|---|
| `index.html` | a página inteira (âncoras `#oque`, `#garantias`, `#direcao`) |
| `assets/styles.css` | tokens de cor, tipografia, grades e adaptação a telas estreitas |
| `assets/fonts/newsreader-normal-400_700.woff2` | única família, subset latino, self-hosted |
| `assets/seal.svg` | favicon e monograma |
| `assets/og.png` | imagem de compartilhamento (1200x630) |

Uma família tipográfica, uma ação (e-mail), nenhum gradiente, nenhum menu.

## Rodar localmente

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Licença

AGPL-3.0-or-later.
