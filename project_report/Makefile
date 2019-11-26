PAPER = report
TEX = $(wildcard *.tex)
FIGS = $(wildcard figures/*.pdf figures/*.png)

.PHONY: all clean

$(PAPER).pdf: $(TEX) $(FIGS)
	echo $(FIGS)
	pdflatex $(PAPER)

clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.fdb_latexmk *.fls *.synctex.gz
