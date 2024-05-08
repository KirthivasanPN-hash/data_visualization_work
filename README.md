These are few projects that I worked related to Data Visualization


Project 1: Iris Flower Classification

Summary: 
1. The dataset was classified according to the height and width of petals and sepals. An Exploratory Data Analysis (EDA) was conducted to deepen the understanding of the data.
   
2. Pair plots were utilized to visualize the relationships between pairs of features, with different species highlighted in varying colors. Box plots were employed to examine the distribution and identify any outliers for each feature. Additionally, a heatmap was created to assess the correlation among various attributes. For data preprocessing, the Label Encoder was utilized.
   
3. The dataset was subsequently divided into training and test sets to facilitate the training of multiple models. Models trained included Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Naive Bayes, Decision Tree, and Random Forest.


Project 2: Aviation Itinary Fare Dataset Analysis

This project was created as a final project for a subject in Spring semester to understand the fare for various states.
I created a Extract, Transform, Load (ETL) pipeline to understand concepts of big data. The following is the short summary of creating a pipeline. 

Summary of Pipeline Creation Process
Extract: Data is gathered from the Bureau of Transportation and Statistics and uploaded to Cloud Storage buckets on the Google Cloud Platform. This step initiates the data pipeline, ensuring that raw data is readily available for transformation.

Transform: Utilizing Google Cloud Data Fusion with its Wrangler feature, the raw data undergoes cleaning and transformation. This includes filtering, aggregation, and cleansing to refine the data for accurate analysis. I filtered top 5 states for this. 

Load: The transformed data is loaded into BigQuery, which facilitates extensive analysis and supports real-time analytics. This allows for seamless integration with other datasets for future aviation data. 

Data Visualization Techniques and Insights
Bar plot: Utilized this to identify the airport and average fare
Histogram: To illustrate the difference between Highest and Lowest average fare
Bubble charts: Comparing the intensity of travellers and average fare 

Insights Gained from the Analysis
Data Distribution and Variability: The visual tools have highlighted the differences in data distribution across various features, revealing key insights into the typical behaviors and characteristics within the dataset.


Project 3: Insights from various situation based analysis
This was an assignment that I had to understand the relation between various correlation factors for understanding the data, understanding various factors such as assumptions of linear regression, such as independence, homoscedasticity, and normality of residuals and experimental group analysis. 

Problem 1: Bivariate Analysis of Heights
Scatter Plot: A scatter plot of sister and brother heights was likely used to visualize the relationship between these variables. This helps in understanding the distribution and correlation between sister and brother heights.
Problem 2: Exam Anxiety and Performance
Scatter Plot with Regression Line: A scatter plot showing the relationship between anxiety and exam scores, with a fitted regression line, was used. This plot visualizes the negative relationship, indicating that higher anxiety is associated with lower exam scores.
Problem 3: Analysis of Variance (ANOVA)
Boxplots: These would be useful to compare the distributions of rat weights across different feed types, showing median, quartiles, and potential outliers. It helps in visually assessing the differences between groups before conducting ANOVA.
ANOVA Table: This table, while primarily numerical, serves as a summary visualization of the statistical test results, showing sum of squares, mean squares, F-statistic, and p-values. It is instrumental in determining if there are significant differences across groups.
Problem 4: Empathy Across Game Types
Boxplot: A boxplot grouped by game type (GTA, HalfLife, Neutral) visually represents the empathy scores distribution across different game types. This helps in quickly assessing median values, variability, and outliers across categories.


