#Brett Emory
#Makefile for lab2

Target: lab2

#Final Executable
lab2: shellA.o
	gcc shellA.o -o lab2

#compile source file
shellA.o: shellA.c
	gcc -c shellA.c

#create the zip file
lab2.zip: Makefile shellA.c
	zip lab2.zip Makefile shellA.c

#clean up
clean:
	rm -f lab2 shellA.o lab2.zip
