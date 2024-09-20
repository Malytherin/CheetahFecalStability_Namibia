# CheetahFecalStability_Namibia
 Code and files for preprocessing and analyses of 16S fecal microbiota data from cheetahs. Fecal samples were collected fresh and analyzed for an additional 4 days to observe microbial changes in fecals exposed to the environment. 
 
 ## R Markdown Files
 1. NAM_Degradation_Preprocessing.Rmd - code for preprocessing unpaired FASTQ files (dada2,         decontam, rarefactin curve, alpha calculations, create phyloseq object files)
 2. NAM_Degradation_Analyses.Rmd - code for statistical tests and visualizations for relative abundance, alpha and beta diversity
 3. NAM_Degradation_MaAslin2_Code.Rmd - code for running differential abundance testing across samples days using MaAslin2
 
## Files for building phyloseq object
1. CCF8_featuretable_July2024.csv (feature table - ASV counts for each sample)
2. CCF8_Meta_July2024.csv (metadata for samples)
3. CCF8_taxonomy_July2024.csv (taxonomy file for mapping ASV numbers to taxonomy classifications)
4. CCFPT_2024_DNAsequences.fasta (Sequences of ASVs)
5. CCFPT_2024_tree.nwk (phylogenetic tree of DNA sequences from ASVs)
