
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: I2CFirstByte.svg
