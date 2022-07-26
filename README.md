# K-means-Clustering_OpenMp_Parallel Processing
is a method of vector quantization that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid ), serving as a prototype of the cluster

## How to run 
   1-you must have a virtual machine
   
   2-to compile code : gcc -fopenmp __FILENAME.c__
   
   3-to set number of threads : export OMP_NUM_THREADS= __Any__  __Number__ 
   
   4-to run :  ./a.out 


## Requirements:
   1-Number of data points(which point are in 2 dimension (X,Y) )
   
   2-file to read point
   
   3-Number of Clusters and for first time  i Initiate 2 random numbers(X,Y) for each cluster  (assume number of clusters equal number of threads)
   
   4-using mean square error to calculate distance
   
   
  
## See Also:

  * [Sum-of-Convergent-Series Using MPI](https://github.com/MarwanaMostafa/Parallel-Processing-Sum-of-Convergent-Series-MPI)

  * [Histogram Usin MPI and OPENMP](https://github.com/MarwanaMostafa/Parallel-Processing_Histogram_MPI-and-OPENMP)

  * [Divide Data by standard function Using MPI](https://github.com/MarwanaMostafa/Parallel-Processing-Sum-of-Convergent-Series-MPI/tree/main/Divide%20Data%20By%20Standard%20Function)




