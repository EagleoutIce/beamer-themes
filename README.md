[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/) [![GPL license](https://img.shields.io/badge/License-GPL-blue.svg)](http://perso.crans.org/besson/LICENSE.html)  
![Compile all example PDFs](https://github.com/EagleoutIce/beamer-themes/workflows/Compile%20all%20example%20PDFs/badge.svg)
# beamer-themes

A hopefully growing collection of (latex) beamer-themes that i have created over the years.
All themes supplied are standalone versions but can be constructed via inner and outher themes if desired.

## General

Some resources are shared between all of the example-documents (they are just placeholders and therefore not necessary).
The example bibliography-file is based on an [overleaf-example](https://www.overleaf.com/learn/latex/Bibliography_management_in_LaTeX).

## colorful-dream

This theme is located [here](./colorful-dream) and _has_ BibLaTeX-Support.
Valid Options (defaults are marked):

- `nofont`/__`font`__ (automatic font-loading)
- `nolibs`/__`libs`__ (automatic loading of other libraries like tikz)
- __`noemblem`__/`emblem` (place emblem on titlepage, configure the emblem with `\SetEmblem`)
- __`notheorems`__/`theorems` (automatic configuration of theorems. Will define "exercise" and "solve").
- `nobib`/__`showbib`__ (shows bibliography on the last slide; will only be shown if biblatex is setup).

Other configuration-options and commands like `\email` and `\outro` are presented in the [example.tex](colorful-dream/example.tex):

![colorful-dream example image](colorful-dream/example.png)
Another example is located at [example.pdf](colorful-dream/example.pdf).

## lucy

This theme is located [here](./lucy) and _has_ BibLaTeX-Support. I've written this template for my abitur.
Valid Options (defaults are marked):

- `nofont`/__`font`__ (automatic font-loading. Loads the title-font too)
- `nolibs`/__`libs`__ (automatic loading of other libraries like tikz)

You must insert the title-page yourself, as seen in the [example.tex](lucy/example.tex):

![lucy example image](lucy/example.png)
Another example is located at [example.pdf](lucy/example.pdf).

## fragment

This theme is located [here](./fragment) and _has_ BibLaTeX-Support. It is loosely based on my sopra-seraphim class.
Valid Options (defaults are marked):

- `nofont`/__`font`__ (automatic font-loading. Loads the title-font too)
- `nolibs`/__`libs`__ (automatic loading of other libraries like tikz)

You must insert the title-page yourself, as seen in the [example.tex](fragment/example.tex):

![fragment example image](fragment/example.png)
(Note: the unbalanced lines on the title page come from weird anti-aliasing in the image and are not part of the template)  
Another example is located at [example.pdf](fragment/example.pdf).
