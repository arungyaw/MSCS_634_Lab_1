# Lab 1: Data Visualization, Data Preprocessing, and Statistical Analysis Using Python in Jupyter Notebook

## Purpose of the Lab

The purpose of this lab was to practice basic data analysis using a taxi fare prediction dataset. The lab included loading a CSV dataset into a Pandas DataFrame, viewing the first few rows of the data, creating visualizations before preprocessing, applying data preprocessing techniques, and performing statistical analysis. These steps helped prepare the dataset for better understanding and possible future machine learning tasks.

## Key Insights from Visualizations

The passenger count distribution showed that most taxi trips were completed by a single passenger. This indicates that solo rides were the most common trip type in the dataset, while trips with larger groups were less frequent.

The taxi pickup location scatter plot showed that most pickup points were concentrated in one main geographic area. This suggests that the majority of trips started within a common service region. A few points appeared far from the main cluster, which may represent unusual locations or possible data entry issues that needed further review during preprocessing.

## Key Insights from Statistical Measures

The general overview using `.info()` helped identify the structure of the dataset, including column names, data types, and non-null values. The `.describe()` output provided a summary of numerical columns, including count, mean, minimum, maximum, and quartile values.

The central tendency measures helped summarize the typical values in the dataset by calculating minimum, maximum, mean, median, and mode. These measures gave a clearer understanding of common patterns in the numerical columns.

The dispersion measures showed how spread out the numerical values were. Range, quartiles, IQR, variance, and standard deviation helped identify variation in the dataset and supported the outlier detection process.

The correlation matrix was used to examine relationships between numerical columns. This helped show whether variables such as pickup location, drop-off location, and passenger count had strong, weak, positive, or negative relationships.

## Challenges and Decisions Made

One challenge was to use the dataset after missing value handling and outlier removal for statistical analysis. This was done because missing values and extreme outliers can distort mean, variance, standard deviation, and correlation results. Using the cleaned dataset made the statistical summary more reliable.

For data reduction, sampling was used to reduce the number of rows, and the `key` column was removed because it mainly served as an identifier and did not directly support analysis of taxi trip patterns. Although the first five rows shown by `.head()` may look similar before and after sampling, the dataset shape confirmed that the number of rows was reduced.

## Conclusion

Overall, this lab provided hands-on experience with the main stages of data analysis. The taxi fare prediction dataset was loaded, visualized, preprocessed, and statistically analyzed. The visualizations helped identify passenger and location patterns, while preprocessing improved the quality of the dataset. The statistical analysis provided a deeper understanding of the data through summary statistics, central tendency, dispersion, and correlation analysis. These steps helped prepare the dataset for future analysis or machine learning model development.
