### Instructors and contact information

- **Hervé Pagès**, Fred Hutchinson Cancer Research Center, Seattle, WA
- **Qian Liu**, Roswell Park Comprehensive Cancer Center, Buffalo, NY
- **Martin Morgan**, Roswell Park Comprehensive Cancer Center, Buffalo, NY


### Pre-requisites

- Basic knowledge of R syntax (`matrix`, `array`, `data.frame`, etc.)
- Some familiarity with manipulation of S4 objects in general
- Some familiarity with `SummarizedExperiment` objects


### Learning objectives

- Introduction to `DelayedArray` objects and related concepts (seed,
  delayed operations, realization, block-processed operations, in-memory
  vs on-disk backends, etc...)

- Use `VariantExperiment` to represent your DNA-seq data.

- Statistical analysis of variant data (VCF) using `VariantExperiment`.

- Create `SQLDataFrame` from in-memory data, text format file, and
  database tables.

- Use `SQLDataFrame` to represent and manipulate orgdb database tables.


### Workshop participation

Students will be using their laptops with internet connection, follow
the instructor to read course materials and run through the working
code chunks.


### Time outline

| Activity | Time |
|----------|------|
| DelayedArray and HDF5Array objects | 30m |
| DelayedArray and HDF5Array hands-on | 10m |
| Specialized DelayedArray backends | 10m |
| VariantExperiment | 20m |
| DelayedDataFrame | 10m |
| SQLDataFrame | 10m |
| Future directions | 5-10m |


###  _R/Bioconductor_ packages

The workshop makes use of the following packages:

```{r setup, message = FALSE}
library(DelayedArray)
library(HDF5Array)
library(pryr)
library(DelayedMatrixStats)
library(SummarizedExperiment)
library(gdsfmt)
library(SeqArray)
library(GDSArray)
library(VCFArray)
library(DelayedDataFrame)
library(SQLDataFrame)
library(VariantAnnotation)
library(org.Hs.eg.db)
library(TxDb.Hsapiens.UCSC.hg38.knownGene)
library(DBI)
#> library(VariantExperiment)
```
