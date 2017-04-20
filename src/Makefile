CC=gcc
OBJ=mfs

all:${OBJ}
mfs:	mfs.o
	${CC} -o $@ $<
mfs.o:	mfs.c
	${CC} -c $<
test:	mfs
	./mfs
clean:
	rm -f *.o ${OBJ}
