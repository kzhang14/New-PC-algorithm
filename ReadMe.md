** A new PC algorithm.

2020-01-08
Add delta_L: in each round l, test in priority neighbors all l, l+1, ..., l+deltaL subsets, then from other nodes, test all l subsets.
Change data generation to allow 1-5 "big nodes", who connects to a lot of other nodes.

2020-01-13
Add accuracy measurement, using ROC and AUC. 

2020-01-23
Within each deltaL, run reversely.
Tune alpha (threshold) to find a continuous ROC.
