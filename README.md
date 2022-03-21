# GEO

## SOFT
SOFT stands for Simple Omnibus Format(mix) in Text. SOFT is a kind of format to submit data efficiently. [SOFT](https://www.ncbi.nlm.nih.gov/geo/info/soft.html)

There are actually four types of GEO SOFT file available. 

- GEO Platform (GPL):
These files describe a particular type of microarray. They are annotation files.

- GEO Sample (GSM):
Files that contain all the data from the use of a single chip. For each gene there will be multiple scores including the main one, held in the VALUE column.

- GEO Series (GSE):
Lists of GSM files that together form a single experiment. We usually see this number from papers.

- GEO Dataset (GDS)
These are curated files that hold a summarised combination of a GSE file and its GSM files. They contain normalised expression levels for each gene from each sample (i.e. just the VALUE field from the GSM file).

## Series Matrix File(s)
It is usually the normalized data. 

## SRA
Sequence Read Archive: SRA stores raw sequencing data and alignment information to enhance reproducibility and facilitate new discoveries through data analysis.

