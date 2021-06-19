.PHONY: all clean

all:
	latexmk -pdf cv
	mv -f cv.pdf ../dl/mricher.pdf


clean:
	latexmk -C cv
	rm -f cv.bbl
