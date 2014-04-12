read_mapping_to_pangenome_matrix
=================================

A Python script to automate the mapping of short reads to draft genomes. The output is a gene x draft genome matrix providing the number of reads which map to each annotated gene based on the format of the pangenome matrix output by the software package "Get_Homologues."

Dependencies:

-bowtie2

-samtools

-genomeCoverageBed

-Pandas (Python module)



Data Input: 
pangenome_matrix.csv (get_homologues output) 

Get_Homologues Software:  <http://www.ncbi.nlm.nih.gov/pubmed/24096415>
