# Latex-Dissertation-Template
 LaTeX Template for a University of Rochester Dissertation. It is built according to the guidelines set by the University, see: http://www.rochester.edu/Theses/. It includes an example bibliography and properly formatted page numbers for the frontmatter and table of contents. It also uses the subfiles package (https://www.ctan.org/pkg/subfiles) which allows you to either compile the whole document by compiling "master.tex" or compiling a chapter individually. Though it is formatted specifically for the University of Rochester, it will likely be close to many other Universities' guidelines as well. 


### You will need a working TeX Installation
The PDF was generated with LuaTeX using the latest (July 2020) MikTeX (https://miktex.org/) distribution. 


### Note About subfiles
Compiling a single chapter is useful only for checking formatting and text content. Any references to labels that occur outside that chapter (including bibliography) will not work properly. The references and labels will only be correct when compiling the whole dissertation. 


### Note About .gitignore
PDF files are ignored since this will greatly inflate the size of the repo.
