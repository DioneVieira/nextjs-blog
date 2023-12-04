---
title: 'Two Forms of Pre-rendering'
date: '2020-01-01'
---

<h2>Blog</h2>

Next.js has two forms of pre-rendering: **Static Generation** and **Server-side Rendering**. The difference is in **when** it generates the HTML for a page.

- **Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.

********************************************************************************************************************
**PT-BR**

Next.js tem duas formas de pré-renderização: **Geração Estática** e **Renderização no lado do servidor**. A diferença está em **quando** ele gera o HTML de uma página.

- **Geração Estática** é o método de pré-renderização que gera o HTML no **tempo de construção**. O HTML pré-renderizado é então _reutilizado_ em cada solicitação.
- **Renderização no lado do servidor** é o método de pré-renderização que gera o HTML em **cada solicitação**.

É importante ressaltar que Next.js permite que você **escolha** qual formulário de pré-renderização usar para cada página. Você pode criar um aplicativo Next.js "híbrido" usando geração estática para a maioria das páginas e renderização do lado do servidor para outras.
