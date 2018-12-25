LyX template for Technion IIT thesis
====================================

A lyx binding for a technion thesis LaTeX class by Eyal Rosenberg

Original LyX adaptation by Ronen Abravanel

Adaptation to LyX 2.3+ by Erez Zinman

Usage:
-----
* Download the whole file.
* Open 'thesis_head.lyx' file and follow instructions (Configure class, install Hebrew support, and choose Hebrew font).

Changelog:
---------
* V. 2.0
  * Updated to support LyX 2.3.
  * Added "Hebrew" module that, in this template, allows writing Hebrew inside the document anywhere.
  * Simplifies the font usage, and allows using any Englosh font wanted.
  * Changed bibliography engine to Natbib with good default style.

Requirements:
------------
* LyX version 2.3. Might work with newer/little-older versions as well. See http://www.lyx.org/
* Updated version of LaTeX (texlive 2011 and above. New version of Miktex on windows also work).
  * In debian \ Ubuntu, Install the package *texlive-lang-arabic*. 
* Proper Hebrew fonts:
  * For Linux, Use *Culmus* fonts (not culmus-latex fonts. Just proper culmus) .
  * For Windows, use *Ezra-SIL* fonts,  http://scripts.sil.org/ezrasil_home .
     If you find other nice hebrew fonts that works on Windows, please report [here](https://github.com/ronenabr/technion_thesis_lyx/issues/1).
  * Another nice font found is Alef (see http://alef.hagilda.com/ )

If you have problem with using the package, please report on github's [issue tracker](https://github.com/EZSlaver/technion_thesis_lyx/issues)

Original TeX template can be found at http://www.cs.technion.ac.il/graduate/etc/thesis-template/
Ronen's original LyX template can be found [here](https://github.com/ronenabr/technion_thesis_lyx)
