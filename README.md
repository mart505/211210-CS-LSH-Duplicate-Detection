# 211210-CS-LSH-Duplicate-Detection

This repository includes the code for a duplicate produt detection method which uses LSH to increase scalability.

Everything can be run from the file 

Underneath all functions, one finds the code to be run, including the following hyperparameters:

numhashfunc = 200   # min hashing
bands = 100         # lsh
num_resampling = 10 

epsilonCandidates = [0.5,0.6,0.7] # values of epsilon used in cross validation
weightsCandidates = [[1,0]]       # values of weights for KVpair similarity (not used in final version)
