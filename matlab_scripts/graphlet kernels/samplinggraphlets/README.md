# Description

- gestkernelK.m - compute a kernel based on sampling size-K graphlets
- gestkernelK.m needs a parameter specifying the sample size. This can be computed via the script samplesize.m and depends on two probabilities epsilon and delta, and the number of equivalence classes of graphlets. This number is equal to 4 for K=3, 11 for K=4 and 34 for K=5.

If the parameter equals -1, there is no sampling, it computes exact distributions (but takes forever).
