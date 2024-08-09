build: build_library
	gcc -o main main.c -Llib -lexample
build_library:
	gcc -c -o lib/example.o lib/example.c
	ar rcs lib/libexample.a lib/example.o
clean:
	rm -f main lib/example.o lib/libexample.a