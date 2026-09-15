# procurar.github.io

Página institucional da [Procurar](https://github.com/Procurar), publicada em
<https://procurar.github.io/> pelo GitHub Pages a partir deste repositório
(`main`, raiz).

## A tese da página

**Um clone do advogado, por escritório.** Treinamos agentes para trabalharem com
os modelos de peça, os padrões e o jeito do escritório do cliente. O ganho é
tempo de serviço e menos erro humano; a assinatura continua com o advogado.

O processo é apresentado como serviço artesanal — receber o acervo, agrupar e
ler os padrões, configurar o `.docx` da casa, treinar com supervisão e melhorar
em rodadas medidas (seção II). Trabalhista é o vertical do MVP, não o escopo.

Não publicar aqui: estágios internos, artefatos, nomes de gates e números de
inventário do motor. Isso é know-how, não argumento de venda.

## Como editar

Site estático, sem build e sem JavaScript:

| Arquivo | O que é |
|---|---|
| `index.html` | a página inteira (âncoras `#oque`, `#processo`, `#ganho`, `#porque`) |
| `assets/styles.css` | tokens de cor, tipografia, grades e adaptação a telas estreitas |
| `assets/fonts/newsreader-normal-400_700.woff2` | única família, subset latino, self-hosted |
| `assets/seal.svg` | favicon e monograma |
| `assets/og.png` | imagem de compartilhamento (1200x630) |

Regras do desenho, para não regredir:

- **Uma** família tipográfica (Newsreader), papel claro, sem gradiente, sem
  inverter cor de fundo em nenhuma faixa.
- **Uma** ação na página: o botão de e-mail na barra (fixa).
- Tudo dentro da coluna de conteúdo: hero, artefato, seções e rodapé começam no
  mesmo eixo; as réguas de seção também.
- O artefato é um fragmento de peça **estilizado** (sem dado de cliente) com
  notas de margem numeradas; a nota e o trecho se acendem juntos no hover, no
  foco do teclado e no clique (`:has()` + `:target`, sem JavaScript).

Ao mexer no sistema no repositório `engine`, conferir se o processo descrito na
seção II continua verdadeiro.

## Rodar localmente

```bash
python3 -m http.server 8080
# http://localhost:8080
```

## Licença

AGPL-3.0-or-later.
