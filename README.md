# phylogenetic-analysis-predicted-proteins
## Problem statement
Prepare an apptainer definition file to be used to build an apptainer sif image that holds all the software and scripts you need to make your project reproducible.
get locust genome DNA from NCBI, link https://www.ncbi.nlm.nih.gov/data-hub/genome/GCA_000516895.1/Links to an external site.
pull out the assembled contigs of lengths >= 80,000 nucleotides
use wgsim to generate simulated reads (use a range of parameters to explore)
assemble those reads with soapdenovo
evaluate your assembly results; interpret the results for different parameter sets (long versus short reads; single-end versus paired-end; depth of sequencing; effect of error rates)
Annotate your original contig using the Augustus (web-based) gene prediction tool
Evaluate the predicted gene models using blastp against known proteins (are there any good matches?)
Take 3 promising candidates and run a phylogenetic analysis on the predicted proteins; interpret your results

## Experiments
Extracted the contigs using seqkit and then formed assembly using SoapDenevo. Then utilised Augustus to generate related protein sequence and with help of blastp identified most matching protein sequence and formed a phylogenetic tree with MEGA software.

## Observation
Based on results of assembly:
Analyzing the parameters of the tools used to maximize our understanding of the tools and apply to the different requirements of analysis of genomes.
Based on Results of phylogenic tree:
It helps in understanding how different protein sequence are related to each other.
