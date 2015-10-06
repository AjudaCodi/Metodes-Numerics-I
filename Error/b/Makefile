# toc per a tenir llistes

all: lola.pdf
d:clear all
lola.pdf: lola.dvi
	dvipdf lola.dvi
lola.dvi: lola.toc
	latex ../motor/lola.tex
lola.toc:
	latex ../motor/lola.tex
clear:	
	rm lola.*
