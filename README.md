# EnergyConsumption

LondonDataExploration.ipynb contains all data exploration. 
> It uses daily_dataset.csv, which has (3510433, 9) w/ NaN values and (3498343, 9) w/o NaN values

LondonDataFeatureEngineering.ipynb contains all feature engineering.
> It uses a dataframe of shape (167817021, 3) and no NaN values

LondonDataModelTraining.ipynb contains a baseline model that I was planning to use for my comparisons.

LondonDataModelwGaussian.ipynb adds 10 percent Gaussian noise to the data.

LondonDataModelwPepper.ipynb adds 10 percent salt and pepper noise to the data.

Note that the "Data" folder is on the gitignore list so that it's not exposed to the public. This is because I started out using a dataset that is not supposed to be released to the public.
