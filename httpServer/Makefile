CC=gcc
CFLAGS=-Wall -std=c99

#CC=i686-w64-mingw32-gcc
LN=ld

FILES=main.c extclib/extclib.o

.PHONY: default build run
default: build run

build: $(FILES)
# 	$(CC) $(CFLAGS) $(FILES) -o main
	$(CC) $(CFLAGS) $(FILES) -o main
run: main
# 	./main
	  ./main
