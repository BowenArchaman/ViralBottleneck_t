# ViralBottleneck
## Description
This package is used for estimating viral transmission bottleneck size using different methods.
The main steps to use the program are:
1. Create the transmission object
2. Calculate the transmission bottleneck size 
   
There are the links for [manual](manual_and_tutorial/ViralBottleneck_manual_0.1.0.pdf) and [tutorial](manual_and_tutorial/ViralBottleneck_Tutorial.pdf).

The test data for "ViralBottleneck" is in [test_dataset folder](test_dataset).

## Download
To install the package in R use the following commands: 
```
library(devtools)
install_github("BowenArchaman/ViralBottleneck", build_vignettes = TRUE)
library(ViralBottleneck)
```

## Requirements
- R 4.2.2
- methods
- utils
- ggplot2
- pbapply
- rmutil

