# COMICAL
COMputatIonal Competencies for Academic Librarians"

# Computational Research Skills for Librarians: A Framework

This document is the result of my own (ongoing) effort to learn computational research tools (e.g. R, git, etc.) and figure out where the boundaries are between my own areas of (emerging, hopefully) expertise, and disciplinary-specific expertise. Related is the hope to create  a list of concrete and pragmatic services that librarians could offer with computational tools as I think this has been a fuzzy area and has led problems both learning new skills and advertsing services to users. 

More specifically, I want to think about what aspects of computational research are related to academic librarianship in a way that it makes sense for us to learn and teach them. For example, I think aspects of documentation, versioning, and code sharing are practically and philosophically highly related to our own practice, while things like complex data visualization and machine learning are less related to our work. Some specific skills I think are related to things we currently do, such as cleaning datasets computationally, bibliometric research, and text-mining fall in the middle. 

This is not particilarily philosophically coherent. 

# TODO

- Add references to recommendations for best practices related to data management in computational research
- move images to github and add citations
- Spell check


![Areas that Libraries can Impact](https://d2mxuefqeaa7sj.cloudfront.net/s_8C52BE63C3C9994B7D61D2D293D2CAFA1962E529CB2D5E78CAD53CCC1AB84042_1507553995845_file.jpeg)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_8C52BE63C3C9994B7D61D2D293D2CAFA1962E529CB2D5E78CAD53CCC1AB84042_1508257276286_screenshot.png)

# Why we should librarians be involved in computational research
- Better support for computational research across disciplines
- The link between computational research, data management, and reproducibility
    - Computational research requires its own data management methods
    - Computational research can itself help researchers be more reproducible as scripting data processing and analysis reduces researcher degrees of freedome, allows for auditability, and improves rigor.
- Support for data-intensive research, big data, digital humanities, etc.
- Data Management, Reproducibility, Rigor, and automating data processing and analysis

# Meta Computational Research Skills
The following I am calling "meta skills" as they relate less to any particular function than helping users learn whats possible and how to do general things across languages. 

## Highlu-Aligned Meta Skills

### Picking a language
    - Why:
    - Skills:
      - R
      - Python
      - Perkl

### Learning X language
    - Stratagies
    - Major sites

### Getting Help
    - Googling
    - Stackoverflow
    - How to ask for help

### Documenting your code
    - GoodDoc https://github.com/NCBI-Hackathons/GoodDoc 


### Producing transparent documents 
    - RMarkdown - http://rmarkdown.rstudio.com/ 
    - RNotebooks - http://rmarkdown.rstudio.com/r_notebooks.html 
    - Jupyter Notebooks - http://jupyter.org/ 
 
### Sharing your code
    - GitHub

### Reproducibility of Code
    - Containerization 
      - ReproZip - https://www.reprozip.org/ 
    - Tracking and documenting dependencies
    - Version control
      - Git - https://www.atlassian.com/git/tutorials 
 
### Reproducibility Via Code
    - Avoiding manual data manipulation
    - Reproducible Research with R and RStudio (book) http://christophergandrud.github.io/RepResR-RStudio/ 

### Developing a Workflow
    - Workflow: You should Have One https://speakerdeck.com/jennybc/workflow-you-should-have-one 
    - Automating Data Analysis Pipelines (presentation) http://stat545.com/automation01_slides/?utm_content=buffer92ec6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer#/automating-data-analysis-pipelines 
  
  
#Librarian specific Research Skills
  - Running searches programmatically?
    - Pubmed
    - Scopus
  - Conducting Bibliometrics / Scientometrics
  - Text mining
  
  
##Basic skills with R
  - How can I get X dataset into R?
    - Textual material 
    - Tabular/excel data
  - How do I clean up my data in R?
    - Changing NA values
    - Subsetting data
  - How do I get data out of R? 
  - How do I do basic data visualization in R?
    - Bar charts
    - Scatterplots
## Skills
- Text Mining Pubmed tutorial: 
  - CRAN: https://cran.r-project.org/web/packages/pubmed.mineR/index.html 
  - CRAN: risMED
  - https://www.r-bloggers.com/how-to-search-pubmed-with-rismed-package-in-r/



## Tutorials/Resources
- Library Carpentry
- R for Cats - https://rforcats.net/ 
- DataCamp - https://www.datacamp.com/home 
- R for Data Science (book - free) http://r4ds.had.co.nz/
- Python Data Science Handbook (book - free) https://github.com/jakevdp/PythonDataScienceHandbook 
- Reproducible Research With R and RStuio http://christophergandrud.github.io/RepResR-RStudio/ 


## Important Packages
- Tidyverse - https://www.tidyverse.org/ 
- DiagrammeR - http://rich-iannone.github.io/DiagrammeR/ (create diagrams with R)


## References
- Wilson, G., Bryan, J., Cranston, K., Kitzes, J., Nederbragt, L., & Teal, T. K. (2016). Good enough practices in scientific computing. *arXiv Preprint*, arXiv:1609.00037. http://doi.org/10.1371/journal.pcbi.1005510 
- Sandve, G. K., Nekrutenko, A., Taylor, J., & Hovig, E. (2013). Ten Simple Rules for Reproducible Computational Research. *PLoS Computational Biology*, *9*(10). http://doi.org/10.1371/journal.pcbi.1003285 

