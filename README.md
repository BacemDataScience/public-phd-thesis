Variation-aware algorithms for cancer genome analysis
-------------------------------------
Eric T Dawson  
Submitted: September 27, 2019

## Overview
This repository contains the publicly-available versions of my PhD
thesis text and analyses. An overview of the PDF is laid out below.

All code used in my analyses should be public (though some only by request). 
If you cannot find it,
please reach out to me on twitter at @erictdawson.

## Document Structure
The following section describes the structure and contents of the chapters in
the text.

### Introduction
Chapter 1 provides an introduction to the cancer genome. This begins with a review
of the human genome and the types of variants. Mutational catalogs are discussed in
detail, as are the types of mutations known to drive cancer. Strucutural variants are covered
in slightly more detail than the other types of mutations. Background on variation graphs and
basic concepts in pangenomes, metagenomics, and mixtures of genomes follows.
The Chernobyl disaster, sporadic thyroid cancer and radiation's effects on the genome complete this
chapter.

### Genomic characterization of radiation-associated papillary thyroid carcinoma
Describes a cloud-based analysis of 300+ thyroid carcinoma tumors and matched normal tissue or normal blood from the Chernobyl Tissue Bank.

### Structural variation in variation graphs
Describes representation and incorporation of structural variants into variation graphs.
Demonstrates variant genotyping using graphs and discusses methods for SV detection,
breakpoint refinement, and other analyses relevant to cancer.

### Further algorithms for examining genetic heterogeneity
Describes a MinHash-based toolkit for viral coinfection analysis and further
possible applications of such lightweight algorithms.

## License / Copyright
Code and analyses in this repo are licensed individually.
The text itself may be cited based on this repo.

```
@phdthesis{Dawson2019,
    title={Variation-aware algorithms for cancer genome analysis},
    author={Eric T. Dawson},
    school={University of Cambridge},
    year={2019},
    month={September},
    note={Submitted, not yet reviewed.}
}
```
