# LTER-ASM18 workshop -  Reproducible Data Visualization using Rmarkdown and ggplot2

Participants will use of Rmarkdown and ggplot2 to create document integrating R code, documentation and data visualization in compelling documents. The first half of the session will be focusing on an introduction to Rmarkdown and how this format can be used to make data processing and analysis more reproducible by combining, documentation and executable code chunks into one document, that can be rendered in different formats (PDF, html, …) to be shared. In the second half of this workshop, participants will take a deeper look into data visualization and how ggplot’s grammar of graphics approach can be used to conduct powerful data exploration and analysis visualizations. Basic knowledge of the R programming language recommended.

## Session

This training will be held on Monday, October 1, 2018 from 1:30pm - 5:00pm

Here to register: http://sched.co/FYq5

### Organizers:

- [Julien Brun](http://brunj7.github.io/about/), Scientific Programmer, National Center for Ecological Synthesis and Analysis (NCEAS), UCSB
- [Lauren Hallett](https://laurenmh.github.io/), Assistant Professor in Environmental Studies and Biology, University of Oregon


## Preparing for the Workshop

### Required software

We will primarily be using a web browser, `R`, RStudio, and `git`. Please be sure these are all installed on your laptop, as follows:

- **R:** We will use R version 3.5.1, which you can download and install from [CRAN](https://cran.rstudio.com)

- **RStudio**: To download RStudio, visit [RStudio's download page](https://www.rstudio.com/products/rstudio/download/).
  *If you don't know how up to date your version of RStudio is, please download an updated copy and install it*
    
- **R packages:** Please be sure you have installed or updated the following packages:

    - devtools
    - rmarkdown
    - DT
    - kableExtra
    - dplyr
    - purrr
    - ggplot2
    
    We'll be using the following package versions:
    
    - devtools: version 
    - dplyr: version 
    - purrr: verion
    - DT: version 
    - kableExtra: version 0.8.0
    - ggplot2: version 2.2.1
    
    Ideally, you should have the same versions installed. ...but as long as your versions are not too far off, you should be okay. To check your versions, you can run the following snippet:
    
    ```r
    for (p in packages) {sprintf("%s: version %s", p, packageVersion(p)) %>% print()}
    ```
### text editor:

If you already have something you like, feel free to use that code editor. Popular code editors include:
    
- Sublime Text
- Notepad++
- Atom
- Visual Studio Code
- Emacs
- vi(m)
        
    If you don't know if you have a code editor or know you don't have one, we recommend downloading [Atom](https://atom.io).

### Version control - git (and git bash): 

Please install git on your system: https://git-scm.com/downloads and follow the instructions. 

- Windows - you can set the options to default during the installation, until you reach `Configuring the terminal emulator to use with Git Bash` -> be sure `Use MinTTY` is selected.  This will install both git and a set of useful command-line tools using a trimmed down Bash shell.  
- Mac OSX - depending your OS version, you might have to run few commands from the terminal. Please refer to the `README.txt` that comes with the download regarding the exact steps to follow.

- **git:** [Download git](https://git-scm.com/downloads) and install it on your system.
- **GitHub:** We will be using [GitHub](https://github.com) so you will need create (or remember your existing) GitHub login

### Refresh your skills

This workshop assumes a base level of experience using R for scientific and statistical analyses.
However, we realize that not everyone will be at the same place in terms of familiarity with the tools we'll be using.
If you'd like to brush up on your R skills prior to the workshop, check out this list of resources we like:

- The [Introduction to R](http://www.datacarpentry.org/R-ecology-lesson/01-intro-to-r.html) lesson in [Data Carpentry's R for data analysis](http://www.datacarpentry.org/R-ecology-lesson/) course.
- The QCBS [Introduction to R](https://qcbs.ca/wiki/r) lesson
- [RStudio's R Programming](https://www.rstudio.com/online-learning/) page

If you're a fan of cheat sheets, [RStudio](https://www.rstudio.com) provides some fantastic ones on their [Cheat Sheets](https://www.rstudio.com/resources/cheatsheets/) page.
