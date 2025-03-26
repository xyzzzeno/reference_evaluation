# Evaluation of DNA barcoding reference databases for marine species in the Western and Central Pacific Ocean 
This GitHub page contains R script used for the paper "Evaluation of DNA barcoding reference databases for marine species in the Western and Central Pacific Ocean"

## Background
DNA barcoding is a widely used tool for species identification, with its reliability heavily dependent on reference databases. While the quality of these databases has long been debated, a critical knowledge gap remains in their comprehensive evaluation and comparison at regional scales. Marine metazoan species in the Western and Central Pacific Ocean (WCPO), a region characterized by high biodiversity and limited sequencing efforts, are an example of this gap. 
## Purpose of this study
This study developed a systematic workflow to assess mitochondrial cytochrome c oxidase subunit I (COI) barcode coverage and sequence quality in two commonly used reference databases for DNA barcoding: the nucleotide reference database from the National Center for Biotechnology Information (NCBI); and from the Barcode of Life Data System (BOLD). Comparative analyses across marine phyla and WCPO regions identified significant barcode gaps and quality problems, providing insights to guide future barcoding efforts. 

## Description of files
**Species Checklist** contains script for record retrival from Ocean Biosiversity Information System (OBIS) for metazoan species in different regions of WCPO.
**Barcode Coverage** contains script for barcode coverage test and visualization for WCPO metazoan species.
**Basic Evaluations** contains script for sequence count, sequence lengths check, ambiguous nucleotide check, taxonomic information check, and representation check for WCPO metazoan species.
**Barcoding Gap tSNE** contains script for calculating barcoding gap and tSNE clustering for the randomly selected 100 species.
