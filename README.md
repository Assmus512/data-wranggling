# Preparations for the CAS Data Engineering - Data Wrangling Module
## Create the Python ENV for the exercises
### 1 clone this repo locally
```
git clone https://github.com/fburnelli/cas_de_data_wrangling_prep.git
cd cas_de_data_wrangling_prep
```
###  2 Creating the env using  pip 
```
pip install -r requirements.txt
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```

### 2 (alternative option): If you prefer using Conda instead of pip for creating the env, this is how to create the env with conda
```
conda env create -f environment.yml
python -m ipykernel install --user --name wrangling --display-name "Python (wrangling)"
```
