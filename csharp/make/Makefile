TARGET=icpp1-01-uvod.pdf icpp1-02-objektove-typy.pdf icpp1-03-dedicnost-polymorfizmus.pdf icpp1-04-vyjimky-jmenne-prostory.pdf icpp1-05-sablony.pdf icpp1-06-datove-proudy.pdf icpp1-07-pretezovani-operatoru-stl.pdf icpp1-08-kontejnery.pdf icpp1-09-iteratory.pdf icpp1-10-algoritmy.pdf

all: $(TARGET)


clean:
	rm -rf *.aux *.log *.nav *.out *.snm *.toc *.eps *.vrb *.data *~ $(TARGET)


%.pdf: %.tex
	cd ..; pdflatex -output-directory make ./make/$*.tex > /dev/null
	cd ..; pdflatex -output-directory make ./make/$*.tex > /dev/null
	rm -rf *.aux *.log *.nav *.out *.snm *.toc *.eps *.vrb *.data *~
