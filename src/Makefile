all:
	gcc -Wall -g -O2 -shared -o codec.so codec.c -llua -lcrypto -fPIC

clean:
	rm -f codec.so
