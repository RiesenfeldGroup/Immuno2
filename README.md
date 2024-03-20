# Immunogenomics 2 (IMMU48900/MENG2-33330) starter code

This repository includes instructions for installing R and RStudio (below) and code to install R packages relevant to genomics analysis (below and `Immunogenomics 2 Packages Installation.Rmd`).

First, please follow the instructions on [this website](https://rstudio-education.github.io/hopr/starting.html) to install R and RStudio. You **must** use R 4.3.3. This means your operating system must be at least MacOS Big Sur (11) or higher, OR Windows 10 or 11. *(Note: even if you have a Mac with an M1 chip, please still install `R-4.3.3-x86_64.pkg`, NOT `R-4.3.3-arm64.pkg`. Students have had issues with `arm64` in the past.)*

Next, open RStudio and enter the following command into the console. It will install packages needed for using RMarkdown files.

```
install.packages(c("rmarkdown","knitr"))
```

Last, run the `Immunogenomics 2 Packages Installation.Rmd` script either by copying and pasting the script into RStudio or by downloading this repository to your local computer and running it in R. 

To confirm you have run this script correctly, enter the following command into the console. 

```
find.package("Seurat")
```

If in response to the command, R returns the directory location of the Seurat package, you should be all set. If you get an error, please review the instructions and then contact the teaching team if you still require help. 
