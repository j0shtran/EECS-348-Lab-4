CC=gcc

CFLAGS= -c -Wall

all: prog
	./prog

prog: main.c isOdd.h isOdd.c
	$(CC) main.c isOdd.h isOdd.c -o prog

main.o: main.c
	$(CC) $(CFLAGS) main.c

isOdd.o: isOdd.h isOdd.c
	$(CC) $(CFLAGS) isOdd.h isOdd.c


clean: 
	rm -rf *.o
