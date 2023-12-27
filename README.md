# Parallel_FP_Growth
TLDR: Parallelizing the FP Growth Algorithm which is used in various data mining applications.

The traditional FP-Growth algorithm often struggles with scaling up to handle large datasets efficiently. It lacks inherent support for parallel processing and distribution across multiple processors or machines. This limitation leads to slower performance and increased execution times when dealing with substantial data volumes.
Parallel FP-Growth stands as a robust solution to the challenges faced in managing extensive datasets. It offers significant improvements over traditional FP-Growth methods by enabling efficient parallelization, optimal storage usage, and enhanced communication among distributed components.

This project includes the implementation of Parallelization of this algorithm by implementing it using
- Map-Reduce Approach
- the inbuilt ```FPGrowth``` class in the ```mlib``` library.
