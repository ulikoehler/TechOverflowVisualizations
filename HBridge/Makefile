
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: HBridgeDriver1.svg HBridgeDriver1.pdf HBridgeDriver2.svg HBridgeDriver2.pdf
