---
layout: post
title:  "SynTeX Editor"
summary: "LaTeX equation editor with selection syncing"
category: "Projects"
image: "syntex.png"
---

<div class="aspect-ratio" style="
  display: absolute;
  width: 100%;
  height: 600px;
  padding: 0;
"><iframe src="https://ayassaka.github.io/syn-tex/"/></div>

## What is this?

An interactive LaTeX equation editor with **selection syncing**.

That is, you can select source code from the rendered equation, and vice versa.

## How is this done?

This project is based on:

- [MathJax](https://www.mathjax.org/) with some [customization](https://github.com/Ayassaka/MathJax-src), which tracks TeX source location while compiling.
- [Ace Editor](https://ace.c9.io/), with great syntax highlighting support for LaTeX.
