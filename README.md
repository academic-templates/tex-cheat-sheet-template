<h1 align="center">LaTeX Cheat Sheet Template <a href="https://twitter.com/intent/tweet?text=LaTeX%20Cheat%20Sheet%20Template.%0D%0ALaTeX%20template%20for%20creating%20your%20attractive%20cheat%20sheet%2e%0D%0A&hashtags=TeXLaTeX"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a></h1>

## :information_source: Introduction

The goal of this template is to provide a nice-looking cheat sheet layout, easy to configure and fill in.

> This cheat sheet template is a largely inspired but purified version of [this template](https://www.latextemplates.com/template/baposter-landscape-poster).

Here is an example preview:

<p align="center"><img src="https://raw.githubusercontent.com/academic-templates/tex-cheat-sheet-template/main/doc/preview.png" width="50%"><br>
<sub><sup>Preview image generated with <a href="https://gist.github.com/dhondta/f57dfde304905644ca5c43e48c249125">this tool</a></sup></sub></p>


## :card_file_box: Structure

The template is structured in the following way:

- `main.tex`: This is the main TeX file to be compiled. Here you can include your payload.
- `figures`: This folder is aimed to contain logos and figures.
- `styles`: This folder contains the styles for defining the layout. Most of the included ones should not be edited.

## :gear: Compilation

The compilation can easilly be configured in [Texmaker](https://en.wikipedia.org/wiki/Texmaker) by defining a *Quick Build Command*:

1. Go to the menu *Options*
2. Select *Configure Texmaker*
3. Go to tab *Quick Build*
4. In the field *User : (...)*, replace the command with:

        pdflatex -synctex=1 -interaction=nonstopmode %.tex|bibtex %.aux|pdflatex -synctex=1 -interaction=nonstopmode %.tex

5. Then click *OK*

This will produce `main.pdf`.

## :newspaper: Making your cheat sheet

Parts that you should adapt:

- `main.tex`
- include images in `figures` and refer to these in `main.tex`


## :star: Related Projects

You may also like these:

- [TeX Book Template](https://github.com/academic-templates/tex-book-template): A template for writing a nice book with LaTeX.
- [TeX Course Index Template](https://github.com/academic-templates/tex-course-index-template): A template for writing a condensed course index leveraging LaTeX indexing.
- [TeX Master Thesis Template](https://github.com/academic-templates/tex-master-thesis-template): A template for writing a nice master thesis dissertation with LaTeX.
- [TeX Poster Template](https://github.com/academic-templates/tex-poster-template): A template for creating a nice scientific poster with LaTeX.
- [TeX Slideshow Template](https://github.com/academic-templates/tex-slideshow-template): A template for making a nice presentation with LaTeX.


## :clap: Supporters

[![Stargazers repo roster for @academic-templates/tex-cheat-sheet-template](https://reporoster.com/stars/dark/academic-templates/tex-cheat-sheet-template)](https://github.com/academic-templates/tex-cheat-sheet-template/stargazers)

[![Forkers repo roster for @academic-templates/tex-cheat-sheet-template](https://reporoster.com/forks/dark/academic-templates/tex-cheat-sheet-template)](https://github.com/academic-templates/tex-cheat-sheet-template/network/members)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

