# tkz-euclide --- for euclidan geometry

Release 3.05c 2020/03/08

## Description

`tkz-euclide` is a package (latex) which allows you to draw  two-dimensional
geometric figures, in other words to create figures of Euclidean geometry.
It uses a Cartesian coordinate system orthogonal provided by the tkz-base
package as well as tools to define the unique coordinates of points and to
manipulate them. The idea is to allow you to follow step by step a construction
that would be done by hand as naturally as possible.

## Licence

The scontents package may be modified and distributed under the terms and
conditions of the LaTeX Project Public License, version 1.3c or greater.

## Features
- needs tkz-base !!, xfp  and numprint;
- requires and automatically loads  PGF/TikZ > 3;
- compiles with utf8, pdflatex and lualatex;

## Installation

The package `tkz-eculide` is present in TeXLive and MiKTeX, use the package
manager to install.

You can experiment with the `tkz-euclide` package by placing all of the
distribution files in the directory containing your current tex file.

The different files must be moved into the different directories in your
installation `TDS` tree or in your `TEXMFHOME`:

```
  TDS:doc/latex/tkz-euclide/cheatsheet_euclide_1.pdf
  TDS:doc/latex/tkz-euclide/Euclidean_geometry.pdf
  TDS:doc/latex/tkz-euclide/cheatsheet_euclide_2.pdf
  TDS:doc/latex/tkz-euclide/TKZdoc-euclide.pdf
  TDS:doc/latex/tkz-euclide/examples/*.*
  TDS:doc/latex/tkz-euclide/sourcedoc/*.*
  TDS:tex/latex/tkz-euclide/*.*
```

## How to use it

To use the package `tkz-euclide`, place the following lines in the preamble of
your LaTeX document.

```
\usepackage{tkz-euclide}
```

`\usetkzobj{all}` is no longer required with tkz-euclide but you can use it with
other packages, `tkz-euclide` loads `tkz-base` and `TikZ`.

If you use the `xcolor` package, load that package before `tkz-euclide` to avoid
package conflicts.

## Documentation

Documentation for `tkz-euclide` is available on `CTAN`. You have two
cheatsheets about tkz-euclide in the archive. Use `texdoc tkz-euclide`.

## Examples

All  examples given in documentation will be stored on `CTAN` as standalone
files, ready for compilation. You can use the main.tex file to load and
compile  an example.

The archive contains a litle document about Euclidean Geometry with four
examples.

Other examples are on  my site : http://altermundus.fr (en français)

## Compatibility

The new version of `tkz-euclide` 3.05c is *not* fully compatible with the version
1.16 but the differences are minor.

## History
- 3.05 correction of bugs, amelioration of the documentation.
- 3.02 replacement french documentation by english documentation, correction of
bugs.
- 3.01 replacement  fp for xfp, addition of some macros, correction of bugs
- 1.16 correction of bugs
- 1.13 first version

## Author
 Alain Matthes
 5 rue de Valence
 Paris 75005

 al (dot) ma (at) mac (dot) com

