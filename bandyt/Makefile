CC=g++
CFLAGS=-Wall -c -fPIC -std=c++11 -O2

all: ofext.so

ofext.so: ofext.o
	$(CC) -shared -o ofext.so ofext.o 

ofext.o: ofext.cpp
	$(CC) $(CFLAGS) ofext.cpp
