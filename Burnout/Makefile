
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: Wheatstone1.svg Burnout1.svg Burnout2.svg
