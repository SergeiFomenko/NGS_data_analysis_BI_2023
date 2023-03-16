## Homework №1
### 1. GC composition.
Using the FASTQ file, determine the average GC composition of reeds and its distribution. The GC composition distribution is a graph on which GC composition is plotted along the x-axis and its frequency along the y-axis, i.e. the number of reeds with the corresponding composition.
To improve the results, the following was added to the program:
Ignore nucleotides with poor quality 
Do not consider riads with few good nucleotides (estimated by the expected number of errors per riad). 2.

### 2. Quality distribution.
Using FASTQ file plot the distribution of error probability depending on the nucleotide position.

### 3. Verification of results
Run the fastqc program on the input data and check the results against yours. 

### 4.* k-measure spectrum (can be done instead of one of the first two tasks)
Sometimes spectra of k-mers (nucleotide sequences of length k) are plotted to analyze the input rids. For a relatively small k (from 2 to 8), count how many times each possible k-measure occurs in the rids. The result can be represented as a graph.
