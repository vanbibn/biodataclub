# March 2019: Automate your pathway enrichment analysis with R
## Presenter: [Paul Stewart](mailto:paul.stewart@moffitt.org)
### Meeting location
Date/time: Friday, March 15th @ 2pm

Location: [Moffitt Stabile Research Building (SRB)](https://goo.gl/maps/o6j3rtTuxCB2), David Murphey Conference Room (1st floor)

### Meeting details
Pathway enrichment analysis is a [common computational method](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002375) for deriving biological meaning from large lists of genes. We will begin with a gentle introduction to the mathematical concepts used in pathway enrichment analysis. Next, we will discuss some practical considerations and the interpretation of results. Finally, we will use the R programming language to build a simple, reproducible pathway enrichment pipeline that can be used in your research.

### Meeting prerequisites
* A laptop with an internet connection.
* Current versions of [R](https://cloud.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/).
    * You will need to install the [enrichR](https://cran.r-project.org/web/packages/enrichR/vignettes/enrichR.html) R package. To do this, first install R and RStudio. Next, open RStudio and find the "Console" window. In this window, type the command: `install.packages('enrichR')` and press enter. You might be prompted for a server to download from. They all contain the same libraries, so just pick one located in the United States.
* [Download the sample data](https://raw.githubusercontent.com/pstew/biodataclub/master/meetings/march_2019/sample_data.txt). In most browsers, you can right click on this link and choose "Save As..." to save it to your hard drive.
* Familiarity with R or any level experience with another programming language is a plus but not required. If you have never programmed before, then you might want to take a look at the first few sections in [this tutorial](https://www.cyclismo.org/tutorial/R/) before the meeting.

### Meeting materials
* [Meeting slides](biodata_2019-03-14.pdf)
* [Meeting code](march_2019_R_code.R)
* [Meeting RData](march2019_R_data.RData)
