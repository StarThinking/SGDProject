PAPER = report
TEX = $(wildcard *.tex)
FIGS = $(wildcard figures/*.pdf figures/*.png)

.PHONY: all clean

$(PAPER).pdf: $(TEX) $(BIB) $(FIGS)
	echo $(FIGS)
	pdflatex $(PAPER)

clean:
	rm -f *.pdf *.aux *.bbl *.blg *.log *.out 


