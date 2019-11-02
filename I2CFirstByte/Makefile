
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: I2CFirstByte.svg I2CAddressExample.svg I2CAddressNoConflict.svg
