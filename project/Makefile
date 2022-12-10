all: main.pdf

main.pdf: main.tex sources.bib
	pdflatex main.tex
	biber main
	pdflatex main.tex

clean:
	rm -f *.aux *.log *.pdf *.bbl *.blg *.bcf *.run.xml *.out *.toc