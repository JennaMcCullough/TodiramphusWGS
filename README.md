# Overview of code used in McCullough et al. (in review) 

This repository serves to publish code overviews and notes for the bioinformatic steps taken in McCullough et al. (in review) "Phylogenomics of a genus of ‘Great Speciators’ reveals rampant incomplete lineage sorting, gene flow, and mitochondrial discordance in island systems". 

The link to this study is here: 

The Dryad link is here:

The Zenodo link is here: 

Because the bioinformatic steps for analyzing data were performed across a mix of high performance computing clusters and piecemealed across different sample subsets, I thought it would be better to publish general summaries of the code with notes instead. See bioinformatic-workflow-figure.png for a visual representation of this workflow. 

There are X different summary files in this repository: 
1. RawReads-to-bams.txt: processing raw read data to producing the final bam files
2. UCE-overview.txt: to be added 
3. BUSCO-overview.txt: masking fastas, running BUSCO on reference, using coordinates to pull other samples, then filtering and analyses (iqtree, astral, site and gene concordance factors). 
4. SNPs.txt: calling SNPs with UnifiedGenotyper, filtering, and analyses (phylogenetic estimation, Dsuite plotting, and heterozygosity). 
5. MtDNA-overview.txt 

