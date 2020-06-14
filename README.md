Sparkify

This project is designed to identify churn within a dataset comprised of user data for the fictional sparkify product.  The data is discrete user event data related to a music app similar to Pandora or Spotify.

The files within this project include:
- mini_sparkify_event_data.json - json file consisting of a subset of data used to build the project results
- Sparkify.ipynb - The main project notebook that analyzes and models the dataset
- README.md - this readme file

The Sparkify.ipynb is the major project deliverable.  It is designed to leverage pyspark on a larger dataset contained at s3n://udacity-dsnd/sparkify/sparkify_event_data.json.

The project uses the pyspark libraries, and specifically:
-pyspark.sql for SparkSession and functions module
-pyspark.ml for the model construction

The sections for the project include:
-Loading the dataset
-Exploratory data analysis w/ some distribution visualizations
-Cleaning the dataset
-Feature Engineering
-Modeling (Random Forest & Logistic Regression w/ scaling)
-Conclusion with potential improvements
