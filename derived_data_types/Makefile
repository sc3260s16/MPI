CC=/usr/local/intel/ClusterStudioXE_2013/impi/4.1.3.048/bin64/mpicc
CFLAGS=-Wall -O3

student : student.c
	$(CC) -o $@ $< ${CFLAGS}

.PHONY: clean

clean:
	rm student