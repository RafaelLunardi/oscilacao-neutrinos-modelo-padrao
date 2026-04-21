# Oscilação de neutrinos e os limites do Modelo Padrão

Blog acadêmico em Jekyll para acompanhar o TCC sobre física de partículas, neutrinos e limites do Modelo Padrão.

## Como publicar um novo post

Crie um arquivo Markdown dentro da pasta `_posts` com o formato:

```text
AAAA-MM-DD-titulo-do-post.md
```

Exemplo:

```text
2026-04-22-problema-dos-neutrinos-solares.md
```

No início do arquivo, use este cabeçalho:

```yaml
---
title: "Título do post"
categories: [neutrinos, experimentos]
tags: [super-kamiokande, sno]
excerpt: "Resumo curto do texto."
---
```

Depois do cabeçalho, escreva o texto normalmente em Markdown.

## Fórmulas

O blog usa MathJax. Fórmulas em linha podem ser escritas com `$...$`, e fórmulas destacadas com:

```text
$$
P(\nu_e \to \nu_\mu) = \sin^2(2\theta)\sin^2\left(\frac{\Delta m^2 L}{4E}\right)
$$
```

## Estrutura

- `_posts`: textos do blog.
- `_layouts`: modelos de páginas e posts.
- `_includes`: partes reutilizáveis do site.
- `assets/css/style.css`: aparência visual.
- `referencias.md`: bibliografia e fontes.
- `linha-do-tempo.md`: marcos históricos.
- `sobre.md`: apresentação do TCC.

## Publicação

Este repositório está preparado para GitHub Pages. Ao enviar alterações para a branch `main`, o site é publicado automaticamente.
