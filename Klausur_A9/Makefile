all: Aufgabe9.c helper
	gcc-10 Aufgabe9.c helper.o -o Aufgabe9 `pkg-config --cflags gtk+-3.0` `pkg-config --libs gtk+-3.0`

helper: helper.c
	gcc-10 helper.c -c

clean: 
	rm Aufgabe9 helper.o
