 Predicting Sales Data for Rossmann Stores
This is a machine learning project for sales and customer count prediction of Rossmann stores.

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Elifchio/Sales_prediction

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```
Project Overview:
This project includes the steps of implementation of sales and customer value prediction of the 
test data of the Rossmann stores. Pre processing of the dataset can be followed through the notebook: pre processing3.
Then implementation of three different models (linear regression. decision tree regressor and xgboost) can be examined
in their respective files in the notebooks folders. 
All the dataset necessary to run the codes are added under the data/raw files. All the necessary packages are imported
within the respective codes. 
Python1 folder includes the source code of the latex documentation that was used to create the group report. 
Lastly, under the results file, the results of the the implementation of the best performing
model (XGBoost) to the test data can be found. 
