Aayush Vishwakarma
Roll No: 25070123125
EXP 15 : Data Normalization and Encoding using Python
Theory
Data Normalization

Data normalization is a preprocessing technique used to scale numerical data into a specific range. It helps in improving the performance of machine learning models and ensures that no feature dominates due to large values.

Min-Max Normalization

Min-Max normalization scales data between 0 and 1 using the formula:

X
′
=
X
max
	​

−X
min
	​

X−X
min
	​

	​


It preserves the relationships between original data values and is commonly used when the distribution is not Gaussian.

Z-Score Normalization

Z-score normalization (standardization) transforms data so that it has a mean of 0 and a standard deviation of 1. It is calculated as:

Z=
σ
X−μ
	​


This method is useful when data follows a normal distribution.

Decimal Scaling

Decimal scaling normalizes data by dividing values by a power of 10. It shifts the decimal point to bring values into a smaller range. It is simple but less commonly used compared to other normalization methods.

Label Encoding

Label encoding is used to convert categorical data into numerical form by assigning each category a unique integer value. It is useful for machine learning models that require numerical input.

One-Hot Encoding

One-hot encoding converts categorical variables into binary columns. Each category is represented as a separate column with values 0 or 1. This prevents models from assuming any ordinal relationship between categories.

get_dummies() Function

The pd.get_dummies() function is used for one-hot encoding in Pandas. It automatically creates binary columns for categorical variables.

drop_first Parameter

The drop_first=True parameter is used to avoid the dummy variable trap by removing one column from the encoded variables, preventing multicollinearity.

DataFrame Creation

A DataFrame can be created using dictionaries where keys represent column names and values represent data entries. This is useful for testing and small datasets.

Conclusion

Thus, data normalization and encoding techniques were studied and implemented successfully using Python. Various normalization methods such as Min-Max normalization, Z-score normalization, and decimal scaling were applied to numerical data. Additionally, categorical data was transformed using label encoding and one-hot encoding techniques. The experiment demonstrated the importance of preprocessing in improving data quality and preparing datasets for machine learning and data analysis.
