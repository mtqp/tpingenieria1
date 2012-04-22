SOURCES=Informe.tex
OBJS= ./*

all: Informe

Informe: $(SOURCES) $(OBJS)
	pdflatex $^
	pdflatex $^
	mv -f *.out *.aux *.log	./logs
	clear; echo 'PDF COMPILADO!'
        
clean:
	rm -f ./logs/*
	rm -f Informe.pdf
	
new: clean all
	
