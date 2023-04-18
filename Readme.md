# Lab 03 Parallel and Distributed Computing

To run the product of a vector and a scalar, run the following commands:
```
  mpicc -g -Wall  mpi_vector_addOpe.c -o mpi_vope.exe
  mpirun --use-hwthread-cpus --oversubscribe -np 5 ./mpi_vope.exe
```