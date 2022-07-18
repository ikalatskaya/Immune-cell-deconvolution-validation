# Immune Cell Deconvolution validation
## Introduction
Computational immune cell deconvolution methods utilizing gene expression profiling to estimate immune cells in bulk tissues and blood are an appealing alternative to flow cytometry.

## Goals
The main focus of this study is a comprehensive comparison between immune cell deconvolution signatures generated by xCell and Cibersort and corresponding flow cytometry data. 

## Data
Gene expression and flow cytometry data from the publicly available rheumatoid arthritis GSE93777 dataset were used for validation of CIBERSORT and xCell immune cell deconvolution methods. All GSE93777 samples were used in the validation (rheumatoid arthritis patients with or without drug treatment and healthy volunteers). Treated rheumatoid arthritis patients received either methotrexate, infliximab, or tocilizumab in roughly equal parts.
CIBERSORT and xCell deconvolution cell signatures were matched to corresponding/related immune cell subtypes assessed by flow cytometry. 

## Methods

## Output
We have designed the Rshiny app for a comprehensive validation of two most popular deconvolution methods xCell and CIBERSORT on publicly available data.
The app could be found here: 
https://minijen.shinyapps.io/Immune_Cell_Deconvolution_Validation/
