all: clean
	gcc -fPIC -Iinclude -c ./src/runcmd.c
	mkdir lib
	gcc --shared runcmd.o -o lib/libruncmd.so

clean:
	rm -rf lib
