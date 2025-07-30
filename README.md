# Adult Income Dataset Analysis
This project explores the Adult Income Dataset (also known as the "Census Income" dataset) from Kaggle. The goal is to analyze the dataset using Python libraries like pandas, matplotlib, and seaborn, clean the data, and find insights such as which demographics are more likely to earn over $50K per year.

# 📂 Dataset Source
The dataset is available on Kaggle and contains demographic data used to predict whether an individual's income exceeds $50K/year.

# 📌 Objective
Load and explore the dataset

Clean and preprocess the data

Perform univariate and bivariate analysis

Visualize important trends

Identify patterns related to income using groupby and visualizations

# 📊 Libraries Used
1.bash
2.Copy code
3.pandas
4.numpy
5.matplotlib
6.seaborn
# ✅ Key Steps
# 1. Data Loading and Initial Exploration
Load the CSV file into a pandas DataFrame

Display top & bottom records

Show data types and basic stats

Check shape of the dataset

# 2. Data Cleaning
Replace ? values with NaN

Drop missing values and duplicates

Convert categorical columns to appropriate datatypes

Drop unnecessary columns like capital-gain, capital-loss, and educational-num

# 3. Exploratory Data Analysis (EDA)
# 🔹 Univariate Analysis:
Age distribution

Education levels

Workclass statistics

Count of people aged between 17–48

Number of Bachelors and Masters degree holders

# 🔹 Bivariate Analysis:
Income distribution across workclass and gender

Boxplots between income and age

Grouped mean incomes by category
# 4. Feature Transformation
Converted target column income to binary (0 for <=50K, 1 for >50K)

Converted workclass to categorical datatype

# 📈 Visualizations Included
Histograms for Age and Workclass

Heatmaps to visualize missing values

Boxplots for Age vs. Income

Grouped bar charts for Gender and Workclass comparisons

# 📌 Insights
People working in the Private sector have the highest count but Self-employed have the highest proportion of >$50K earners.

Males are more likely to earn >$50K than females.

Most people earning >$50K are aged between 35–60.

# 🧠 Future Work
Apply ML classification algorithms (like Logistic Regression, Random Forest) to predict income

Perform feature engineering

Use cross-validation and evaluate model accuracy

# 🔖 Author
# "ifra jabeen"
Self-learner in AI/ML | Exploring real-world datasets
