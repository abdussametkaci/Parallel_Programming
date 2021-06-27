# Parallel_Programming
compile ->  mpicc file.c -o file.x

run -> mpirun -oversubscribe -np 4 ./file.x 

OR

exec -> mpiexec -oversubscribe -np 4 ./file.x 
