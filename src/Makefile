CC=gcc
OBJ=mfs

all:${OBJ}
mfs:	mfs.o
	${CC} -o $@ $<
mfs.o:	mfs.c
	${CC} -c $<
clean:
	rm *.o ${OBJ}
