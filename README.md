
<!-- README.md is generated from README.Rmd. Please edit that file -->

# An R project template to write scientific manuscripts reproducibly by integrating data, code, text and citations

About the project: - this is a template repository with an R project
that the [Jékely
lab](https://www.cos.uni-heidelberg.de/en/research-groups/gaspar-jekely)
uses to start to write new research papers.

Add the specific information about your paper here:

This repository contains the data and code for our paper:

> Authors, (YYYY). *Title of your paper goes here*. Name of journal/book
> <https://doi.org/xxx/xxx>

Our pre-print is online here:

> Authors, (YYYY). *Title of your paper goes here*. Name of
> journal/book, Accessed 06 Jun 2024. Online at
> <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Authors, (2024). *Compendium of R code and data for Title of your
> paper goes here*. Accessed 06 Jun 2024. Online at
> <https://doi.org/xxx/xxx>

## Contents

The project directory contains:

- [:file_folder: manuscript](/manuscript/Manuscript.qmd): Quarto source
  document for manuscript. Includes text, references and inserts the
  latest version of the figures from the /figures folder. There is also
  a rendered html version, `Manuscript.html`, suitable for reading.

- [:file_folder: data](analysis/data): Data used in the analysis.

- [:file_folder: figures](manuscript/figures): Plots and other
  illustrations

- [:file_folder: supplements](manuscript/supplements): Supplementary
  materials including notes and other documents prepared and collected
  during the analysis.

- [:file_folder: source_data](manuscript/source_data): Source data files
  associated with each figure containing all data points that have been
  plotted in the figure. These files should be submitted together with
  the paper.

## How to run in your browser or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

If you would like to use the template, you could open Rstudio in your
computer, then go to File \> New Project \> Version Control \> Git.
Under repository URL add the URL of this page
<https://github.com/JekelyLab/new_paper_template> and save it in a local
folder.

The R project will live in the folder (as working directory) where the
new_paper_template.Rproj file is saved. All other files and directories
will be accessed relative to this working directory. This way the
project is portable and self-contained.

The working directory contains this README file, a LICENCE file, a
CITATION.cff file, the .gitignore file and the R project file. You can
update these files to fit your project.

### Licenses

**Text, figures, code, data :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

### Acknowledgements

This project is modified after
<https://annakrystalli.me/rrresearch/10_compendium.html>.
