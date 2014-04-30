proposal:
	pdflatex preproposal.tex
	-bibtex preproposal
	-bibtex preproposal
	pdflatex preproposal.tex
	-cp preproposal.pdf DeanAlexanderPreproposal.pdf

clean:
	-rm *.blg *.bbl *.aux *.log
	-rm preproposal.pdf
