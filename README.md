 % encodage utf8    

--------------------  english readme ----------------------------------------

readme-tkz-euclide.txt V3.05 c 2020/03/08

tkz-euclide is a package (latex) which allows you to draw  two-dimensional 
geometric figures, in other words to create figures of Euclidean geometry. 
It uses a Cartesian coordinate system orthogonal provided by the tkz-base 
package as well as tools to define the unique coordinates of points and to 
manipulate them. The idea is to allow you to follow step by step a construction 
that would be done by hand as naturally as possible.

Licence
-------

This work may be distributed and/or modified under the
conditions of the LaTeX Project Public License, either version 1.3
 of this license or (at your option) any later version.
 The latest version of this license is in
   http://www.latex-project.org/lppl.txt
 and version 1.3 or later is part of all distributions of LaTeX
 version 2005/12/01 or later.


Features
--------
 -- needs tkz-base !!, xfp  and numprint;
 -- requires and automatically loads  PGF/TikZ > 3; 
 -- compiles with utf8, pdflatex and lualatex;
  
Installation  
------------

You can experiment with the tkz-euclide package by placing all of the
distribution files in the directory containing your current tex file.

You can also placing all of the distribution files in the directory : 
/texmf/tex/latex/tkz.

 
How to use it
-------------

To use the package tkz-euclide, place the following lines in the preamble of
 your LaTeX document.

\usepackage{tkz-euclide} 

\usetkzobj{all} is no longer required with tkz-euclide but you can use it with other packages
 
\usepackage{tkz-euclide}  loads tkz-base and TikZ. 

If you use the xcolor package, load that package before tkz-euclide to avoid
 package conflicts.


Documentation
-------------

Documentation for tkz-euclide and tkz-base is available on CTAN. You have two cheatsheets about tkz-euclide in the archive.

Examples
--------

All  examples given in documentation will be stored on CTAN as standalone
  files, ready for compilation. You can use the main.tex file to load and compile  an example. 
The archive contains a litle document about Euclidean Geometry with four examples.
Other examples are on  my site : http://altermundus.fr (en français)  

Compatibility
-------------  

The new package tkz-euclide 3.02c is *not* fully compatible with the version 1.16 but the differences are minor.

History
-------
-- 3.05 correction of bugs, amelioration of the documentation.
-- 3.02 replacement french documentation by english documentation, correction of bugs.
-- 3.01 replacement  fp for xfp, addition of some macros, correction of bugs
-- 1.16 correction of bugs
-- 1.13 first version

 Alain Matthes
 5 rue de Valence
 Paris 75005  
 
 al (dot) ma (at) mac (dot) com              
