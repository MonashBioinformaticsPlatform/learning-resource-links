# Learning resources for bioinformatics, genomics and computational biology

## General programming and command line

> In the wet lab, you might need to learn to pipette, use a centrifuge, or maybe run some gel electrophoresis before you can get useful results.
> In the dry lab, you need to learn to use a computer to automate tasks and analyse data before you can get useful results - often this means telling the computer what to do using plain text.

### Linux, the "shell", command line

- https://linuxjourney.com/
- https://www.edx.org/course/introduction-linux-linuxfoundationx-lfs101x-1
- http://rik.smith-unna.com/command_line_bootcamp -  an interactive command line tutorial in the browser
- https://www.codecademy.com/courses/learn-the-command-line/lessons/navigation/exercises/ls
- http://andrewjrobinson.github.io/training_docs/tutorials/unix/
- http://andrewjrobinson.github.io/training_docs/tutorials/hpc/

### R

#### Introductory R

- Intro R : https://monashdatafluency.github.io/r-intro-2/
- Rmarkdown: https://rmarkdown.rstudio.com/authoring_quick_tour.html
- R-more training material - a follow on from intro R - https://monashbioinformaticsplatform.github.io/r-more/
- [Introduction to R - Tidyverse](https://bookdown.org/ansellbr/WEHI_tidyR_course_book/)
- The R for data science ‘wrangling’ section for a detailed reference https://r4ds.had.co.nz/wrangle-intro.html
- Another Tidyverse tutorial: http://www.hiercourse.com/docs/Working_in_the_Tidyverse.pdf

- Making plots (examples) : http://www.statmethods.net/graphs/index.html
- Code School: Try R: http://tryr.codeschool.com/
- R programming - coursera: https://www.coursera.org/course/rprog
- Data Carpentry R lessons: https://datacarpentry.org/R-ecology-lesson/ and https://datacarpentry.org/genomics-r-intro/


#### Advanced R

- End-to-end visualisation using ggplot2; https://rviews.rstudio.com/2017/08/14/end-to-end-visualization-using-ggplot2/ 
- HarvardX biomedical data science MOOC: http://genomicsclass.github.io/book/ (Chapter 5 has good examples of linear model design and contrasts - with diagrams)


### Python

#### Introductory Python

- Monash Data Fluency [Introduction to Python Workshop](https://monashdatafluency.github.io/python-workshop-base/) material
  - ... uses some material from: [Data Analysis and Visualization in Python for Ecologists](http://www.datacarpentry.org/python-ecology-lesson/)
- The 'official' Python tutorial: https://docs.python.org/3/tutorial/
- http://rosalind.info/problems/list-view/?location=python-village 
- http://andrewjrobinson.github.io/training_docs/tutorials/python_overview/python_overview/ - more of a quickstart for those comfortable with programming
- Intro to Python: http://introtopython.org/
- Introduction to Data Processing with Python: http://opentechschool.github.io/python-data-intro/
- Python for Everyone (Basic introductory material, through to object oriented programming, interaction with web services, databases, plotting) https://www.py4e.com/lessons
- [BE/Bi 103 a: Introduction to Data Analysis in the Biological Sciences (Caltech)](https://bebi103a.github.io/index.html) - Data Science for Biology, with statistics and visualisation in Python

#### Advanced Python

- Magic methods, context managers (__enter__, __exit__ for 'with' and more !): http://www.rafekettler.com/magicmethods.html
- @property decorators, Descriptors: http://intermediatepythonista.com/classes-and-objects-ii-descriptors
- @staticmethod, @classmethod and @abc.abstractmethod
- https://julien.danjou.info/blog/2013/guide-python-static-class-abstract-methods
- Metaclasses: http://eli.thegreenplace.net/2011/08/14/python-metaclasses-by-example and https://stackoverflow.com/questions/100003/what-is-a-metaclass-in-python
- Understanding scope, closures: https://www.farside.org.uk/201307/understanding_python_scope 


## General Bioinformatics and Computational Biology

- EMBL-ABR training videos: https://www.youtube.com/channel/UC5WlFNBSfmt3e8Js8o2fFqQ/videos

#### Theory

- [Rosalind](http://rosalind.info/problems/locations/) - problem solving exercises in computational biology to learn the fundamentals
- [JHU Computational Genomics notebooks](https://github.com/BenLangmead/comp-genomics-class) - in depth code examples to help understand how genome short read alignment and assembly works. Burrows-Wheeler Transforms and de Bruijn graphs.

#### Genomics on the commandline

- [Data Carpentry Genomics Workshop](https://datacarpentry.org/genomics-workshop/) - a great starting point for learning genomics on the commandline.
- [Computational Genomics Tutorial](https://genomics.sschmeier.com/index.html) - based on the Massey University Genome Science course taught by Sebastian Schmeier. A very clear tutorial series that covers installing and running tools for doing NGS read quality control, genome assembly and mapping, annotation, variant calling and interpretation. Light on theory, but a good starting point for working through the mechanics of genomics on the commandline.

#### RNA-seq

- A big list of RNASeq links - nicely organized into sections like 'normalization' and 'batch effects': https://github.com/crazyhottommy/RNA-seq-analysis
- http://master.bioconductor.org/help/course-materials/2015/Uruguay2015/V6-RNASeq.html
- http://bioinf.wehi.edu.au/RNAseqCaseStudy/
- https://www.ebi.ac.uk/training/online/course/ebi-next-generation-sequencing-practical-course/rna-sequencing/rna-seq-analysis-transcripto-0
- RNASeq tutorial from UOregon: https://github.com/griffithlab/rnaseq_tutorial/wiki
- http://www.ngscourse.org/Course_Materials/alignment/tutorial/example.html
- https://f1000research.com/articles/5-1408/v2: RNA-seq analysis is easy as 1-2-3 with limma, Glimma and edgeR
- COMBINE- http://combine-australia.github.io/RNAseq-R/ 
- http://www.rnaseqforthenextgeneration.org/protocols/index.htm
- https://github.com/MaayanLab/intro-rnaseq-jupyter
- https://newonlinecourses.science.psu.edu/stat555/node/78/
- https://mikelove.github.io/counts-model/index.html
