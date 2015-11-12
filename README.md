"How to Win Proportional Representation" Slide Sources
======================================================

The sources for these slides are admittedly hideous. I release them
out of ideology, and in the hopes that somebody might take inspiration
from them, but you probably do not want to use them as an example of
best practices. 

The slides are released under a CC-BY-SA 4.0 license. 


Requirements
------------

This is easiest to compile on a Linux system, but you can probably
make it work with Windows. 

On Debian, you want the following packages installed: 
biblatex biber beamer texlive texlive-fonts-extra

Basic Compilation
-----------------

cd tmp
pdflatex ../2015-10-28-howto-win-pr.tex
biber 2015-10-18-howto-win-pr
pdflatex ../2015-10-28-howto-win-pr.tex
pdflatex ../2015-10-28-howto-win-pr.tex


Spooky Font
-----------

The spooky font is "Green Fuz" from Larabie fonts. You can run the 
script in addfont/ to register it if you have the "greenfuz.ttf" file
in that folder. In Debian, you can find this font in the non-free
repository: 

fonts-larabie-uncommon: /usr/share/fonts/truetype/larabie/greenfuz.ttf

(Yes, the font is non-free, but it is offered pretty liberally.) 


Graphs 
------

The bar graphs are created using matplotlib and a python script. They
are not in these sources, but you should (eventually) be able to find
them in the same place where you found these slide sources (maybe
<http://github.com/pnijjar> ?) 

- Paul "Worthless" Nijjar, 2015-11-11
