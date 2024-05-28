# Master Thesis 2024

This repository contains all the necessary materials for conducting the experiments and generating the performance metrics throughout the thesis. The repository contains folders for the first and third BIE. For the second BIE, no code was used as solutions were only pasted in empty '.md' files such that they could be checked by the Markdownlint tool (https://github.com/DavidAnson/markdownlint.git)

## BIE 1:
For the first BIE, the only code necessary was to calculate the BERTScore metrics. Therefore, this folder only contains the notebook necessary to calculate these metrics:
- text_evaluation.ipynb

## BIE 3:
For the third BIE, the code was assessed. The folder, therefore, contains five .ipynb files:
- pipeline_1.ipynb
- pipeline_2.ipynb
- pipeline_3.ipynb
- pipeline_4.ipynb
- pipeline_5.ipynb


Each pipeline notebook relates to the specific use case as described in Chapter 3, 'Methodology' of the thesis. 

Furthermore, due to the size of the mimic4.db dataset, this could not be included in this repository. Therefore, the dataset itself, as well as the files to convert it to an SQLite database, can be accessed via https://github.com/MIT-LCP/mimic-code.git.



