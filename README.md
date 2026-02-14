This project aims to predict airline ticket prices using Machine Learning techniques. The model analyzes various features such as airline, source, destination, journey date, duration, total stops, and additional information to estimate the flight ticket price.
The objective is to help users understand price trends and make better booking decisions.
📊 Dataset Information
The dataset contains the following features:
Airline
Date_of_Journey
Source
Destination
Route
Dep_Time
Arrival_Time
Duration
Total_Stops
Additional_Info
Price (Target Variable)

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
🔍 Project Workflow

1️⃣ Data Collection
Flight dataset collected from publicly available sources.

2️⃣ Data Cleaning
Handling missing values
Removing duplicates
Converting date & time columns
Feature engineering
3️⃣ Exploratory Data Analysis (EDA)
Price distribution
Airline vs Price analysis
Stops vs Price
Duration vs Price
4️⃣ Feature Engineering
Extracting day, month from journey date
Extracting hour & minute from departure and arrival time
Converting categorical variables using One-Hot Encoding
