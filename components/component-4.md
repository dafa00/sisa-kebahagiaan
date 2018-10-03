---
layout: default
type: components
title: Component 4
---
\- name: "page"

\    label: "Page"

\    folder: "pages"

\    sort: "title:asc"

\    create: false

\    slug: "{{slug}}"

\    fields:

\- {label: "Layout", name: "layout", widget: "hidden", default: "page"}

\- {label: "Title", name: "title", widget: "string", tagname: "h1"}

\- {label: "Permalink", name: "permalink", widget: "hidden"}

\- {label: "Section", name: "section", widget: "hidden", default: "{{name}}"}

\- {label: "Intro Paragraph", name: "intro_paragraph", widget: "markdown", required: false}

\- {label: "Body", name: "body", widget: "markdown", required: false}
