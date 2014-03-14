proposal:
	pdflatex proposal.tex
	-bibtex proposal
	-bibtex proposal
	pdflatex proposal.tex
	-cp proposal.pdf DeanAlexanderProposal.pdf

clean:
	-rm *.blg *.pdf *.bbl *.aux *.log 
