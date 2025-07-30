# Adult_Income_Dataset_Analysis
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Adult Income Dataset Analysis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #f4f4f4;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        code, pre {
            background-color: #eee;
            padding: 4px 8px;
            display: inline-block;
            border-radius: 5px;
        }
        pre {
            white-space: pre-wrap;
        }
        ul {
            list-style-type: square;
            margin-left: 20px;
        }
        a {
            color: #2980b9;
        }
        .section {
            background-color: #fff;
            padding: 20px 30px;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>

    <div class="section">
        <h1>Adult Income Dataset Analysis</h1>
        <p>This project explores the <strong>Adult Income Dataset</strong> from Kaggle. The goal is to analyze the dataset using Python libraries like <code>pandas</code>, <code>matplotlib</code>, and <code>seaborn</code>, clean the data, and find insights such as which demographics are more likely to earn over $50K per year.</p>
    </div>

    <div class="section">
        <h2>📂 Dataset Source</h2>
        <p>Available on <a href="https://www.kaggle.com/competitions/adult-census-income" target="_blank">Kaggle - Adult Census Income</a></p>
    </div>

    <div class="section">
        <h2>📌 Objective</h2>
        <ul>
            <li>Load and explore the dataset</li>
            <li>Clean and preprocess the data</li>
            <li>Perform univariate and bivariate analysis</li>
            <li>Visualize important trends</li>
            <li>Identify income patterns using groupby and plots</li>
        </ul>
    </div>

    <div class="section">
        <h2>📊 Libraries Used</h2>
        <pre><code>pandas
numpy
matplotlib
seaborn</code></pre>
    </div>

    <div class="section">
        <h2>✅ Key Steps</h2>
        <h3>1. Data Loading and Exploration</h3>
        <ul>
            <li>Load CSV into pandas</li>
            <li>Show top/bottom rows</li>
            <li>Display data types and memory usage</li>
        </ul>
        <h3>2. Data Cleaning</h3>
        <ul>
            <li>Replace '?' with NaN</li>
            <li>Drop missing values and duplicates</li>
            <li>Convert columns to correct datatypes</li>
        </ul>
        <h3>3. Exploratory Data Analysis (EDA)</h3>
        <p><strong>Univariate:</strong> age, education, workclass, income</p>
        <p><strong>Bivariate:</strong> income vs. age, gender, workclass</p>
        <h3>4. Feature Transformation</h3>
        <ul>
            <li>Convert income to binary (0 for <=50K, 1 for >50K)</li>
            <li>Convert workclass to categorical datatype</li>
        </ul>
    </div>

    <div class="section">
        <h2>📈 Visualizations Included</h2>
        <ul>
            <li>Histograms for Age and Workclass</li>
            <li>Missing values heatmap</li>
            <li>Boxplot of Age vs. Income</li>
            <li>Groupby bar charts for income comparison</li>
        </ul>
    </div>

    <div class="section">
        <h2>📌 Insights</h2>
        <ul>
            <li>Private sector has most workers but Self-employed have higher proportion earning >50K</li>
            <li>Males are more likely to earn >50K</li>
            <li>Most high earners are aged 35–60</li>
        </ul>
    </div>

    <div class="section">
        <h2>🧠 Future Work</h2>
        <ul>
            <li>Apply ML classification models</li>
            <li>Feature engineering</li>
            <li>Cross-validation and accuracy evaluation</li>
        </ul>
    </div>

    <div class="section">
        <h2>🔖 Author</h2>
        <p><strong>ifra jabeen</strong><br>
        Self-learner in AI/ML | Exploring real-world datasets</p>
    </div>

</body>
</html>
