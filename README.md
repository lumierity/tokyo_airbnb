This is a data exploration project using Python in Jupyter Notebook as part of my final project in a postgraduate program in Data Analytics. 
Conducted in April 2020, the project focuses on summarizing insights from (cleansed) 3m+ Airbnb bookings data made between August 2019-August 2020 as a result of the planned Tokyo Olympics in 2020.
The Python packages used were: pandas, numpy, seaborn, matplotlib, scikit-learn.

Project followed an end-to-end data analytics process from preparation (i.e. webscraping, wrangling), to visualization, then training, validation and test.
Out of personal curiosity, some experimentation with geopy and Google Maps API (through Google Cloud Platform) was used to identify the coordinates of the Olympic venues.

The machine learning algorithms adopted for this project is a result of independently reviewing 6 publications to examine their approaches to similar Airbnb price prediction projects.
The algorithms chosen for this project are: Linear regression (L1 regularization) (with and without PCA), Random Forest and SVM (RBF-kernel).

Due to time constraints, models were not applied in predicting prices. Project only determined the best predicting factors of prices, and the best model in predicting prices using various accuracy scores (i.e. R-squared and RMSE).

The best predictor of Airbnb prices during this period is Random Forest. The number of guests permitted in an accommodation (the 'accommodates' variable) proved to be the best indicator of Airbnb prices.

Further developments of this project can be:
- Adjust algorithm parameters to see change on their accuracy evaluation scores.
- Understand the visualization results of applying PCA on the data.
- Investigate the relationship between the Olympic venues with Airbnb prices, and identify the proximity between the Airbnb locations with these Olympic venues.
