# MFD_sample_check
This repo contains a simple R code which checks Microflora danica scanned ID barcodes and tube barcodes match in plate possition before extraction can be made


# TO run the code
    1. Fork this repo
    2. Insert ID_files and plate files in the given folders
    3. Open the Microflora_Danica_barcode_sample_check.Rmd (Rmarkdown file) in Rstudio and run the code. 
        OPS. install packages to run the code.  
          library(tidyverse)
          library(purrr)
          library(ggplot2)
          library(patchwork)
          library(openxlsx)
