CC=gcc
CFLAGS= -m32 -fno-stack-protector -z execstack -mpreferred-stack-boundary=2

exploit: exploit.c
	$(CC) exploit.c $(CFLAGS) -o exploit
