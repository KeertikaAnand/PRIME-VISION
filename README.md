**Amazon Prime Data Analysis Dashboard**
This project involves building a data analysis dashboard using Power BI and performing data analysis tasks using Python for Amazon Prime Video content. The analysis includes content classification, recommendation systems, and exploratory data analysis using the Amazon Prime Video dataset. The dataset contains features such as the type, title, director, cast, country, date added, release year, rating, duration, and description of shows available on Amazon Prime Video.

**Technologies Used**
Power BI: For creating the interactive dashboard.
Python: For data cleaning, machine learning, and data analysis.
Pandas: For data manipulation and preprocessing.
NumPy: For numerical operations.
Scikit-learn: For machine learning model development.
Matplotlib/Seaborn: For data visualization.

**Project Features**
Exploratory Data Analysis (EDA): Visualizations and insights about the data.
Data Preprocessing: Handling missing values, encoding categorical features, and feature engineering.
Machine Learning:
Random Forest Classifier to classify content into Movies and TV Shows.
Content-Based Recommendation System to recommend similar shows based on descriptions.
Visualization: Create various graphs to visualize the distribution of content, ratings, and countries.

**Project Setup**
1. Install Dependencies
   
2.To install the necessary Python libraries, run the following command:
pip install pandas numpy scikit-learn matplotlib seaborn

3. Dataset
Ensure that you have the Amazon Prime dataset (CSV format) available on your local system or cloud storage. You can upload it into your Google Colab environment or use Power BI to import the dataset for the dashboard.

4. Run the Python Script
The Python script processes the dataset by cleaning, analyzing, and developing machine learning models. It performs:

Data Preprocessing: Clean the dataset by filling missing values, encoding categorical features, and dropping duplicates.
Exploratory Data Analysis (EDA): Generate various visualizations to better understand the distribution of data such as the type of content, countries, ratings, etc.
Machine Learning Models:
Random Forest Classifier for predicting content type (Movies or TV Shows).
Content-Based Recommendation System to suggest shows based on similar content descriptions.

**4. Power BI Dashboard**
Use Power BI to import the dataset and create an interactive dashboard. Follow these steps in Power BI:

Load the dataset (CSV or database).
Create visualizations (bar charts, line graphs, pie charts) based on the data.
Build interactive elements like slicers, filters, and tooltips.
Share or publish the dashboard.

**How to Contribute**
Fork this repository.
Create a new branch for your feature (git checkout -b feature-name).
Commit your changes (git commit -am 'Add feature').
Push to the branch (git push origin feature-name).
Create a new Pull Request.

**License**
This project is licensed under the MIT License - see the LICENSE file for details.

**Conclusion**
This project demonstrates how data analysis, machine learning, and visualization can be applied to analyze and recommend content on Amazon Prime Video. Through preprocessing, feature engineering, and machine learning models, we can classify content and recommend similar shows to users. The interactive Power BI dashboard adds a great layer of user engagement for decision-makers.
