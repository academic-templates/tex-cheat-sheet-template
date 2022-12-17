## :information_source: Introduction

The goal of this template is to provide a nice-looking cheat sheet layout, easy to configure and fill in.

> This cheat sheet template is a largely inspired but purified version of [this template](https://www.latextemplates.com/template/baposter-landscape-poster).

Here is an example preview:

<p align="center"><img src="https://raw.githubusercontent.com/dhondta/tex-cheat-sheet-template/master/doc/preview.png" width="50%">


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

- [TeX Book Template](https://github.com/dhondta/tex-book-template): A template for writing a nice book with LaTeX.
- [TeX Course Index Template](https://github.com/dhondta/tex-course-index-template): A template for writing a condensed course index leveraging LaTeX indexing.
- [TeX Master Thesis Template](https://github.com/dhondta/tex-master-thesis-template): A template for writing a nice master thesis dissertation with LaTeX.
- [TeX Poster Template](https://github.com/dhondta/tex-poster-template): A template for creating a nice scientific poster with LaTeX.


## :clap: Supporters

[![Stargazers repo roster for @dhondta/tex-cheat-sheet-template](https://reporoster.com/stars/dark/dhondta/tex-cheat-sheet-template)](https://github.com/dhondta/tex-cheat-sheet-template/stargazers)

[![Forkers repo roster for @dhondta/tex-cheat-sheet-template](https://reporoster.com/forks/dark/dhondta/tex-cheat-sheet-template)](https://github.com/dhondta/tex-cheat-sheet-template/network/members)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

