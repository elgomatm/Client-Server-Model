#elgomatim on 12/22/22
#makefile for hello.c

CC=gcc
CFLAGS = -g -Wall

all: client


client: client.c
	$(CC) $(CFLAGS) -o client client.c

clean:
	rm client
