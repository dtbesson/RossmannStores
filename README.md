# Rossmann Stores
The Rossmann stores dataset is a publicly available dataset, which once featured a competition on Kaggle. It was set as coursework on my MSc Data Science course.

Rossmann is a chain of drug stores across Germany and the rest of Europe. The task is to predict the sales and customers numbers for 1,115 stores located in Germany, using predictors such as whether a store is running any promotional offers, the distance to the nearest competition store, and so on.

In this project, we:
- Review the data and assess its quality
- Clean and pre-process the data
- Perform exploratory data analysis to identify key features and trends
- Create new features or remove existing ones
- Build a regression model (XGBoost was used here)
- Draw relevant conclusions.

The information for each store is in the store.csv file, and the testing data is in the test.csv file. The training data file is too large for Github, but it is of identical format to the test.csv file, with 'Sales' and 'Customers' numbers filled in.

The final report is attached as RossmannReport.docx, and the accompanying Jupyter notebook is attached as RossmannCoursework.ipynb.
