CC=/usr/local/intel/ClusterStudioXE_2013/impi/4.1.3.048/bin64/mpicc
CFLAGS=-Wall
SRC=mpi_hello.c
EXE=mpi_hello

release : ${SRC}
	$(CC) -o ${EXE} $< ${CFLAGS} -O3

debug : ${SRC}
	$(CC) -o ${EXE}_debug $< ${CFLAGS} -g

.PHONY: clean

clean:
	rm ${EXE}
	rm ${EXE}_debug