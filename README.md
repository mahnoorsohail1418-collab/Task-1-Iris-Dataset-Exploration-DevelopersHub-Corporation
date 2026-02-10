Task 1: Iris Dataset Exploration - DevelopersHub Corporation

Task Objective
The main objective of this task is to explore, analyze, and visualize the Iris dataset to understand the patterns, distributions, and relationships between different features.  
This is a fundamental step in data science and AI/ML pipelines, as understandingthe data is crucial before applying any predictive models.  

Specifically, this task focuses on:
- Loading and inspecting the dataset.
- Performing descriptive statistics.
- Creating visualizations to identify patterns, correlations, and outliers.

Dataset Used
- Name: Iris Dataset  
- Source:Can be loaded via seaborn (sns.load_dataset(iris)) .
- Samples:150 total  
- Classes: 3 species of Iris flowers: setosa, versicolor, virginica. 
- Features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)

 Models Applied
- This task does not involve predictive modeling.  
- The focus is on Exploratory Data Analysis (EDA) and data visualization.  
- Tools and methods used:
  - Scatter Plots: To visualize relationships between pairs of features.
  - Histograms: To analyze the distribution of each feature .
  - Box Plots: To detect outliers and understand the spread of the data.  

Steps Performed
1. Import Libraries:  
   pandas, matplotlib.pyplot, seaborn for data handling and visualization.  

2. Load Dataset:  
   - Loaded Iris dataset into a pandas DataFrame.  
   - Displayed the first few rows using .head().

3. Data Inspection:  
   - .shape to check dataset dimensions.  
   - .columns to list feature names.  
   - .info() to check data types and missing values.  
   - .describe() to generate summary statistics for each feature.  

4. Visualizations: 
   - Scatter Plots: Showed relationships between each pair of features.  
   - Histograms: Showed value distributions for each feature.  
   - Box Plots: Highlighted outliers in sepal and petal dimensions.

Key Results and Findings
- Species Separation: 
   Petal length and width clearly separate the three species: setosa is distinct, while versicolor and virginica slightly overlap.  
- Sepal Observations:  
   Sepal length and width have some overlap between species, making them less useful alone for classification.  
- Distribution Patterns:  
   Histograms with 15 bins revealed detailed patterns in feature distributions.  
- Outliers:
   Box plots detected a few outliers in sepal width and petal dimensions.  
- Insights:
   The dataset is well-structured and clean, with no missing values.  
   Petal features are the most important for separating species, which aligns with common ML approaches to classify Iris flowers.  


