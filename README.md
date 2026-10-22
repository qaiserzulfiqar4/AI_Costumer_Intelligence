SmartBiz AI — Customer Intelligence & Purchase Prediction

📌 Project Overview

SmartBiz AI is an end-to-end Data Science project that analyzes online shopping behaviour and uses Machine Learning to predict whether a customer session will result in a purchase.

The project transforms raw data into meaningful business insights through data cleaning, Exploratory Data Analysis (EDA), professional visualizations, and predictive modelling.

🎯 Objectives

- Clean and prepare raw customer shopping data.
- Analyze customer behaviour and purchasing patterns.
- Identify factors associated with purchase decisions.
- Create professional charts and visualizations.
- Build a Random Forest classification model.
- Evaluate model performance using multiple metrics.
- Generate data-driven business recommendations.

📊 Dataset

Dataset Name: Online Shoppers Purchasing Intention Dataset

Source: UCI Machine Learning Repository

- Total records: 12,330 shopping sessions
- Attributes: 18
- Target variable: "Revenue"
- "Revenue = True": Purchase occurred
- "Revenue = False": No purchase occurred

Dataset link: https://doi.org/10.24432/C5F88Q

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- ucimlrepo
- Google Colab / Jupyter Notebook

🔍 Project Workflow

1. Data Collection

Load the online shopping dataset from the UCI Machine Learning Repository.

2. Data Cleaning

- Inspect missing values and duplicate records.
- Check column names and data types.
- Handle missing values where necessary.
- Prepare the dataset for analysis.

3. Exploratory Data Analysis (EDA)

- Analyze purchase and non-purchase sessions.
- Compare conversion rates across visitor types.
- Explore monthly purchasing trends.
- Examine relationships between numerical features.
- Compare browsing behaviour between buyers and non-buyers.

4. Data Visualization

Create professional visualizations, including:

- Purchase distribution bar chart
- Visitor type conversion analysis
- Monthly conversion trend
- Correlation heatmap
- Browsing behaviour comparison
- Feature importance chart
- Confusion matrix

5. Machine Learning

Train a Random Forest Classifier to predict purchase outcomes using customer shopping session features.

6. Model Evaluation

Evaluate the model using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrix

7. Business Insights

Use the analysis to identify customer behaviour patterns and suggest areas for improving website engagement and purchase conversion.

📈 Key Business Questions

1. Which visitor types have higher purchase conversion rates?
2. How does browsing behaviour differ between buyers and non-buyers?
3. Which features are most useful for predicting purchase outcomes?
4. What patterns are associated with unsuccessful shopping sessions?
5. How can businesses use data analysis to improve customer experience?

💡 Expected Business Value

- Better understanding of customer behaviour.
- Identification of potentially valuable customer segments.
- Data-driven website optimization opportunities.
- Support for marketing and conversion improvement strategies.
- Practical experience with an end-to-end Machine Learning workflow.

🚀 How to Run the Project

1. Open Google Colab: https://colab.research.google.com/
2. Create a new Python notebook.
3. Install the required dataset library:

!pip install ucimlrepo

4. Import the required libraries.
5. Load the dataset.
6. Run the data cleaning and EDA steps.
7. Generate the visualizations.
8. Train and evaluate the Random Forest model.
9. Review the final business insights.

📁 Project Outputs

The project can generate:

- Cleaned dataset CSV
- Feature importance report
- Executive summary CSV
- Data analysis charts
- Machine Learning evaluation results

⚠️ Limitations

This project uses a publicly available educational dataset, not confidential company data. Model performance and business recommendations must be validated before real-world deployment.

Feature importance shows which features the trained model uses; it does not prove that those features directly cause purchases.

👩‍💻 Author

Qaiser Jahan
Data Science Student | Aspiring Data Analyst

Skills: Python, Data Analysis, Data Visualization, and Machine Learning.

⭐ Conclusion

SmartBiz AI demonstrates how raw shopping data can be transformed into useful insights through Python, statistical analysis, data visualization, and Machine Learning.

The project provides practical experience in solving a business problem using an end-to-end Data Science workflow.

If you find this project useful, feel free to star the repository!
