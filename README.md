The pipeline herein was developed to study the expression of genes and transposable elements (TE) for the study : 
Transposable element expression with variation in sex chromosome number supports a toxic Y effect on human longevity
Jordan Teoli, Miriam Merenciano, Marie Fablet, Anamaria Necsulea, Daniel Siqueira-de-Oliveira, Alessandro Brandulas-Cammarata, Audrey Labalme, Hervé Lejeune, Jean-François Lemaitre, François Gueyffier, Damien Sanlaville, Claire Bardel, Cristina Vieira, Gabriel AB Marais, Ingrid Plotton
bioRxiv 2023.08.03.550779; doi: https://doi.org/10.1101/2023.08.03.550779
https://www.biorxiv.org/content/10.1101/2023.08.03.550779v5. 

It gives gene count and TE count files from FASTQ files (paired-end RNAseq data, compatible with non-stranded or reverse stranded data). 
It uses :
- FASTQC and trimmomatic tools (Bolger, Lohse, and Usadel 2014) for data quality control
- Then kallisto tool (Bray et al. 2016) to generate gene count files or TEcount from TEtools (Lerat et al. 2016) to generate TE count files.

When necessary, see https://pachterlab.github.io/kallisto/starting.html for a kallisto tutorial and https://github.com/l-modolo/TEtools for details concerning the use of TEcount and the generation of rosetta file.
