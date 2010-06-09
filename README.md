# Timetable

## How it's going to look like

An example how a timetable created with this LaTeX package (v.1.41) looks like:
![sample for the style of the timetable](http://img444.imageshack.us/img444/3129/sampletimetable.png)

## Overview

This is the latest version 1.41 of a LaTeX package for creating one-week timetables as they can frequently be found in universities or schools. It contains bugfixes to 1.4.

New features of this version are pdfLaTeX compatibility, and several design extensions. This package is fully interface compatible to documents created under version 1.3, and contains all amendments proposed by Daniel Bader. Like its predecessor, however, it is unfortunately incompatible to versions 1.1 and 1.2.

## Website

More information can be found online on the project website <http://www.planetk.de/index.php?title=Stundenplan>.

## Usage

You can compile the timetable to PDF via LaTeX and PostScript:

    latex example.tex && dvips example.dvi && ps2pdf example.ps

and directly with pdfLaTeX

    pdflatex example.tex

The package additionally contains a PDF manual with explanations and examples. Please note again that this package does not work with documents using the old syntax of versions 1.1 and 1.2 (which you might still find on the net).

## License

The timetable LaTeX style sheet is free software. You can redistribute and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation. You may use version 3 of the license, or (at your option) any later version.

If you decide to redistribute this package, please leave the name of the original author, Pascal Gwosdek, in the header of the file or move it into a file AUTHORS.

