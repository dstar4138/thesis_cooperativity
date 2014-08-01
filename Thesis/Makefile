all: compile compile-anon
	mv thesis.pdf DeanAlexanderThesis.pdf
	mv thesis-anon.pdf Thesis-Anonymized.pdf

compile:
	pdflatex -shell-escape thesis.tex
	pdflatex -shell-escape thesis.tex
	bibtex thesis
	bibtex thesis
	pdflatex -shell-escape thesis.tex
	pdflatex -shell-escape thesis.tex

compile-anon:
	pdflatex -shell-escape thesis-anon.tex
	pdflatex -shell-escape thesis-anon.tex
	bibtex thesis-anon
	bibtex thesis-anon
	pdflatex -shell-escape thesis-anon.tex
	pdflatex -shell-escape thesis-anon.tex

clean:
	-rm chapters/*.aux
	-rm *.aux *.bbl *.blg *.idx *.log *.bak *.dvi *.xml 
	-rm *.lot *.toc *.lof
	-rm thesis-blx.bib

distclean: clean
	-rm *.pdf
