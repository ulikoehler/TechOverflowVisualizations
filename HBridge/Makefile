
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: HBridge.svg HBridge.pdf
