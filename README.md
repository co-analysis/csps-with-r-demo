# csps-with-r-demo

## Purpose

This repository is to support people in 'The CSPS with R and RStudio session' on Tuesday 18 February 2020 who do not have R or RStudio installed, or are unable to install packages or download the data.

In the session we'll be following along with this document: https://co-analysis.github.io/csps-with-r/

## RStudio in the cloud

If you don't have R and RStudio installed, you can click the 'Launch Binder' button below to open RStudio in the cloud from your browser.

<!-- badges: start -->
[![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/matt-dray/csps-with-r-demo/master?urlpath=rstudio)
<!-- badges: end -->

This is not how you would normally access RStudio; this has been set up so you are able to follow along with the demonstrations in the session. 

After a period of inactivity, your instance of RStudio will shut down. Note that anything code you write won't be preserved. You will need to copy, paste and save anything you write into a file on your computer instead.

Note that you won't be able to install any packages, but the packages of the tidyverse have been installed for you. You can access them with a call to `library(tidyverse)`. The data have also been supplied in the `data/` folder.

## Folder structure

There's lots of files and folders in this repository that you don't need to worry about. You should consider the following as the main folder structure:

```
csps-with-r-demo/              # the project folder
  ├── csps-with-r-demo.Rproj   # R Project file
  ├── data/                    # read-only raw data
  |   └── csps_synth.dta       # the synthetic data set
  └── output/                  # processed data goes here
```

You can save your R script files (.R) under `csps-with-r-demo/`.
