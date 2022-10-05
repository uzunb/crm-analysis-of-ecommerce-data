# CRM Analysis Of E-Commerce Data

## Project Description
The project refer from Customer Analysis in Data Science Course of Veri Bilimi Okulu. 

### Goals
- Customer Acquisition
- Customer Conversion and Retention
- Customer Churn Prediction
- Enriching the experience of the customer

### Steps
1. Data Collecting
2. Data Preprocessing
3. Feature Engineering
4. Customer Segmentation
5. Association Rules & Market Basket Analysis 

## About Dataset

### Context
Typically e-commerce datasets are proprietary and consequently hard to find among publicly available data. However, The UCI Machine Learning Repository has made this dataset containing actual transactions from 2010 and 2011. The dataset is maintained on their site, where it can be found by the title "Online Retail".

### Content
"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."

### Acknowledgements
Per the UCI Machine Learning Repository, this data was made available by Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

Image from stocksnap.io.

### Inspiration
Analyses for this dataset could include time series, clustering, classification and more.

## Installation

### Tested on this environment
- python==3.10.5
- pandas==1.5.0
- numpy==1.23.3
- matplotlib==3.6.0
- seaborn==0.12.0
- scikit-learn==1.1.2
- mlxtend==0.21.0

### Usage
```bash
# clone the repo
git clone https://github.com/uzunb/crm-analysis-of-ecommerce-data.git

# change to the repo directory
cd crm-analysis-of-ecommerce-data

# if virtualenv is not installed, install it
#pip install virtualenv

# create a virtualenv
virtualenv -p python3 venv

# activate virtualenv for LINUX or MACOS
source venv/bin/activate

# # activate virtualenv for WINDOWS
# venv\Scripts\activate.ps1
#     # throubleshooting for activation error in windows
#     Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

# install dependencies
pip install -r requirements.txt

# you can run all cells in main.ipynb
```


### Source & References
[E-Commerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
[Customer Analysis](https://youtu.be/DowbzgtH0-0)