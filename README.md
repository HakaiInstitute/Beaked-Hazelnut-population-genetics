<div align='center'>
    <a href='https://tula.org'><img height='75px' src=docs/logos/tula-logo.png /></a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href='https://hakai.org'><img height='75px' src=docs/logos/hakai-logo.png /></a>
</div>

# HakaiInstitute/Beaked-Hazelnut-population-genetics

This repository contains data files from a survey of Beaked Hazelnut population genetic diversity in British Columbia. 

```
repository reference citation
```

## Method

We used e-flora distributions and local knowledge (from farmers, outdoor recreators, hunters, and Indigenous knowledge holders) to locate potential hazelnut stands throughout BC. Leaf tissues for genetic analysis were harvested from live individuals between 2014–2015. Morphometric data, including tree height, branching density, surface leaf area, first year stem diameter, largest stem diameter, nut length, involucre length, involucre hairiness, and number of nuts per cluster were recorded for each shrub/tree at the time of collection.A total of 285 samples were collected. Samples were then prioritized for their quality (diseased or spoiled leaves disregarded) and their coverage (multiples disregarded), leaving the total number to 219 individual samples. The genomic DNA was extracted using the DNeasy Plant Mini kit (Qiagen). Genomic DNA was converted into nextRAD genotyping-by-sequencing libraries (SNPsaurus, LLC). The nextRAD libraries were sequenced on a Novaseq 6000 with two lanes of 122 bp reads (University of Oregon).

## Reports

A manuscript based on these data is currently in review:

Armstrong CG, Clemente-Carvalho RBG, Turner NJ, Wickham S, Trant A, Lemay MA. Genetic differentiation and pre-colonial Indegenous cultivation of hazelnut (Corylus cornuta) in western North America. In Review. 

## Resources

This repository contains the following data files:

1. Sample_metadata.csv - Collection metadata for all tissue samples analyzed in this study.

2. Hazelnut_SNP_genotypes.csv - A table of SNP gentypes formatted as a sample x genotype matrix
  
3. Hazelnut_Morphological_Data.csv -  Table of morphological data used to acompany the genetic results
  
4. Sanger_sequences.fasta.txt - a fasta file containing the raw rbcL and matK sequences derrived from a subset of samples in this study

5. Raw Illumina sequence data has been depositied at NCBI (BioProject ID: PRJNA1138710).
   Link to raw Illumina sequence data: https://www.ncbi.nlm.nih.gov/bioproject/1138710

See the data dictionary file for a complete description of data variables, units
and descriptions.
  
