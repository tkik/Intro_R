Introduction to R
========================================================
author: Reka Toth
date: 20 February, 2023
autosize: true

Short intoduction
========================================================
left: 65%

## Studies
  - MSc. in Molecular Biology (Eotvos Lorand University, Hungary)
  - PhD in Health Sciences (University of Debrecen, Hungary)
  - BSc in Software Engineering (University of Debrecen, Hungary)

## Current workplace
  - Postdoc in Computational Epigenomics group / Cancer Epigenomics (Plass, DKFZ), Molecular Thoracic Oncology (Sotillo, DKFZ)

## Research area
  - Integrative analysis of cancer epigenomics/genomics
  - Cell-of-origin in solid cancers

## Github/twitter </newline>
  <http://github.com/tkik>, <http://github.com/CompEpigen><br>
  <http://twitter.com/rn_toth><br>
***
![R_like](R_like.jpg)
<small><https://github.com/allisonhorst/stats-illustrations></small>

Main topics included
========================================================
left: 70%
### General R introduction
  - R basic variable types
  - if, for, while
  - apply, lapply, tapply
  - writing functions
  - installing packages

### Data exploration
  - data cleaning
  - plotting/ggplot

### Statistics
  - Basic statistics for data exploration

### S4 classes
- working with genomic data `GRanges` - `rtracklayer` - `Gviz`
- data from public resources

***

### Reproducible research
  - git
  - workflowr
  - Rmarkdown


General introduction
========================================================

# Starting R
  - command line (Mac/Linux)
  - R-Gui
  - Rstudio
  - other IDEs

# What is R?
  - Programming language and <b>free</b> software for statistical computing
  - R is an interpreted language, no compiling required
  - Object oriented
  - Functional language (procedural)
  - non-declarative

Data types in R
========================================================

## Primitive types

  - Numeric
  - Integer
  - Character (string)
  - logical
  - Complex

##  Simple types (S3 classes)

  - factors (1d)
  - date
  - vector (1d)
  - list
  - matrix, array (2d, nd)
  - data.frame (2d)


## S4 classes

Data types in R - Practice
========================================================

-- see R_data_types.Rmd

Variable names in R
========================================================

Variable naming conventions:

- do not overwrite keywords! Don't name your variable e.g. TRUE, vector, list, etc. Use the free names.
- variable names are case sensitive
- use ".",  "_" or uppercase letters as a separator. Try to be consistent in your codes.
- create meaningful, but not too long names!
