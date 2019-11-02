
%.pdf: %.tex
	pdflatex $<

%.svg: %.pdf
	pdf2svg $< $@

all: Node.svg NodeWithBorder.svg NodeWithBlueBorder.svg NodeWithDashedBorder.svg BorderThickness.svg