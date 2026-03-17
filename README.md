# Overview of code used in McCullough et al. 2025

This repository serves to publish code overviews and notes for the bioinformatic steps taken in McCullough et al. (in review) "Phylogenomics of a genus of ‘Great Speciators’ reveals rampant incomplete lineage sorting, gene flow, and mitochondrial discordance in island systems". 

The link to this study is here: https://academic.oup.com/sysbio/advance-article-abstract/doi/10.1093/sysbio/syaf075/8293216

The Dryad link is here: https://datadryad.org/dataset/doi:10.5061/dryad.cfxpnvxg8 

The Zenodo link is here: https://zenodo.org/records/18939768

I have also included the supplemental tables (Appendix_1.xlsx), as well as supplemental figures and discussion (Appendix_2.pdf). 

This study extracted four types of molecular markers from moderate coverage (20X) whole genomes: Ultraconserved Elements (UCEs), benckmarking universal single copy orthologous loci (BUSCOs), Single Nucleotide Polymorphisms (SNPs), and mitochondrial genomes (mtDNA). 

<img width="719" height="546" alt="bioinformatic-workflow-figure" src="https://github.com/user-attachments/assets/384a0e19-99d5-4149-9cef-d36f41840a8a" />

Approximately half of DNA samples were derived from clippings of toepads of museum study skins. Many of the notes in this repository discusses the steps taken to ameliorate issues with these historical samples. Because the bioinformatic steps for analyzing data were performed across a mix of high performance computing clusters and piecemealed across different sample subsets, I've included summaries of the code with notes instead.  

There are 5 different summary files in this repository: 
1. RawReads-to-bams.txt: processing raw read data to producing the final bam files
2. UCE-overview.txt: to be added 
3. BUSCO.txt: masking fastas, running BUSCO on reference, using coordinates to pull other samples, then filtering and analyses (iqtree, astral, site and gene concordance factors). 
4. SNPs.txt: calling SNPs with UnifiedGenotyper, filtering, and analyses (phylogenetic estimation, Dsuite plotting, and heterozygosity). 
5. MtDNA.txt: Extracting mitochondrial DNA from cleaned reads files and ML analysis in IQtree.   

