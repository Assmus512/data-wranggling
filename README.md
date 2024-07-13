# Preparations for the CAS Data Engineering - Data Wrangling Module
## Create the Python Env for the exercises

### OPTION 1: Using Conda:
```
conda env create -f environment.yml
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```


### OPTION 2:If you prefer using pip:
```
pip install -r requirements.txt
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```


### OPTION 3: If you prefer using Deepnote :
```
copy the requirements.txt to /root/work/ and run pip install -r requirements.txt
