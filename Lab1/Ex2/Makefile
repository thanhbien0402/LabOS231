hello.o: hello.c
	gcc -c -o hello.o hello.c

main.o: main.c
	gcc -c -o main.o main.c
myapp: hello.o main.o
	gcc -o myapp hello.o main.o
clean:
	rm *.o
all: myapp

