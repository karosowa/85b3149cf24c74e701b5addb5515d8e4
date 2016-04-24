all: program clean

program: DTAB.o test.o
	g++ DTAB.o test.o -o program

DTAB.o: DTAB.cpp DTAB.h
	g++ -c DTAB.cpp

test.o: test.cpp DTAB.h
	g++ -c test.cpp

clean:
	rm -f *.o
	rm -f *~
