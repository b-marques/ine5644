all:
	rm build -r; mkdir build; pdflatex -output-dir=build main.tex; bibtex build/main.aux; pdflatex -output-dir=build main.tex; pdflatex -output-dir=build main.tex; cp build/main.pdf .; rm build -r