# Acknowledgments

This GitHub repository contains the code used to analyse all fossil datasets presented in the manuscript Prow-Fleischer et al. (in prep) 

Code written and maintained by Ashley Prow Fleischer and Jood Al Aswad

Contact: prowa@stanford.edu and jood@vt.edu

# 
To view the code as a webpage, please visit: [Code](https://aprow620.github.io/Latitudinal_Extinction_Gradients/)

# Reproducibility Statement

All codes and data used in this paper are provided here for reproducibility.

There are two ways to access the Paleobiology Database data used in this study. You may either open the 'Devonian_pbdb.data.Feb2026.csv' file to access the processed fossil dataset utilized here, or if you wish to download straight from the database

The fossil occurrence analyses can be found and reproduced by opening index.html from the src folder, which is accompanied by the source code 'index.ipynb' which can be opened in Jupyter lab or a texteditor. Data files can be found in the 'data_files' folder, and files for the plate reconstructions can be found in the 'georeferences_files' folder. Figures generated for publication are in the figures folder.

The html rendering of the code can be accessed here: 


This code is free to reuse. If you use this code please cite as:



To reproduce this analysis, clone this repository and the environment following the commands.



```bash
git clone https://github.com/aprow620/Latitudinal_Extinction_Gradients.git
cd Latitudinal_Extinction_Gradients
```

Set up the conda environment and R dependencies:
```bash
conda env create -f environment.yml
conda activate lat-ext-grad
```

Restore R packages:
```bash
R -e "renv::restore()"
```

Launch the notebook:
```bash
jupyter notebook
```

Navigate to `src/index.ipynb`.
