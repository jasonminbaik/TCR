# Background:
# T cells represent a crucial component of the adaptive immune system and are thought to mediate the anti-tumoral immunity. 
# Antigen-specific recognition is realized via T cell receptor (TCR), which is the product of somatic V(D)J gene 
# recombination, plus some random addition/subtraction of nucleotides at recombination junctions. Next-generation 
# sequencing of TCR is used as a platform to profile the TCR repertoire. The distribution of TCR data based on single-cell 
# RNA sequencing typically follows some unknown distribution with inflation in the low abundance, which might occur due to 
# technical noise. 

# Goal: 
# We aim to find a cut-off value to filter the low abundance data and keep the enriched data while controlling type I error 
# via false discovery rate. We considered different inflated mixtures of distributions (inflated discrete mixtures, and 
# inflated continuous mixtures) to model the abundance of clones in the TCR repertoire to account for the excess ones 
# in abundance and compared the cut-offs. 

# We proposed a data-dependent procedure to select the best candidate mixture distribution and searched for the optimal 
cut-off. Both simulated and real data sets are used to illustrate the method.
