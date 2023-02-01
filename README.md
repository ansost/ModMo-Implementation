# ModMo-Implementation
This repository contains the code for the computational implementation BN task for the Modeling morphology class with Prof. Dr. Ingo Plag (WiSe 2022/23).

## File structure
The `Scripts` folder contains Jupyter notebooks.
- `data_preprocessing`: Code to format the input file to event files, the format needed in order to train a model with [`pyndl`](https://pyndl.readthedocs.io/en/latest/). The data is taken from: https://github.com/SabineArndtLappe/TrAML/files/7328577/20thcent.txt
- `train_model`: Code to train the NDL model with the event files from `data_preprocessing`
- `data_interpretation`: Code to calulate the F1 score, macro-averaged F1 scorea and overall prediction accuracy in percentages for the models. 
- `frequency_plots`: Code to plot the frequency of the suffixes int the dataset in a colorblind-friendly format. 
- `ModelingMorphology`: PDF containing the written explanation and motivation of this small analysis. 

## Author
[**Anna Stein**](https://slam.phil.hhu.de/authors/anna/)
