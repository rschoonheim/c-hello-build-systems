build:
	gcc -c -o lib.o lib.c
	ar rcs liblib.a lib.o
build_executable:
	gcc -o main main.c -L. -llib
clean:
	rm -f main lib.o liblib.a