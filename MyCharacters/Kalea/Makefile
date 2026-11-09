PAPER=Kalea

pdf:
	pdflatex -interaction=nonstopmode -halt-on-error $(PAPER)
	pdflatex -interaction=nonstopmode -halt-on-error $(PAPER)

clean:
	-del $(PAPER).aux
	-del $(PAPER).log
	-del $(PAPER).out
	-del $(PAPER).toc
	-del $(PAPER).fls
	-del $(PAPER).fdb_latexmk