\# Exploratory Data Analysis (EDA) – Titanic Dataset



\## 📌 Project Overview



This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset. The goal is to explore passenger characteristics, identify missing values, clean the data, and investigate patterns and relationships related to passenger survival.



\## 🎯 Objectives



\* Understand the structure and characteristics of the dataset.

\* Identify and handle missing values.

\* Generate descriptive statistics.

\* Visualize passenger distributions and relationships.

\* Explore trends associated with passenger survival.

\* Summarize the key findings.



\## 🛠️ Tools and Technologies



\* Python

\* JupyterLab

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn



\## 📂 Dataset



\*\*Dataset:\*\* Titanic Training Dataset (`train.csv`)



The dataset contains 891 passenger records and 12 original columns, including passenger class, age, gender, fare, family information, and survival status.



\## 🔍 Project Workflow



\### 1. Data Loading



\* Loaded the Titanic dataset using Pandas.

\* Examined the first few rows and dataset dimensions.



\### 2. Data Exploration



\* Used `head()` to inspect the data.

\* Used `shape` to check the number of rows and columns.

\* Used `info()` to examine column data types and non-null values.

\* Used `describe()` to generate descriptive statistics.

\* Used `isnull().sum()` to identify missing values.

\* Used `value\_counts()` to examine survival counts.



\### 3. Data Cleaning



\* Checked for duplicate records.

\* Filled missing age values using the median.

\* Filled missing embarkation values using the mode.

\* Created a `Cabin\_Known` feature to indicate whether cabin information was available.

\* Removed the original `Cabin` column.



\### 4. Data Visualization



The following visualizations were created using Matplotlib and Seaborn:



1\. \*\*Age Distribution Histogram\*\* – Examined the distribution of passenger ages.

2\. \*\*Age Boxplot\*\* – Examined the spread of passenger ages and potential outliers.

3\. \*\*Age vs. Fare Scatterplot\*\* – Explored the relationship between passenger age and ticket fare.

4\. \*\*Pairplot Analysis\*\* – Compared survival status, age, fare, and passenger class.

5\. \*\*Correlation Heatmap\*\* – Examined correlations among selected numerical features.

6\. \*\*Survival Count Plot\*\* – Compared the number of passengers who survived and did not survive.

7\. \*\*Survival by Passenger Class\*\* – Compared survival counts across passenger classes.

8\. \*\*Survival Rate by Gender\*\* – Compared survival rates between male and female passengers.

9\. \*\*Survival Rate by Embarkation Port\*\* – Compared survival rates among passengers boarding at different ports.



\### 5. Trends and Relationships



The visualizations were used to investigate:



\* Differences in survival outcomes by gender.

\* Differences in survival across passenger classes.

\* Relationships between passenger age, ticket fare, and survival.

\* Differences in survival rates by embarkation port.



\### 6. Summary of Findings



The analysis demonstrates how data exploration, missing-value handling, descriptive statistics, and visualizations can be used to understand passenger characteristics and investigate survival patterns in the Titanic dataset.



\## 📸 Screenshots



Screenshots of the Python code and corresponding visualization outputs are included in the `screenshots/` folder.



The screenshots provide supporting evidence of the analysis performed in JupyterLab.



\## 📁 Project Files



\* `EDA\_Titanic.ipynb` – Jupyter Notebook containing Python code, analysis, and visualizations.

\* `EDA\_Titanic\_Report.pdf` – PDF report of the analysis.

\* `train.csv` – Original Titanic dataset.

\* `README.md` – Project documentation.

\* `screenshots/` – Screenshots of the code and visualization outputs.



\## ▶️ How to Run the Project



1\. Install Python and JupyterLab.



2\. Install the required libraries:



&#x20;  ```bash

&#x20;  pip install pandas numpy matplotlib seaborn

&#x20;  ```



3\. Place `train.csv` in the project directory.



4\. Open `EDA\_Titanic.ipynb` in JupyterLab.



5\. Run the notebook cells in order.



\## ✅ Conclusion



This project demonstrates practical skills in Python-based data exploration, data cleaning, descriptive statistics, and visualization. It provides an introduction to identifying patterns and relationships in a dataset through Exploratory Data Analysis.



