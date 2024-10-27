TEX_NAME=main.tex
PDF_NAME=main.pdf

.PHONY: $(PDF_NAME) all clean

all : $(PDF_NAME)

$(PDF_NAME): $(TEX_NAME)
	latexmk -pdf -pdflatex="pdflatex -interaction=nonstopmode" -use-make $(TEX_NAME)

clean:
	latexmk -CA
