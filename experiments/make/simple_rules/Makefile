OBJECTS = main.c
BUILDS = example

default:
	@echo "I'm the default target"

example: ${OBJECTS}
	gcc -o example main.c

.PHONY: clean
clean:
	rm -f ${BUILDS}