# Web personal

Sitio de CV/blog hecho con [Hugo](https://gohugo.io) y el tema [Archie](https://github.com/athul/archie).

## Desarrollo local

```sh
hugo server --bind 127.0.0.1 --port 1313 --disableFastRender
```

Abre `http://localhost:1313/`.

## Crear un post

Añade un archivo Markdown en `content/blog/`:

```md
---
title: "Título del post"
description: "Resumen breve"
date: 2026-05-11
draft: false
tags:
  - etiqueta
---

Contenido del post.
```

## Editar páginas principales

- Inicio: `content/_index.md`
- Experiencia: `content/experiencia.md`
- Proyectos: `content/proyectos.md`
- Contacto: `content/contacto.md`

## Generar el sitio estático

```sh
hugo
```

El resultado se genera en `public/`.
