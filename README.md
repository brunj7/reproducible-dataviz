# LTER-ASM18 workshop -  Reproducible Data Visualization using Rmarkdown and ggplot2

Participants will use of Rmarkdown and ggplot2 to create document integrating R code, documentation and data visualization in compelling documents. The first half of the session will be focusing on an introduction to Rmarkdown and how this format can be used to make data processing and analysis more reproducible by combining, documentation and executable code chunks into one document, that can be rendered in different formats (PDF, html, …) to be shared. In the second half of this workshop, participants will take a deeper look into data visualization and how ggplot’s grammar of graphics approach can be used to conduct powerful data exploration and analysis visualizations. Basic knowledge of the R programming language recommended.

### Workshop

<p><img  src="https://lternet.edu/wp-content/uploads/2018/02/LTER-network-horizontal.png" width="250px" align="right" /></p>

This training will be held on Monday, October 1, 2018 from 1:30pm - 5:00pm

To register, simply add the session to your schedule: http://sched.co/FYq5

### Organizers:

- [Julien Brun](http://brunj7.github.io/about/), Scientific Programmer, National Center for Ecological Synthesis and Analysis (NCEAS), UCSB
- [Lauren Hallett](https://laurenmh.github.io/), Assistant Professor in Environmental Studies and Biology, University of Oregon


## Preparing for the Workshop

### Required software

We will primarily be using a web browser, `R`, `RStudio`. Please be sure these are all installed on your laptop, as follows:

- **R:** We will use R version 3.5.1, which you can download and install from [CRAN](https://cran.rstudio.com)

- **RStudio**: RStudio is an excellent front-end (IDE) for R with integrated graphics and coding tools and is recommended (read: required) for this course. It is free and available for both Windows, Mac OS X and Linux.
To download RStudio (current version is 1.1.456), visit [RStudio's download page](https://www.rstudio.com/products/rstudio/download/).
  *If you don't know how up to date your version of RStudio is, please download a recent version and install it*
    
- **R packages:** Please be sure you have installed or updated the following packages:

    - `remotes` (not needed, if you have `devtools` already installed) 
    - `rmarkdown`
    - `tidyverse` (includes `ggplot2`)
    - `lubridate`
    
#### There are several ways to install a R package:

- In the R console, type: `install.packages("package-name")` Note that R is **case sensitive**, and that the **package name should be in quotes**.

- In RStudio, click on the "Packages" tab in the bottom right quadrant of the interface, click Install, type the package name and click Istall _or_ click  Tools => Install Packages, type the package name and click Install

- In R for Windows clients, go to the Packages menu => Install package(s).

- In R for MacOS X clients, go to the Package & Data menu and click on Package Installer => CRAN (binaries) => Get list. Click on the box “install dependencies” in order to automatically install other necessary libraries while installing your R libraries.


If you want to generate PDF output from Markdown (we will mainly focus on html files), you will need to install LaTeX. For R Markdown users who have not installed LaTeX before, we recommend to follow the recommendations of [Xie et 2018] and that you install TinyTeX (https://yihui.name/tinytex/):

```r
install.packages("tinytex")
tinytex::install_tinytex()  # install TinyTeX
```

### Refresh your R skills

This workshop assumes a base level of experience using R for scientific and statistical analyses.
However, we realize that not everyone will be at the same place in terms of familiarity with the tools we'll be using.
If you'd like to brush up on your R skills prior to the workshop, check out this list of resources we like:

- The [Introduction to R](http://www.datacarpentry.org/R-ecology-lesson/01-intro-to-r.html) lesson in [Data Carpentry's R for data analysis](http://www.datacarpentry.org/R-ecology-lesson/) course.
- The QCBS [Introduction to R](https://qcbs.ca/wiki/r) lesson
- [RStudio's R Programming](https://www.rstudio.com/online-learning/) page

If you're a fan of cheat sheets, [RStudio](https://www.rstudio.com) provides some fantastic ones on their [Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/) page.

---

<div>
  <p align="center"><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png"  /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>. </p>
</div>


