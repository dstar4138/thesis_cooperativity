all:
	pdflatex thesis.tex
	pdflatex thesis.tex
	bibtex thesis
	bibtex thesis
	pdflatex thesis.tex
	pdflatex thesis.tex

clean:
	-rm chapters/*.aux
	-rm *.aux *.bbl *.blg *.idx *.log *.bak *.dvi *.xml 
	-rm *.lot *.toc *.lof
	-rm thesis-blx.bib

distclean: clean
	-rm *.pdf
