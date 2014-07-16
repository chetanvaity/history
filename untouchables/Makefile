all: untouchables.dvi untouchables.pdf

untouchables.dvi: untouchables.tex
	latex untouchables
	bibtex untouchables
	latex untouchables
	latex untouchables

untouchables.pdf: untouchables.dvi
	dvipdf untouchables.dvi untouchables.pdf

clean:
	rm -f untouchables.aux untouchables.log untouchables.dvi untouchables.pdf untouchables.bbl untouchables.blg
