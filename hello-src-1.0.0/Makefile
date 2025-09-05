CC=gcc
CFLAGS=-O2

all: hello

hello: hello.c
	$(CC) $(CFLAGS) -o hello hello.c

install: hello
	mkdir -p $(PREFIX)/
	cp hello $(PREFIX)/

