# Latex-Dissertation-Template
 LaTeX Template for a University of Rochester Dissertation. It is built according to the guidelines set by: http://www.rochester.edu/Theses/. 
 
To see the result of compiling this document open "master.pdf". This template includes an example bibliography and properly formatted page numbers for the frontmatter and table of contents. It also uses the [subfiles package](https://www.ctan.org/pkg/subfiles) which allows you to either compile the whole document by compiling "master.tex" or compiling a chapter individually. Though it is formatted specifically for the University of Rochester, it will likely be close to many other Universities' guidelines as well. 

### You will need a working TeX Installation
The PDF was generated with LuaTeX using the latest (July 2020) [MikTeX](https://miktex.org/) distribution. 

### Recommended Editor

I wrote my dissertation using VS Code as my Latex editor. I included my vscode settings and tasks which you should copy into your own ".vscode" folder. If you do not use vscode you can safely delete "settings.json" and "tasks.json". If you are just starting to use VS Code for LaTeX I highly recommend the ["Latex Workshop"](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) and ["Latex language support"](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support) extensions. The default build task in "tasks.json" can be run by pressing CTRL+SHIFT+B and runs the following commands in order:

lualatex master -> bibtex master -> lualatex master -> lualatex master -> git commit --all -m 'auto' -> git push --all

"settings.json" also is set to always turn on word wrapping and to auto-save every 10 seconds.  

### Note About subfiles
Compiling a single chapter is useful only for checking formatting and text content. Any references to labels that occur outside that chapter (including bibliography) will not work properly. The references and labels will only be correct when compiling the whole dissertation. 


### Note About .gitignore
PDF files are ignored since this will greatly inflate the size of the repo.
