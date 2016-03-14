CC=/usr/local/intel/ClusterStudioXE_2013/impi/4.1.3.048/bin64/mpicc
CFLAGS=-Wall -O3 -lm

scatter_gather : scatter_gather.c
	$(CC) -o $@ $< ${CFLAGS}

.PHONY: clean

clean:
	rm scatter_gather
