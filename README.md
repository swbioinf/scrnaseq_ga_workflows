scRNAseq Processing Workflows
==============

# General recommendations

This document describes how to use some scanpy-based scRNAseq workflows on galaxy Australia. 

The aim of these workflows is to handle the routine ‘boring’ part of single cell RNAseq data processing. It will produces an ‘AnnData’ object, which can then be used as a base for downstream analysis – either within galaxy or outside of it. AnnData is a standard format used by the ‘scanpy’ python package. 

These workflows represent just one way of processing data for a ‘typical’ scRNAseq experiment – there are many other options!  

---

This document describes 3 sub-workflows for processing single cell RNAseq data with scanpy 

Load counts matrix:  

https://usegalaxy.org.au/u/s.williams/w/scrnaseq-load-counts-matrix-subworkflow   

This workflow adds a sample name, which enables multi-sample analyses 

Single cell QC:  

https://usegalaxy.org.au/u/s.williams/w/scrnaseqcellqc   

This workflow generates some basic QC plots and applies filtering 

Single cell QC to basic processing:  

https://usegalaxy.org.au/u/s.williams/w/copy-of-scanpyqcplusdraft  

This generates a UMAP, does clustering and calculates cluster marker genes. 

 

For single sample experiments, there is a streamlined workflow that runs all 3 sub-workflows all at once 

Single sample workflow:  

https://usegalaxy.org.au/u/s.williams/w/copy-of-scrnaseqcountsmatrixtoqc  

 

# Tutorials and reference 

 

For more general information about single cell RNAseq processing on galaxy; there are some excellent tutorials to be found here on the galaxy training website:  

https://training.galaxyproject.org/training-material/topics/single-cell/ 

The workflow described here is heavily influenced by this tutorial; https://training.galaxyproject.org/training-material/topics/single-cell/tutorials/scrna-scanpy-pbmc3k/tutorial.html  

 
For more general information on using galaxy: https://training.galaxyproject.org/training-material/  

 
And for more information on the principals of single cell analysis 

The Scanpy preprocessing and clustering tutorial 

https://scanpy-tutorials.readthedocs.io/en/latest/pbmc3k.html 

This page describes the scanpy code used within galaxy. Even if you ignore the code, it works through many of the plots these workflows generate.  

Ochestrating Single cell Analysis with Bioconductor https://bioconductor.org/books/release/OSCA/ 

This is an extensive book that doesn’t using galaxy or scanpy, but does describe why various analysis steps are needed. 


# How To


...


# Attributions

This doco repository based on documentation template : https://github.com/AustralianBioCommons/doc_guidelines


