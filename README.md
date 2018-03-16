# SEquence CApture PRocessor (SECAPR) [![downloads](https://anaconda.org/bioconda/secapr/badges/downloads.svg)](http://bioconda.github.io/recipes/secapr/README.html)

___

*We are now teaching a 1-week intensive course on target enrichment, including practical tutorials of all functionalities of the SECAPR pipeline. Check it out and apply!* http://www.forbio.uio.no/events/courses/2018/target_capture.html


## Installation instructions and documentation [click here](./documentation.ipynb)

This semi-automated pipeline aims to make the processing and analysis of sequence capture (= target enrichment) data simple and straight forward for all users. The detailed documentation and simple installation makes this pipeline accessible also for users with limited biofinformatic knowledge, while enabling user-defined processing options for the more experienced users.

We included an empirical data tutorial in the [pipeline documentation](./documentation.ipynb), which covers the processing from raw Illumina read data into multiple seqeunce alignments (MSAs) for phylogenetic analyses, including the compiling of allele sequence MSAs. This workflow can be applied to any Illumina dataset, independently of the underlying bait set and organism group.

Some functions in this pipeline are inspired by the scripts from the [Phyluce pipeline](https://github.com/faircloth-lab/phyluce) by Braint Faircloth, which is aimed at the processing of Ultraconserved Elements (UCEs). To honour some of the ingenious ideas belonging to Brant Faircloth, and the generous sharing of all is code as open-source, we ask you to cite his Phyluce pipeline (Faircloth et al. 2015) alongside with ours, when using SECAPR.  

#### References:
Faircloth BC. 2015. PHYLUCE is a software package for the analysis of conserved genomic loci. bioRxiv. doi: 10.1101/027904.
