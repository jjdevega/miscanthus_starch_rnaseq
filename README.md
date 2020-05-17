# Transcriptional differences between Miscanthus hybrids with contrasting starch and sucrose concentrations and biomass production

This repository contains the code of the RNA-seq analysis of our paper on transcriptional differences between Miscanthus hybrids with contrasting starch and sucrose concentrations and biomass production. A preprint of the paper is available in X.

**The R notebook (rnaseq_analysis.Rmd) is fully run here with all the figures:
https://joseja.github.io/miscanthus_starch_rnaseq/

# Repository contents
The R markdown raw file is rnaseq_analysis.Rmd in the main folder, that is all you need together with the files in the inputs folder: The counts are loaded into the txi_import.R object, so the importing step does not need to be run each time; and the pheno.txt file contains the libraries metadata. All the other files are results and are generated during the execution of the R notebook.

# Functional annotation of the Miscanthus sinensis genome
The folder Msin_b2go contains a functional annotation of the M. sinensis genome v.7.1 available in phytozome using Blast2GO. The folder contains the GO terms in the format for topGO that the analysis uses.
