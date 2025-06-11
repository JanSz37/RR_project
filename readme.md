This project is a translation done by Jan Szczepanek and Ronald Mjonono. The original project, done in R, can be found at https://www.kaggle.com/code/apoorvayerpude/crime-rate-econometric-analysis.

## Files in this repository

* **Data** is the folder contatining the dataset
* folders ending with **_files** are files created as a result of rendering quarto markdowns to html. They contain the styling etc. of those files.
* **renv** and **renv.lock** are files containing the R environment used to run the project. This is used in order to make the R portion of the code replicable. 
* **presentation_quarto_replicable**, with both the .html and .qmd suffix are the rendered presentation and its qmd source code respectively.
* **project_notebook_replicable**, with both the .html and .qmd suffix are the rendered document and its qmd source code respectively.
* **styles.css** is the styles file used to lower the font in the presentation.
* **project_notebook.ipynb** is an old version of the project. It is left here on purpose to illustrate that we are capable of converting ipynb files to qmd.

The project lacks a requirements.txt file, as after many attempts it proved not to work as intended, i.e. it did not provide the possibility of out-of-the-box rendering. We worked around that by using pip with a list packages in the qmd files. This makes the rendering a bit longer, but ensures unproblematic package control and installation.

## Use of LLMs

ChatGPT version 4o was used for code translation from R to Python.