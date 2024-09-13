This files runs simulations for the AI minimal group experiment.

The basic structure and code follows the examples outlined by Solomon Kurz in his
'power' blogs and Lisa Debruine's 'faux' package. 

For Solomon's blog posts, see here: https://solomonkurz.netlify.app/tags/power/

For Lisa's faux package, see here: https://debruine.github.io/faux/


# What is the easiest way to access this project? #

If you want to see and work with the code, then:

1. Clone, fork or download the project from github to your local machine.
See this link for the difference between cloning and forking. https://github.com/orgs/community/discussions/35849

2. Open the analysis.Rproj file and renv() will automatically bootstrap itself.

3. Use renv::restore() to install all of the packages. Say yes.

4. At this point, you can use the project with the same package versions that are stored in the renv.lock file.


# General structure of files and folders #

- There is one R project file:

**simulation.Rproj**. 

- There is one R markdown file:

**sims.Rmd**

This file runs the simulations and saves figures and data in the folowing folders.

**/figures/**
**/data/**

Since the model objects that the sims are based on are quite large files, we have not uploaded these.
However, these model objects are not required should you wish to re-run the simulations for yourself.