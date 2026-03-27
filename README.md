# Data Analysis Using Pandas

## Aim
To create a dataset using Pandas, store it in a CSV file, and perform exploratory data analysis on a dataset by examining its structure, statistical summary, and missing values.

---

## Algorithm

### Part A: Dataset Creation

1. Import the required library `pandas`.
2. Create a dictionary containing student information such as Roll Number, Gender, Department, and CGPA.
3. Convert the dictionary into a Pandas DataFrame using `pd.DataFrame()`.
4. Save the DataFrame into a CSV file using `to_csv()` with `index=False`.
5. Display the dataset.
6. Find the shape of the dataset using `df.shape`.
7. Find the total number of elements using `df.size`.
8. Display dataset information using `df.info()` to check column types and non-null values.
9. Generate statistical summary of numerical columns using `df.describe()`.

---

### Part B: Dataset Upload and Exploration

1. Import required libraries `pandas` and `numpy`.
2. Load the dataset **Cars93.csv** using `pd.read_csv()`.
3. Display the dataset using `display()`.
4. View dataset structure using `df.info()`.
5. Check the dimensions of the dataset using `df.shape`.
6. Display the first five rows using `df.head()`.
7. Display the last five rows using `df.tail()`.
8. Display a random sample of rows using `df.sample()`.
9. Generate statistical summary using `df.describe()`.
10. Check for missing values in each column using `df.isnull().sum()`.
11. Check for duplicate rows using `df.duplicated().sum()`.
12. Count the number of unique values in each column using `df.nunique()`.

---

## Conclusion

Thus, a dataset was successfully created using the Pandas library and stored in a CSV file. The uploaded dataset was analyzed using various Pandas functions to understand its structure, size, and statistical properties. Data exploration techniques such as viewing the dataset, checking dimensions, identifying missing values, detecting duplicates, and finding unique values were performed. This process helps in understanding the dataset and preparing it for further data analysis and preprocessing.
