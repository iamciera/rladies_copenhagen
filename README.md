<div style="text-align:center"><img src ="https://github.com/iamciera/SOMexample/blob/gh-pages/html/example.jpg?raw=true" width="25%" height="25%"/></div>

# From scientist to data scientist + Level-up your clustering with shape analysis

*Written by: Ciera Martinez*

## Summary

1. From scientist to data scientist (My path to data science: A love story)

2. Two part tutorial:
    - The data science of shape using `Momocs`
    - How to fully explore your clustering results using `ggplot` and `kohonen` 

## Requirements
You will need: Rstudio installed. 

Additional packages we will be using: `tidyverse`, `ggplot2`, `kohonen`, `momocs`, `factoextra`, `naniar`, `RCurl`, `cowplot`, `cowplot`.

You can install them all with this code:

```
install.packages("kohonen")
install.packages("factoextra")
install.package("naniar")
install.packages("RCurl")
install.packages("cowplot")
install.packages("tidyverse")
install.packages("kohonen")
install.packages("cowplot")
```

## Links to website display

[part 1](Copenhagen_Raldies_part1.html): The data science of shape using `Momocs`

[part 2](html/SOM_RNAseq_tutorial_part2a_SOM.html): Running PCA and SOM


Running Code
-------------

To run examples, please download all files from [Github Repository page](https://github.com/iamciera/rladies_copenhagen) and keep files in the same folders they were downloaded in. Open .Rmd files in Rstudio and set working directory to directory in which code was opened in `.r`. (Session > Set Working Directory > To Source File Location)

**New to Github?**: There is a green button that says "clone or download", there is a "download" zip file option here.

Directory Structure of Repository
---------------------

data: Data need to run tutorials. Including output, input, and required data for further analysis after running SOMs.

pdf: Knitted output PDFs from the .Rmd files.

html: knitted output html from .Rmd files.

r: Rmd R markdown files with all original code. Please set working directory to this directory to run all code.