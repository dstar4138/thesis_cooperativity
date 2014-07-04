all:
	pdflatex thesis.tex
	pdflatex thesis.tex
	bibtex thesis
	bibtex thesis
	pdflatex thesis.tex

clean:
	-rm chapters/*.aux
	-rm *.aux *.bbl *.blg *.idx *.log *.bak
	-rm *.lot *.toc *.lof

distclean: clean
	-rm *.pdf
