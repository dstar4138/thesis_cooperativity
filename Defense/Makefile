all: presentation
	mv presentation.pdf DeanAlexanderThesisDefense.pdf
	pdfnup --nup 1x3 --no-landscape --scale 0.9 --delta "0 1cm" --no-tidy DeanAlexanderThesisDefense.pdf
	mv DeanAlexanderThesisDefense-nup.pdf DeanAlexanderThesisDefenseHandouts.pdf

presentation:
	pdflatex presentation.tex
	pdflatex presentation.tex

clean:
	-rm *.aux *.log *.nav *.out *.snm *.toc *.vrb
