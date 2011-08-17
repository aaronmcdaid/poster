ALL: poster.pdf poster_landscape.pdf baposter_guide.pdf

%.pdf: %.tex 
	pdflatex $< &&	pdflatex $< && pdflatex $<

clean:
	  rm -f *.aux	*.bbl	*.blg	*.log	poster.pdf poster_landscape.pdf
