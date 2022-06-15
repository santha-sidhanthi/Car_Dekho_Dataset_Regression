
This is car selling price model. We used regressor model for this and choose which is the best regressor.
The best model is built by using Random Forest Regression Algorithm

EDA of the data includes but not limited to below.
   Removing the strings in kms driven,mileage etc
   Calculating the age of the car
   converting owner,seller_type,transmission into numerical columns
   Visualization of the data and inferences from these plots


The dataset has 13 columns:  ['selling_price', 'name','km_driven', 'owner', 'mileage', 'engine', 'max_power','seats', 'transmission', 'Seller_type', 'fuel', 'torque']



├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources, downloaded from Codingrad LMS
│   │
├── models             <- Trained and EDA pickle files "model.pkl" file [model trained and tested and saved on disk.] EDA_
│   │                 
│   │   ├── CleanedFormattedData.pkl
│   │   └── EDAcar.pkl ; Model.pkl
├── notebooks          <- Jupyter notebooks. "EDA_CARDATA.ipynb", "TRAIN&TEST.ipynb
│
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
├
└──
