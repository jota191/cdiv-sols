
TEX = pdflatex -shell-escape -interaction=nonstopmode -file-line-error

.PHONY: all view

all : 1 2 3 4 5 10

1 : Sol01.tex 
	$(TEX) Sol01.tex


2 : Sol02.tex 
	$(TEX) Sol02.tex


3 : Sol03.tex 
	$(TEX) Sol03.tex


4 : Sol04.tex 
	$(TEX) Sol04.tex


5 : Sol05.tex 
	$(TEX) Sol05.tex

10 : Sol10.tex
	$(TEX) Sol10.tex

10 : Sol11.tex
	$(TEX) Sol11.tex

.PHONY: clean
clean:
	rm *log *aux *~ *pdf
