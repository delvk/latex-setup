# My Latex

[![LaTeX Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/92/LaTeX_logo.svg/220px-LaTeX_logo.svg.png)](https://www.latex-project.org/)

> This is how I setup my Latex develop environment

## Contents

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [My Latex](#my-latex)
  - [Contents](#contents)
  - [About LaTeX](#about-latex)
  - [Distributions](#distributions)
  - [Engines](#engines)
  - [Editors](#editors)
  - [Setup LaTeX (Step by step)](#setup-latex-step-by-step)
  - [References](#references)
  - [Bibliography tools](#bibliography-tools)
  - [Packages](#packages)
    - [Tables](#tables)
    - [LaTeX formulas on the web](#latex-formulas-on-the-web)
      - [TikZ](#tikz)
    - [Source Code](#source-code)
    - [Typography](#typography)
    - [Presentations, Slides](#presentations-slides)
  - [Templates](#templates)
  - [Symbols](#symbols)

<!-- /TOC -->

## About LaTeX

Guides how to I setup my LaTeX

## Distributions

- [MikTeX](https://miktex.org) - Most common LaTeX distribution for Windows, but also available for Mac, Linux or as Docker image.  ![linux] ![windows] ![mac] ![foss]

## Engines

- [pdfTeX](https://www.tug.org/applications/pdftex/) - TeX compiler that produces PDF files immediately instead of DVI files (nowadays, this is the standard compiler for many users).

This already included in MikTeX

## Editors

Some of the most awesome editor for LaTeX do just that: edit LaTeX.

- [TeXStudio](https://www.texstudio.org) - Cross-platform LaTeX editor that stems from TeXMaker.

## Setup LaTeX (Step by step)

1. Install Distribution: [MikTeX download](https://miktex.org/download)
2. Install Editor: [TeXStudio](https://www.texstudio.org)
3. After download MikTeX, Open MiTeX console -> Updates -> Check for Updates -> Updates all
4. Compile the file Sample.tex to install necessary packages

## References

- [egeerardyn/awesome-LaTeX](https://github.com/egeerardyn/awesome-LaTeX)


## Bibliography tools

- [JabRef](https://www.jabref.org) - Very powerful cross-platform (Java) bibtex editor. ![mac] ![windows] ![linux] ![foss]
- [Papis](https://github.com/papis/papis) - Extremely customizable,
  powerful and simple cross-platform (Python) library manager. It has a very
  complete Command-Line-Interface, several GUIs and scripting capability.
  ![linux] ![mac] ![foss]
- [Bibdesk](http://bibdesk.sourceforge.net) - Great bibliography editor for ![mac].
- [Zotero](https://www.zotero.org) - Reference manager for your browser that also exports to bibtex and integrates with many LaTeX editors. ![mac] ![windows] ![linux] ![foss]
- [Mendeley](https://www.mendeley.com) - Both an app and cloud client to manage your references and PDFs. Can sync out to a bibtex file for your LaTeX workflow. ![mac] ![windows] ![linux]
- [betterbib](https://github.com/nschloe/betterbib) - Command-line utility for improving your BibTeX files. Fetches information from online sources. ![mac] ![windows] ![linux] ![foss]

## Packages

- [CTAN](https://www.ctan.org) - The Comprehensive TeX Archive Network is the place to look for useful packages and documentation.

### Tables

- [Tables Generator](https://www.tablesgenerator.com) - This website provides a graphical interface to input your table and produces properly-formatted code for LaTeX, Markdown, HTML, etc.

### LaTeX formulas on the web

- [Auto-LaTeX Equations with Google Docs](https://sites.google.com/site/autolatexequations) - Render high-quality math equations directly in Google Docs.
- [MathJaX](https://www.mathjax.org) - JavaScript engine to render mathematical formulas on the web. The outcome looks really slick. ![foss]
- [mimeTeX](https://ctan.org/pkg/mimetex) - mimeTeX is a rather old tool to render LaTeX formulas to PNG figures for your web site, without actually needing a LaTeX installation on your server. ![foss]
- [mathTeX](https://ctan.org/pkg/mathtex) - mathTeX is the successor of mimeTeX: it produces nicer-looking images but it requires LaTeX to be installed on your server. ![foss]
- [KaTeX](https://khan.GitHub.io/KaTeX/) - KaTeX is a math rendering library made by Khan Academy focusing on fast load times. All output is processed as plain HTML instead of fixed images. ![foss]
- [Franklin.jl](https://franklinjl.org/) - Static site generator with KaTeX support, code evaluation, LaTeX-like commands and optional pre-rendering, in Julia. ![foss]
- [xhub](https://github.com/nschloe/xhub) - Browser extension that lets you use LaTeX in GitHub pages. ![foss]

#### TikZ

TikZ is an awesome package with many plugins that allow you to create figures from within your LaTeX documents.
Typically, it is easier to get to work with `pdflatex` than PSTricks is.

- [TeXample](https://www.texample.net) - Blog about LaTeX, with a big collection of TikZ figures.
- [LaTeX en SI](https://sciences-indus-cpge.papanicola.info/-LaTeX-en-SI-) - Useful website with some custom packages to draw special plots (Bode, Nyquist, electrical schematics, block schematics, etc.) using TikZ. Note that everything is in French.
- [pgfplots](http://pgfplots.sourceforge.net) - Truly awesome plotting library on top of and in the style of TikZ/pgf. This library can load in CSV data files, perform some calculations and create beautiful plots.
- [A very minimal introduction to TikZ (PDF)](https://cremeronline.com/LaTeX/minimaltikz.pdf) - Short introductory document to the world of TikZ, written by Jacques Crémer.
- [PetarV-/TikZ](https://github.com/PetarV-/TikZ) - Collection of publication-ready PGF/TikZ figures by Petar Veličković.
- [matlab2tikz](https://github.com/matlab2tikz/matlab2tikz) - Convert your MATLAB plots to PGFPlots/TikZ. ![windows] ![linux] ![mac] ![foss]
- [tikzplotlib](https://github.com/nschloe/tikzplotlib) - Convert your matplotlib plots to PGFPlots/TikZ. ![windows] ![linux] ![mac] ![foss]
- [TikZBlog](https://latexdraw.com) - Step-by-Step Tutorials about How to Draw Illustrations in LaTeX.

### Source Code

- [minted](https://www.ctan.org/pkg/minted) - The minted package uses [pygments](https://pygments.org/) to generate the listings. In this way, LaTeX is able to format more than 300 programming and markup languages and other text formats.

### Typography

- [microtype](https://ctan.org/pkg/microtype) - This package improves the appearance of your documents by enabling margin kerning and font expansion.

### Presentations, Slides

- [nics](https://nics.nilcons.com/) - An opinionated alternative to Beamer, that we created with the hopes to make common tasks very easy and beautifully rendered by default.  Has awesome documentation and a detailed cheatsheet to help you getting started.

## Templates

- [LaTeX templates](https://www.latextemplates.com) - Collection of templates for papers, posters, resumés, theses, books, presentations, … for LaTeX.
- [Ultimate Beamer Theme List](https://github.com/martinbjeldbak/ultimate-beamer-theme-list) - Links to various beamer themes along with PDF previews.
- [LaTeX Beamer Theme Overview](https://github.com/UweZiegenhagen/LaTeX-Beamer-Theme-Overview/blob/main/OVERVIEW.md) - Visual overview of beamer themes included in TeXLive

## Symbols

- [Comprehensive LaTeX symbol list](https://www.ctan.org/tex-archive/info/symbols/comprehensive/) - Very extensive list of symbols for LaTeX. Available in [A4](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-a4.pdf) and [letter](https://mirrors.ctan.org/info/symbols/comprehensive/symbols-letter.pdf) sizes.
- [Detexify](https://detexify.kirelabs.org/classify.html) - You draw the symbol and this site/app will tell you the LaTeX command.