# Computational Research Skills for Librarians: A Framework

This document is the result of my own (ongoing) effort to learn open computational research tools (e.g. R, git, etc.) and determine the boundaries between my areas of expertise (broadly speaking: information structure and organization in the health sciences) and disciplinary-specific expertise such as that from informatics and computer science. The hope is to create a somewhat logical list of concrete services that academic librarians can offer for those learning or using computational tools in their research. I think this area has been fuzzy and it's made it hard to both learn skills and to offer services using those skills.

More specifically, I want to think about what aspects of computational research are related to academic librarianship such that it makes sense for us to learn, practice, and teach. For example, I think things like documentation, versioning, and code sharing are practically and philosophically highly aligned with our own existing practice, while things like complex data visualization and machine learning are not particilarily related to our work. Some specific things like text-mining,  bibliometric research, and helping clean and normalize datasets fall in the middle. 

This is not a particularly philosophically coherent document. 

I am never totally sure if anything I do is a good idea. 

# TODO

- Add references to recommendations for best practices related to data management in computational research
- move images to github and add citations
- Spell check

# Why should librarians be involved in computational research
- Better support existing computational research across disciplines (bio-informatics, health informatics, etc.)
- To support data management and reproducibile research
    - Computational research requires its own data management methods (need to curate code, deal with dependencies, find acceptable places for preservation and sharing)
    - Computational research can itself help researchers produce better quality data and be more reproducible and rigorous as scripting data processing and analysis reduces researcher degrees of freedom, allows for auditability, and improves rigor
- Many of the tasks we already do ourselves could be done better computationally
	- Examples: 
		- Searching databases programmatically for complex information like co-authorship, top grants for particular subfields
		- Cleaning and normalizing data from internal sources (usage data, collections data) and users (research data)
	

# Meta Computational Research Skills
The following is a list of skills/areas I'm calling "meta skills" as they relate less to any particular function than helping users learn what's possible and general skills regardless of discipline or programming language. 

## Highly-Aligned Meta Skills

### Documenting code (data and code management)
    - GoodDoc https://github.com/NCBI-Hackathons/GoodDoc 
    - Best Practices for writing code

### Producing transparent and reproducible documents (reproducibility, transparency, open access)
    - RMarkdown - http://rmarkdown.rstudio.com/ 
    - RNotebooks - http://rmarkdown.rstudio.com/r_notebooks.html 
    - Jupyter Notebooks - http://jupyter.org/ 
    - Reveal.js for presentations 

### Version Control

Git and Github
["A Quick Introduction to Version Control with Git and GitHub"](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)

### Sharing code (data and code sharing)
    - GitHub
    - Repositories
    - Best practices for code reproducibility and stability (see "Reproducibility of Code")

### Reproducibility of Code (data management)
    - Containerization 
      - ReproZip - https://www.reprozip.org/ 
      - Docker
    - Tracking and documenting dependencies
    - Version control
      - Git - https://www.atlassian.com/git/tutorials 
      	- https://github.com/k88hudson/git-flight-rules
      	- http://neuroplausible.com/github 


## Moderately Aligned Meta Skills

### Getting Help
    - Mindset for getting help with programming issues, heavy on searching, copying, being iterative
    - How to ask for help
    - Googling
    - Stackoverflow
 
### Reproducibility Via Code (data management)
    - Avoiding manual data manipulation
    - Reproducible Research with R and RStudio (book) http://christophergandrud.github.io/RepResR-RStudio/ 

### Developing a Workflow (data management)
    - Workflow: You should Have One https://speakerdeck.com/jennybc/workflow-you-should-have-one 
        - Shirley Zhao, "Principles and Practices for Reproducible Science,"  https://github.com/shirl0207/reproducible_science
    - Automating Data Analysis Pipelines (presentation) http://stat545.com/automation01_slides/?utm_content=buffer92ec6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer#/automating-data-analysis-pipelines 

### What are some major topics in computational methods (meta-topics, not disciplinarily aligned)
	- Machine Learning https://blog.safegraph.com/a-non-technical-introduction-to-machine-learning-b49fce202ae8 

## Not Particularily Aligned Skills

### Picking a language
    - What are the options? why pick a specific language? local supports for X language?
    - Options:
      - R
      - BASH
      	- Tutorial: https://github.com/liux1299/Bash_Demo
      - Python
      - Perl
      - SAS / SPSS
      - Markup languages

### Learning X language
    - Learning strategies and sites for learning a particular language.
    - Strategies
    - Major sites


### This is just a list
    - Extensive programming experience in any specific language (the ability to be a fully-functional programmer)
    - Data visualization
    - Deep knowledge of statistical methods embedded in R/SAS/Etc
    - Disiplinary specific skills (genomic analysis, etc.)

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


## Important Packages relevant to libraries (move to new document)
- Tidyverse (R)- https://www.tidyverse.org/ 
- DiagrammeR (R)- http://rich-iannone.github.io/DiagrammeR/ (create diagrams with R)
- Fulltext (R): An R package to search across and get full text for journal articles - https://ropensci.github.io/fulltext-book/
- OAcounts (Python): makes use of the free Crossref Rest API and the free Unpaywall Rest API to analyze how open access DOIs a journal has - https://github.com/ryregier/OAcounts
- rcrossref: https://ropensci.org/tutorials/rcrossref_tutorial/

## References / Further Reading
- Wilson, G., Bryan, J., Cranston, K., Kitzes, J., Nederbragt, L., & Teal, T. K. (2016). Good enough practices in scientific computing. *arXiv Preprint*, arXiv:1609.00037. http://doi.org/10.1371/journal.pcbi.1005510 
- Sandve, G. K., Nekrutenko, A., Taylor, J., & Hovig, E. (2013). Ten Simple Rules for Reproducible Computational Research. *PLoS Computational Biology*, *9*(10). http://doi.org/10.1371/journal.pcbi.1003285 

