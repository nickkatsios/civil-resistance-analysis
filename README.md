# Civil-resistance-analysis

- In this notebook, we will use data from the [NAVCO 1.2 Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0UZOTX) dataset to explore the question of why civil resistance works. Inspired by the famous book by Erica Chenoweth and Maria Stephan, we will explore the question of why civil resistance is more effective than violent resistance by examining prominent campaigns from 1945 to 2013 and reproduce some of the results from their book including the famous 3.5% rule. 

## Running the notebook

In order to be fully reproducible, the notebook requires dependencies to be installed and a virtual environment to be created and activated before running the .ipynb file locally. This can be done using poetry.

* First, clone the repo
```bash
git clone https://github.com/nickkatsios/civil-resistance-analysis.git
cd civil-resistance-analysis
```
* Install the dependencies
```bash
poetry install
```
* Activate the virtual environment created by poetry
```bash
source $(poetry env info -p)/bin/activate
```
* Run the notebook
```bash
jupyter notebook ./civil-resistance-analysis/analysis.ipynb
```

### Notes 
This project was made as an assignement of the Applied Machine Learning course at DMST AUEB.