# Parallel-prefix-using-OpenMP

This code is implementing efficient C++/OpenMP parallel prefix function omp_scan. We make two assumptions: first, the number of input elements is much larger than the number of available processors, second, the number of available processors is relatively small (as in the case of e.g. compute nodes in CCR).
