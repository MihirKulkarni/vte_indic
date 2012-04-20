# Makefile for project report - LATEX files
# Dept. of Comp/IT
# Sun Apr 11 20:27:45 IST 2011

name=coep_compit_report
all: $(name)

# Main report 
$(name): $(name).tex
	latex $(name)
	bibtex $(name)
	latex $(name)
	latex $(name)
	dvipdf $(name).dvi

# Remove aux files and log files
clean:
	rm *.aux
	rm *.log
	rm *.lot
	rm *.toc
	rm *.lof
	rm *.bbl
	rm *.dvi

