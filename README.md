# 211210-CS-LSH-Duplicate-Detection

This repository includes the code file for a duplicate product detection method using agglomerative clusterig and LSH to increase scalability.

Everything can be run from the file "211210 CS LSH Duplicate Detection". One needs to change the file location of the data, in line 21. 

Underneath all functions, one finds the code that executes the programme. Here, one can tweak the following hyperparameters:

numhashfunc = 200   # min hashing
bands = 100         # lsh
num_resampling = 10 

epsilonCandidates = [0.5,0.6,0.7] # values of epsilon used in cross validation
weightsCandidates = [[1,0]]       # values of weights for KVpair similarity (not used in final version)

Kind regards,

Martijn Korf
