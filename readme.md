Misc datsets
===========

A respository of miscellaneous datasets for experimentation and other purposes,
including:

* 'big' simulation dataset from phoenix and nonmem

* untidy data

* various raw outputs that may be good to have for testing parsers etc.


Files:

* nmsimtable_csv is a snippet for what the code for a nonmem simulation table with NSUB > 1 looks like with the csv output type specified via `FORMAT=,` in the $TABLE statment

* nonmem_sim_small.vpc - small snippet of multiple sim tables
* nonmem_sim.vpc - ~20 mb uncompressed with 100 simulations
* nonmem_sim_big - ~120 mb, simply 6 copies of nonmem_sim
* bigconc.csv - ~40 mb multiple copies of sd_oral_richpk