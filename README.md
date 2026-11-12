# Landing Page — Curso de JavaScript

Projeto de estudo de uma landing page responsiva, construído com HTML e CSS. A página reúne exemplos de navegação por âncoras, seções com fundos alternados, layouts em Grid e Flexbox, galeria, tabela de preços e formulário.

## Como abrir

Abra `index.html` no navegador. Para uma experiência melhor durante o desenvolvimento, abra a pasta no VS Code e use uma extensão de servidor local, como Live Server.

O projeto não precisa de instalação de pacotes nem de etapa de compilação.

## Estrutura

```text
Lading Page/
├── index.html
└── assets/
    ├── css/
    │   ├── variables.css
    │   ├── elements.css
    │   ├── classes.css
    │   ├── menu.css
    │   └── styles.css
    └── img/
        ├── main-bg.svg
        ├── javascript.svg
        └── javascript-not-optimized.svg
```

## Conteúdo da página

- **Home:** título, texto introdutório e ilustração.
- **Intro:** seção de texto com fundo claro.
- **Grid one e grid two:** cartões organizados com CSS Grid e numeração feita com contadores CSS.
- **Gallery:** grade de imagens com efeito de zoom ao passar o cursor.
- **Pricing:** texto e tabela com rolagem horizontal em telas estreitas.
- **Contact:** formulário de exemplo e rodapé.

O menu usa links de âncora (`#intro`, `#gallery` etc.). Em telas menores, o menu é controlado por um checkbox e regras CSS, sem biblioteca JavaScript.

## Arquivos de estilo

- `variables.css`: cores e espaçamento definidos como propriedades personalizadas.
- `elements.css`: estilos básicos para elementos HTML, tipografia e tabelas.
- `classes.css`: classes reutilizáveis para fundos, seções e largura do conteúdo.
- `menu.css`: posicionamento e aparência da navegação.
- `styles.css`: layouts, galeria, formulário e regras responsivas.

## Imagens da galeria

As seis fotos usam URLs diretas do CDN `images.unsplash.com`. Elas são fixas; o endpoint aleatório antigo `source.unsplash.com` foi descontinuado. Para carregá-las, o navegador precisa ter acesso à internet.

## Conceitos praticados

HTML semântico, links por âncora, formulários, variáveis CSS, seletores, pseudo-elementos, contadores CSS, Flexbox, Grid, efeitos `:hover` e media queries.
