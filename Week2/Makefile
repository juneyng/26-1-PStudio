main : main.c function.o
	gcc -o $@ $^

function.o : function.c function.h
	gcc -c function.c

clean :
	rm -f main.exe *.o
