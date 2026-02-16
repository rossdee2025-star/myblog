---
layout: "src/layouts/PostDetails.astro"
title: "How to Add LaTeX Equations in Blog Posts"
description: "A demonstration of using LaTeX equations in Blog posts for AstroPaper."
author: "AstroPaper Contributor"
tags: ["LaTeX", "Markdown", "Blog"]
pubDatetime: 2026-02-16T07:00:00Z
canonicalURL: "https://astro-paper.pages.dev/posts/how-to-add-latex-equations-in-blog-posts/"
hideEditPost: false
---

This blog post demonstrates how to use LaTeX equations in your Markdown files for AstroPaper. LaTeX is a powerful typesetting system often used for mathematical and scientific documents.

## Instructions

### Install Plugins

Install necessary plugins via pnpm:
```
pnpm install remark-math rehype-katex katex
```

### Inline Equations

You can write inline equations such as $E = mc^2$ and $E = \frac{-b \pm \sqrt{b^2-4ac}}{2a}$. 

### Block Equations
For larger models:
```
$$1+e ^x$$«La formule finalise»

ψ Pi etc continue«Full validations»...