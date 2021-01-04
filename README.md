This is a data exploration project using Python in Jupyter Notebook as part of my final project in a postgraduate program in Data Analytics. 
Conducted in April 2020, the project focuses on summarizing insights from (cleansed) 3m+ Airbnb bookings data made between August 2019-August 2020 as a result of the planned Tokyo Olympics in 2020.
The Python packages used were: pandas, numpy, seaborn, matplotlib and scikit-learn.

Project followed an end-to-end data analytics process from preparation (i.e. data sourcing using webscraping, wrangling), to visualization, then training, validation and test. Only approx 18,000 data points were trained and tested due to Jupyter Notebook's constraint in testing 1m+ data points of cleansed data.
Out of personal curiosity, some experimentation with geopy and Google Maps API (through Google Cloud Platform) was used to identify the coordinates of the Olympic venues.

The machine learning algorithms adopted for this project is a result of independently reviewing 6 publications to examine their approaches to similar Airbnb price prediction projects.
The algorithms chosen for this project are: Linear regression (L1 regularization) (with and without PCA), Random Forest and SVM (RBF-kernel).

Due to time constraints, models were not applied in predicting prices. Project only determined the best predicting factors of prices, and the best model in predicting prices using various accuracy scores (i.e. R-squared and RMSE).

The best predictor of Airbnb prices during this period is Random Forest. The number of guests permitted in an accommodation (the 'accommodates' variable) proved to be the best indicator of Airbnb prices.

Please view the code of this project in the following order, which represents the order of my code development process:
1. Initial results: includes data preparation and data visualization results.
2. Neighbourhood & Olympic venues (code experimentation)
3. Prediction: shows how 3+1 algorithms were applied in this project [Linear regression (L1 regularization) (with and without PCA), Random Forest and SVM (RBF-kernel].

Further developments of this project can be:
- Adjust algorithm parameters to see change on their accuracy evaluation scores.
- Understand the visualization results of applying Principal Component Analysis (PCA) on the data.
- Investigate the relationship between the Olympic venues with Airbnb prices, and identify the proximity between the Airbnb locations with these Olympic venues.

References for this project:
- Insideairbnb.com
- Various Towards Data Science articles on Medium (Topics: Webscraping techniques, Google Maps API, GeoPY, data wrangling, outliers processing, PCA application & analysis, L1 vs L2 regularization, Accuracy scores application & evaluation for Regression problems).
