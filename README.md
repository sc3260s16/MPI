# MPI Tutorials

You need to have Intel compilers in your environment 
to run these examples:

	setpkgs -a intel_cluster_studio_compiler

## Running within SLURM

SLURM has its own MPI job management command called ```srun```, which you can think of as ```mpirun```. With ```srun``` you do not need to specify the number of processes you would like to launch, SLURM just launches the program with the maximum allowed process for your job allocation (which is specified in the script that you submit to SLURM).