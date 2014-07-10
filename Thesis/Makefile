all:
	pdflatex -shell-escape thesis.tex
	pdflatex -shell-escape thesis.tex
	bibtex thesis
	bibtex thesis
	pdflatex -shell-escape thesis.tex
	pdflatex -shell-escape thesis.tex

clean:
	-rm chapters/*.aux
	-rm *.aux *.bbl *.blg *.idx *.log *.bak *.dvi *.xml 
	-rm *.lot *.toc *.lof
	-rm thesis-blx.bib

distclean: clean
	-rm *.pdf
