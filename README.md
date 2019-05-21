# Szvetecz et al., PLOS Computational Biology 2019

This repository contains code used for quality control and data analysis presented in: 

> **Szvetecz S, Rasoul B, Jahan N, Enke RA. Combining RNA-Sequencing Data Across Studies to Characterize Gene Expression During Development of the Chicken Retina. PLOS Computational Biology 2019 (in prep).**

----

## Data availability

Data is available in NCBI GEO under the accession numbers [GSE89541](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE89541) and [GSE65938](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi).

## Software used

| Software | Version | URL | 
| --- | --- | --- |
| Concatenate Multiple Files | - | https://wiki.cyverse.org/wiki/display/DEapps/Concatenate+Multiple+Files |
| FastQC | 0.11.5 | http://www.bioinformatics.babraham.ac.uk/projects/fastqc/ |
| HISAT2-index-align | 2.1 | https://ccb.jhu.edu/software/hisat2/index.shtml |
| MultiQC | 1.7 | https://multiqc.info|
| featureCounts | 1.6.0  | http://bioinf.wehi.edu.au/featureCounts/ |
| edgeR | 3.9  | https://bioconductor.org/packages/release/bioc/html/edgeR.html |




## Data analysis walkthroughs & code

Walkthroughs and code used for all of the quality assessment and data analysis steps are available in each of the below links.

1. [Combining multiple FASTQ files/sample into a single file](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/sequence%20prep%20%26%20QC)
2. [Quality assessment of sequencing reads with FastQC](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/sequence%20prep%20%26%20QC)
3. [HISAT2 alignment of sequencing reads](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/sequence%20prep%20%26%20QC)
4. [Quality Assessment and alignment summary aggregate reports with MultiQC](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/sequence%20prep%20%26%20QC)
5. [Differential expression analysis of RNA-seq data using EdgeR](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/normalization%20%26%20plots)
6. [Generation of Gene Count, MDS, and Heatmap plots ](https://github.com/enkera/Szvetecz_PLOS_CB_2019/blob/master/code%20%26%20walkthroughs/normalization%20%26%20plots)
