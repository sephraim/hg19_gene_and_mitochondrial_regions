# Gene and Mitochondial Regions (hg19)

## What is this file?

This file contains all [HGNC](http://www.genenames.org/) gene symbols and their respective gene regions based on the hg19 genome build.

## Sample snippets

### head

```
chr1  11873 14409 DDX11L1
chr1  14361 29370 WASH7P
chr1  69090 70008 OR4F5
chr1  562759  564389  LOC101928626
chr1  567704  567793  MIR6723
chr1  700244  714068  LOC100288069
```

### tail

```
chrM  10759 12136 MT-ND4
chrM  12137 12205 MT-TH
chrM  12336 14147 MT-ND5
chrM  14148 14672 MT-ND6
chrM  14673 14741 MT-TE
chrM  14746 15886 MT-CYB
```

## How was this file generated?

### Gene regions for chr1-22, chrX, and chrY

* All gene regions for chr1-22, chrX, and chrY were generated from the hg19 refFlat.txt file, which can be downloaded [here](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/database/refFlat.txt.gz).
* Gene transcripts were used to create the gene regions
* If a gene contains multiple transcripts 
  * The **lowest transcript start position** was used as the starting position
  * The **highest transcript end position** was used as the ending position

### Mitochondrial gene regions (chrM)

* All gene regions for chrM were take from the [NIH Genetics Home Reference](http://ghr.nlm.nih.gov/mitochondrial-dna/show/Genes). Each region is written explicitly.
