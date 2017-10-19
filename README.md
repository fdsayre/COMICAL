# Computational Research Skills for Librarians: A Framework

This document is the result of my own (ongoing) effort to learn computational research tools (e.g. R, git, etc.) and deterine the boundaries between my areas of (emerging) expertise and expertise disciplinary-specific expertise from informatics, computer science, etc. The hope is to create a somewhat logical list of concrete services that academic librarians could offer for those learning or using computational tools in their research. I think this area has been fuzzy and it's made it hard to both learn skills and to offer services using those skills.

More specifically, I want to think about what aspects of computational research are related to academic librarianship in a way that it makes sense for us to learn, practice, and teach those aspects. For example, I think things like documentation, versioning, and code sharing are practically and philosophically highly aligned with our own existing practice, while things like complex data visualization and machine learning are less related to our work. Some specific things related services academic librarians already do like text-mining,  bibliometric research, and helping clean and normaize datasets fall in the middle. 

This is not a particilarily philosophically coherent document. 

I am never sure if anything I do is a good idea. 

# TODO

- Add references to recommendations for best practices related to data management in computational research
- move images to github and add citations
- Spell check


![Areas that Libraries can Impact](https://d2mxuefqeaa7sj.cloudfront.net/s_8C52BE63C3C9994B7D61D2D293D2CAFA1962E529CB2D5E78CAD53CCC1AB84042_1507553995845_file.jpeg)


![](https://d2mxuefqeaa7sj.cloudfront.net/s_8C52BE63C3C9994B7D61D2D293D2CAFA1962E529CB2D5E78CAD53CCC1AB84042_1508257276286_screenshot.png)

# Why we should librarians be involved in computational research
- To better support existing computational research across disciplines
- There is a link between computational research, data management, and reproducibility
    - Computational research requires its own data management methods
    - Computational research can itself help researchers be more reproducible as scripting data processing and analysis reduces researcher degrees of freedome, allows for auditability, and improves rigor
- Many of the tasks we already do could be done better computationally

# Meta Computational Research Skills
The following is a list of skills/areas I'm calling "meta skills" as they relate less to any particular function than helping users learn whats possible and general skills regardless of discipline or programming language. 

## Highly-Aligned Meta Skills

### Documenting code (best practices)
    - GoodDoc https://github.com/NCBI-Hackathons/GoodDoc 

### Producing transparent and reproducible documents 
    - RMarkdown - http://rmarkdown.rstudio.com/ 
    - RNotebooks - http://rmarkdown.rstudio.com/r_notebooks.html 
    - Jupyter Notebooks - http://jupyter.org/ 
    - Reveal.js for presentations 
 
### Sharing code
    - GitHub
    - Repositories
    - Best practices for code reproducibility and stability (see "Reproducibility of Code"_

### Reproducibility of Code
    - Containerization 
      - ReproZip - https://www.reprozip.org/ 
    - Tracking and documenting dependencies
    - Version control
      - Git - https://www.atlassian.com/git/tutorials 

## Moderately Aligned Meta Skills

### Picking a language
    - What are the options, why pick a specific languahe, local supports for X languahe.
    - Options:
      - R
      - Python
      - Perkl
      - SAS / SPSS
      - Markup langauges

### Learning X language
    - Learning strategies and sites for learning a particular language.
    - Stratagies
    - Major sites

### Getting Help
    - Mindset for getting help with programming issues, heavy on searching, copying, being iterative
    - How to ask for help
    - Googling
    - Stackoverflow
 
### Reproducibility Via Code
    - Avoiding manual data manipulation
    - Reproducible Research with R and RStudio (book) http://christophergandrud.github.io/RepResR-RStudio/ 

### Developing a Workflow
    - Workflow: You should Have One https://speakerdeck.com/jennybc/workflow-you-should-have-one 
    - Automating Data Analysis Pipelines (presentation) http://stat545.com/automation01_slides/?utm_content=buffer92ec6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer#/automating-data-analysis-pipelines 
  

# Librarian-Specific Programmatic Skills
  - Running searches programmatically?
    - Pubmed
         - CRAN: https://cran.r-project.org/web/packages/pubmed.mineR/index.html 
         - risMED https://www.r-bloggers.com/how-to-search-pubmed-with-rismed-package-in-r/
    - Scopus
    - Other API based databases
  - Conducting Bibliometrics / Scientometrics for your faculty
  - Text-mining 
  - Various analytics and research needs
  
  
# Basic skills with R (move to new document eventually)
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


## Tutorials/Resources
- Library Carpentry
- R for Cats - https://rforcats.net/ 
- DataCamp - https://www.datacamp.com/home 
- R for Data Science (book - free) http://r4ds.had.co.nz/
- Python Data Science Handbook (book - free) https://github.com/jakevdp/PythonDataScienceHandbook 
- Reproducible Research With R and RStuio http://christophergandrud.github.io/RepResR-RStudio/ 


## Important Packages (move to new document)
- Tidyverse - https://www.tidyverse.org/ 
- DiagrammeR - http://rich-iannone.github.io/DiagrammeR/ (create diagrams with R)


## References / Further Reading
- Wilson, G., Bryan, J., Cranston, K., Kitzes, J., Nederbragt, L., & Teal, T. K. (2016). Good enough practices in scientific computing. *arXiv Preprint*, arXiv:1609.00037. http://doi.org/10.1371/journal.pcbi.1005510 
- Sandve, G. K., Nekrutenko, A., Taylor, J., & Hovig, E. (2013). Ten Simple Rules for Reproducible Computational Research. *PLoS Computational Biology*, *9*(10). http://doi.org/10.1371/journal.pcbi.1003285 

