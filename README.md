# Machine_Learning_LAB
LAB 1 Dataset - Diabetes Dataset
Shape: (500, 9)
Columns: Various medical measurements related to diabetes diagnosis
Missing Values: 225
Description: A modified version of the Pima Indians Diabetes dataset with missing values.

LAB 2 Dataset - Adult Dataset
Shape: (250, 16)
Columns: Various demographic and income-related attributes such as age, education, occupation, race, and income level
Missing Values: 350
Description: A subset of the Adult Income dataset, commonly used for classification tasks, with missing values in multiple columns.

LAB 3 Dataset - Breast Cancer Dataset
Shape: (569, 32)
Columns: Various diagnostic measurements for breast cancer detection
Missing Values: 868
Description: A modified version of the Breast Cancer Wisconsin dataset containing missing values.

LAB 4 Dataset - Bank and Personal Loan Dataset
Description Sheet: (20, 3) with 31 missing values
Data Sheet: (5000, 14) with 0 missing values
Columns (Data Sheet): Includes Age, Income, Education, Mortgage, and whether a person has a Personal Loan
Description: A dataset used for modeling personal loan approvals based on customer demographics and financial attributes.

LAB 5 Dataset - Employees Dataset
Shape: (5000, 8)
Columns: Employee-related data such as age, income, city, and purchases
Missing Values: 2587
Description: A dataset related to employee demographics and purchasing behavior, with a large number of missing values.

LAB 6 Dataset - 50 Startups Dataset
Shape: (50, 5)
Columns: R&D Spend, Administration, Marketing Spend, State, Profit
Missing Values: 22
Description: This dataset contains financial data of 50 startups, including their expenditures and profits, with some missing values.

LAB 7 Dataset - Iris Dataset
Shape: (150, 5)
Columns: Sepal and petal measurements along with species classification
Missing Values: 12
Description: A modified version of the famous Iris dataset with missing values, used for classification problems.

LAB 8 Dataset - Country Dataset
Shape: (167, 10)
Columns: Country-specific economic and health indicators such as child mortality, GDP, and life expectancy
Missing Values: 47
Description: A dataset used for economic and development analysis across countries.

Best Model that worked for Me:
Decision Tree - Its is useful in both classification and regression tasks unlike linear regressions(only for regression) and K-means(only for clustering).unlike KNN, the data does not need to be standardized or normalized,  Decision Trees can capture complex, non-linear relationships between features and target variables. Unlike Naïve Bayes, which assumes complete data, Decision Trees can handle missing values by splitting data intelligently. Decision Trees provide clear and interpretable rules, making them more understandable than K-Means or Naïve Bayes, which work with probabilities and distances. Unlike NLP models, which require large text datasets to perform well, Decision Trees can work efficiently even on small datasets.
Accuracy : 81%
