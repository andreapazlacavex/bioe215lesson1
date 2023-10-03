#Lesson 1 - Readings Qs and As

*Project workflows*
Bryan (2017)
* What problems can setwd() cause in your scripts and how do RStudio projects address them? The need to manually input paths of one or more related projects. RStudio Projects can address this by creating a single folder with all project-related scripts working from one single .Rproj file with the working directory set-up as the project folder.
* When you call rm(list=ls()), what is removed from your environment? It deletes user-created objects from the global workspace.
* What’s left over that restarting your R session would remove? Packages are still available, any options to non-default values stay that way, and working directory is not affected.
* What’s the keyboard shortcut for restarting your R session? Command+Option+F10

*Version control*

Bryan (2018)

* The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely? Commit and push happen locally, pull happens remotely (in local R but pulls information from GitHub).

* Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)? Because, they are large bionary files.

* Why is Markdown useful for GitHub repos? Because, it can include outputs, links, files from R Projects in the form of HTML or GitHub.
