# gtc-ml-project1-hotel-bookings
Overview
This project is a Jupyter Notebook that performs exploratory data analysis (EDA), data cleaning, and feature engineering on the Hotel Bookings dataset. The goal is to preprocess the data for building a machine learning model to predict booking cancellations (is_canceled target). The dataset includes features like booking details, guest information, and reservation status.
# Key phases:

- EDA: Summary statistics, missing values visualization, and outlier detection.
- Data Cleaning: Handle missing values, remove duplicates, cap outliers, and fix data types.
- Feature Engineering: Create new features like total_guests, total_nights, and is_family.
- Encoding & Preparation: Encode categoricals, remove leakage, and split into train/test sets.


# Dataset
The dataset (hotel_bookings.csv) contains ~119,390 rows and 32 columns, sourced from hotel booking records (e.g., arrival dates, guest counts, cancellation status). It includes both resort and city hotels.

# Requirements

Python 3.8+
Libraries 

- pandas
- numpy
- matplotlib
- seaborn
- missingno
- scikit-learn 
