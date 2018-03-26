TARGET = gwemopt

all: draft
	
draft:
	pdflatex -interaction=nonstopmode  $(TARGET)
	bibtex $(TARGET)
	pdflatex -interaction=nonstopmode  $(TARGET)
	pdflatex -interaction=nonstopmode  $(TARGET)

clean:
	/usr/bin/env rm -f *.dvi *.log *.aux *.bbl *.blg *.toc *.bak *~ $(TARGET)Notes.bib
