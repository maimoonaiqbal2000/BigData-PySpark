# ML-Model-of-Customer-Churn

Repo Link:
https://github.com/ursekar/ML-Model-of-Customer-Churn/blob/master/Sparkify.ipynb

Repo Files:
1.) Notebook Sparkify.ipynb
2.) Readme Readme.md

Overview:
Sparkify is a music streaming service just as Spotify and Pandora. The data provided is the user log of the service, having demographic info, user activities, timestamps and etc. We try to analyze the log and build a model to identify customers who are highly likely to quit using our service, and thus, send marketing offers to them to prevent them from churning. We use F1 score to measure of model performance because we need precision and recall at the same time as we don't want to miss too many customers who are likely to churn whilst we don't want to waste too much on those who are not likely to churn. The model we built has a F1 score of 0.800, which is 16% higher than sending everybody offers. There is also a short article about this project posted here.

Data:
User log extracted from our service.

Packages:
1.) PySpark, 
2.) Pandas, 
3.) Matplotlotlib, 
4.) NumPy, 
5.) MLlib

Models:
1.) Logistic Regression, 
2.) Gradient Boosted Trees

Methodology:
1.) ETL
2.) EDA & Defining Label
3.) Feature engineering
4.) Modeling
5.) Feature import analysis
6.) Accomplishments (Conclusion)
