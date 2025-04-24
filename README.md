# Parallel_computing
Parallel computing using MPI

**Assignment 1**
The first assignment tells about basic MPI functionality, starting with a "Hello World" code.
It also contains usage of functions like MPI_Send and MPI_Recv and implementation of a basic Walkers program.


**Assignment 2 (range of computational tasks)**
i) Estimating Pi using the Monte Carlo method: Estimated the value of pi by showing communication between different processes using MPI functions.
ii) Matrix Multiplication using MPI: Multiplied two 70x70 matrices in parallel using MPI.
iii) Parallel Sorting using MPI (Odd-Even Sort): This is a comparison-based sorting method where neighboring processes communicate to sort their elements.
iv) Heat Distribution Simulation using MPI: Simulated heat distribution in a 2D space, where each process manages a portion of the grid.
v) Parallel Reduction using MPI: Performed parallel reduction - elements from different processes are combined to get a single result.
vi) Parallel Dot Product using MPI: Computed dot product by distributing the elements of the vectors among different processes.
vii) Parallel Prefix Sum (Scan) using MPI: Computed partial sums of an array distributed across processes.
viii) Parallel Matrix Transposition using MPI: The matrix is distributed among processes, and each process handles a portion of the matrix, exchanging rows and columns accordingly.


**Assignment 3**
i) DAXPY Loop Using MPI: Parallelized the DAXPY operation (X[i]=A∗X[i]+Y[i]).
ii) Calculation of π Using MPI_Bcast and MPI_Reduce: Each process(here) computes a partial sum for π. The MPI_Reduce function is used to gather and combine all partial results from different processes.
iii) Prime Number Calculation Using MPI_Recv: Implemented a master-slave model. Master Process loops through numbers from 2 to a given maximum value. It waits for requests from slave processes and sends numbers to them for testing. Slave Process send requests to the master, receive a number, test whether it is prime, and send the result back to the master.


**Assignment 4-5**
CUDA Threads:One thread sums numbers iteratively, another using formula (N=1024).
Merge Sort:Compare CPU pipelined vs. CUDA parallel merge sort on 1000 elements.
Vector Add & Profiling:Use static arrays, measure execution time, and compare theoretical vs. measured memory bandwidth.


**Assignment 6**
CUDA program to compute C[i] = sqrt(A[i]).
Run it for array sizes: 50K, 500K, 5M, and 50M.
Measure the execution time for each and visualize the results in a chart to understand performance as data size increases.
