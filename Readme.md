# Lab 03 Parallel and Distributed Computing

To run vector_add2 commands:
```
  gcc vector_add2.c -o vector2.exe
  ./vector2.exe 
```

To run mpi vector add, run the following commands:
```
  mpicc -g -Wall  mpi_vector_add2.c -o mpi_vadd.exe
  mpirun --use-hwthread-cpus --oversubscribe -np 4 ./mpi_vadd.exe
```

To run mpi vector product dot, run the following commands:
```
  mpicc -g -Wall  mpi_vector_addOps.c -o mpi_vops.exe
  mpirun --use-hwthread-cpus --oversubscribe -np 4 ./mpi_vops.exe
```

To run vector * scalar, run the following commands:
```
  mpicc -g -Wall  mpi_vector_addOpe.c -o mpi_vope.exe
  mpirun --use-hwthread-cpus --oversubscribe -np 4 ./mpi_vope.exe
```