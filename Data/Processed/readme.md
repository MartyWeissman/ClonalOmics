# About these data

In this directory, you can find data after the preprocessing steps.  Preprocessing notebooks are found in the main Data folder.  For each dataset, there are three kinds of files, space permitting:
*Loom* files are compressed files containing gene expression (or peak height) matrices together with information about genes and cells/samples.  See the [AnnData](https://anndata.readthedocs.io/en/latest/) documentation for more on the structure of our Loom files.
*Cell metadata* files are csv-formatted "spreadsheets" containing metadata about each cell, or about each sample in the case of bulks.  This includes clonal information, TCR sequence information, donor, and more.
*Gene data* files are csv-formatted "spreadsheets" containing data about each gene.  This includes genomic information (chromosome and location), and properties of each gene's expression in the particular expression matrix, e.g. dropout frequency, etc.  Additional information includes clonality p-values.  (More explained below.
Other data include protein expression and ATACseq data.  More information to come soon.
