

BASENAME=Modelo-Dissert-DCOMP
TEXNAME=$(BASENAME).tex

all:
	pdflatex $(TEXNAME)
	bibtex $(BASENAME)
	pdflatex $(TEXNAME)
	pdflatex $(TEXNAME)


clean:
	rm -f $(BASENAME).aux
	rm -f $(BASENAME).idx
	rm -f $(BASENAME).lof
	rm -f $(BASENAME).log
	rm -f $(BASENAME).lol
	rm -f $(BASENAME).lot
	rm -f $(BASENAME).toc

	rm -f $(BASENAME).bbl
	rm -f $(BASENAME).blg
	rm -f $(BASENAME).brf





