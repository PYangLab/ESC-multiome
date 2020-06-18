## Multi-omic profiling reveals dynamics of the phased progression of pluripotency

#### Description
This Repo is to host the multi-omic data generated for the study Yang et al. (2015) Cell Systems 8(5):427-445.e10. [fulltext](https://www.sciencedirect.com/science/article/pii/S2405471219301152).

It contains four matrices including phosphoproteome (`ESC.phos`), transcriptome (`ESC.mRNA`), proteome (`ESC.prot`), and epigenome (`ESC.epi`).

#### Usage
Download the data `ESC_multiome.rda` and use the following to access the data:

```r
load("ESC_multiome.rda")

# check the dimension
dim(ESC.phos)

# print the top 10 rows
ESC.phos[1:10,]
```
