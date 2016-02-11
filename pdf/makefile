all: lily

lily: main.tex
	lilypond-book --output=lily --pdf main.tex
	cd lily; pdflatex main.tex; pdflatex main.tex
	mv lily/main.pdf .

clean:
	rm -r lily
