# Preparations for the CAS Data Engineering - Data Wrangling Module
## Create the Python ENV for the exercises
### Creating the env with pip 
```
pip install -r requirements.txt
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```

### If you prefer using Conda  instead of pip, this is how to create the env with pip
```
conda env create -f environment.yml
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```
