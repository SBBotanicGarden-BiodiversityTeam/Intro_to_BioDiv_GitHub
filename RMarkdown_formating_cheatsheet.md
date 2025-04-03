[Rmarkdown file](#rmarkdown-file)  
[Formatting](#formatting)  
- [Table of contents](#table-of-contents)  
- [R script](#r-script)
  
[Running your R script](#running-your-r-script)  
[Saving to html - "knit"](#Knit)

# Rmarkdown file
An R markdown file makes it easy to track and reproduce your R analysis. You can also save your work in different ways so when you're writing up the paper, you can look back on the .html or pdf etc to make sure you have the details right without having to rerun analyses with the parameters you think you used but can't quite be sure of.

To make an Rmd, once you have Rstudio open, go to File>New File>Rmarkdown  
Name your file, and pick the format you want your output Rmd - I go with html

## Formatting 
Formatting is very similar to [.md](Markdown_formatting_cheatsheet.md) files. Text, headers, emphasis (bold,italics,numbering,bullets) are the same.  \
This is a good cheat sheet for Rmd file formatting: https://r02pro.github.io/rmd-text-formating.html  \
The main differences that I use that are different are:  
1) Rmd table of contents (basically automatic)  
2) using r language identifyers for sections of script

### Table of contents
All you have to do is add the `toc:true` line (as shown below) and Rmd with automatically build your table of contents for you based on your headers. You can give it more instructions like I did in the example below. This particular toc example will include the 3 top level headers, will slide around with you wherever you are in the html, and will show the whole toc at all time (you can hve it collaps to its most basic headers when you're not hovering over it)  

    ---
    title: "AUTOMATIC_from when you make the .Rmd"
    author: "AUTOMATIC_from when you make the .Rmd"
    date: "`r Sys.Date()`"
    output: 
      html_document:
        toc: true
        toc_depth: 3
        toc_float: 
          collapsed: false
    ---
    
    ```{r setup, include=FALSE}
    knitr::opts_chunk$set(echo = TRUE)
    ```

    # VMMV_all ddRADseq data analysis
    ## Set up shop
    ### Set your working environment
    Input files you will need: .vcf file (data processing steps output from ipyrad) and a population codes csv (column of pop codes in order of sequences in vcf - more info below). 
    ```{r}
    setwd("/PATH/TO/WORKING/DIRECTORY/")
    ```
    ### Load libraries
    
    ### Read in inputs files
    etc
    etc

### R script
In an Rmd you just type text as normal until you have a section of code. To tell the Rmd that this is something that it should be able to run you put it in an R code block like you see in the example above, by sandwiching it between three ticks marks (the one that shares a key with the tilda `~`

    ```{r}
    some bit of script
    ```
## Running your R script
You can run each code block one by but clicking the green "play" icon at the upper right of the code block, or if you're comfortable with the code then you run the code in the whole document by scrolling to the bottom and click the "run code till here" icon which is the one just to the left of the "play" icon. 

## Knit
To save the results of the run in html (or pdf or word) format, click the knit icon of a blue yarn ball. This will have a time stamp and all output printed to you Rmd. When it "knits", it basically reruns everything to print in html so, heads up, it can take a while depending on the analyses. 

