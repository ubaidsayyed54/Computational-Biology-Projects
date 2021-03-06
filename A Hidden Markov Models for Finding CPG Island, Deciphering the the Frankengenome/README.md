#Prediction of CpG Island:
In human genome wherever the dinucleotide CG occurs the C nucleotide is frequently chem- ically modified to a T. CpG dinucleotides are less frequently observed in the genome than would be expected from the independent probabilities of C and G. This modification is re- pressed in certain regions of the genome, such as around the promoters or start regions of many genes. These stretches of CpG dinucleotides are the regions are called CpG islands.
We can use a Hidden Markov Model to identify these CpG islands given a sequence of DNA. The HMM model has 2 hidden states: CpG-island (I) and non-CpG-island (N). The observation is sequence of DNA.

DNA sequence: TTACGCGCGCGCGATATTT
Calculate the probability that the hidden state is CpG island (I) at every position of the given DNA sequence.


#FrankenGenome Problem:
Dr. Frankenstein is trying to create a new species of bacterium by splicing together the genomes of bacteria A and B. Unfortunately, he lost all but the first two pages of his notes describing how they were spliced together. He needs your help to identify which parts of the frankengenome came from which bacterium. You are given the full frankengenome called frankengene1.fasta as well as the first two pages of notes, called trainingData1.txt and testData1.txt, which have correct labels for the first 50,000 and the next 50,000 bases of the frankengenome respectively. The label 0 indicates the base came from genome A and the label 1 indicates it came from genome B. E.g. the label 0000011111110011 indicates the first 5 bases came from genome A, the next 7 from genome B, the next 2 from genome A, and the last 2 from genome B.

Implement a classifier that assigns a label to each base of the frankengenome according to whether it came from genome A or B. You are not expected to get the labels 100% correct; you will be graded based on your classifier's accuracy relative to a simple "reference" classifier. Accuracy is measured as the fraction of genome positions given the correct label.
