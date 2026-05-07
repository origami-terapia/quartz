---
title: Bruno Ferraz | Psicologia Clínica
---
Entendi perfeitamente! Vou criar um template com cabeçalho e rodapé em HTML/CSS, com uma área central claramente delimitada onde você cola seu texto em Markdown puro. O Quartz renderiza o Markdown normalmente mesmo dentro de arquivos `.md` com HTML.

Criou um arquivo, leu um arquivo

Criou um arquivo, leu um arquivo

Pronto! Como funciona:

**A área de conteúdo fica claramente marcada com comentários:**

```
<!-- ▼▼▼ INÍCIO DO CONTEÚDO — cole e edite seu Markdown aqui ▼▼▼ -->
<div class="lp-content">

## Seu texto aqui em Markdown puro...

</div>
<!-- ▲▲▲ FIM DO CONTEÚDO ▲▲▲ -->
```

Você escreve tudo entre o `<div class="lp-content">` e o `</div>` normalmente em Markdown — parágrafos, `##` títulos, listas, `**negrito**`, `> citações`, `---` separadores. O Quartz renderiza tudo isso sem problema.

**O que você precisa editar em cada página nova:**

1. O `description:` no frontmatter
2. O `<h1>` e o subtítulo no cabeçalho
3. O conteúdo entre os marcadores `▼▼▼` e `▲▲▲`

O cabeçalho e rodapé ficam intocados na maioria das páginas.