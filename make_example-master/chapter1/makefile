#this is a makefile example
.PHONY: clean

depen=main.o clean 
main:$(depen)
	gcc -o main main.o

main.o:main.c
	gcc -c main.c

clean:
	-rm $(depen)