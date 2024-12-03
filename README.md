Python for Data Science Assignments

I. Assignment 1

This assignment file includes my code for the 18 exercises for basic Python. This encompasses the following topics: Syntax & Variables (Numbers 1-3), Lists & Dictionaries (Numbers 4-5), Tuples & Sets (Numbers 6-7), Control Flow (Numbers 8-11), Function (Numbers 12-14) and Integration of all functions (Number 15)
Note: Number 11's match function requires a newer version of Python, which is at least 3.10

II. Assignment 2

This assignment file includes my code for the 4 exercises for a deeper dive into Python. In particular, this encompasses the following topics: Creation of a Function (Number 1), Filtering of Data (Number 2), Creation and Appending of a List (Number 3), Creation of a Function for Temperature Convertion (Number 4)

III. Assignment 3

This assignment file includes my code for the 4 exercises that tackle Object Oriented Coding. This is done through the following topics: creation of a class that adds the names of students and the courses, creation of a class that acts as a registration for classes (enlisting and dropping) and finally, creation of a class that assigns the grades and the respective GPAs.

IV. Assignment 4

Note before proceeding: 
1. Download the "annotations" folder in the GitHub Repository
2. Make sure to update the "annotations" variable to the specific path where you downloaded the "Annotations". Edit this for all the cells.
3. Number 3's match function requires a newer version of Python, which is at least 3.10

This assignment file includes my code for the 7 exercises for Basic Libraries, specifically os, glob and shutil. This is composed of the following topics: 1) Counting files of a folder, 2) Checking if the files follow the naming convention, 3) Extracting files per year, per month and per month-year, 4) Creating a new folder, 5) Sorting files, 6-7) Extracting information based on file naming convention

Disclaimer: All those part of incorrect convention will not be included in the succeeding numbers since they do not follow the naming convention pattern and as such, the numbers in the file are not intuitive and would need further information on how to interpret (only given the corresponding values for those following the naming convention and as such, I have only extracted the data from these)

V. Assignment 5

Note Before Proceeding:
1. Download the "annotations" folder in the GitHub Repository
2. Make sure to update the "annotations" variable to the specific path where you downloaded the "Annotations"
3. Make sure you have a Python version of at least 3.10+ for the match function to work
4. The dataset contains annotation files only from the first half of the year.

This assignment file includes my code for the 7 exercises for Basic Libraries, specifically re, os, glob, and shutil. This is composed of the following topics:
- Counting files in a folder,
- Checking if the files follow the naming convention,
- Extracting files per year, per month, and per month-year,
- Creating a new folder,
- Sorting files,
- Extracting information based on file naming convention.
  
Disclaimer: All files that are part of the incorrect convention will not be included in the succeeding steps, as they do not follow the naming convention pattern. Consequently, the numbers in the files are not intuitive and would require further clarification on how to interpret them. Only files that follow the naming convention pattern have been included, and data was extracted from these. 

Make sure to import re, os, glob, datetime, json, pickle and collections.

VI. Assignment 6

Note Before Proceeding:
1. Download the "netflix_titles" and "train_and_test2 2.csv" 
2. Make sure to update the "path" variable to the specific path where you downloaded the files
3. The dataset does not contain any titles in 2021 for the Philippines

This assignment file includes my code for the exercises related to Netflix and Titanic dataset analysis. This is composed of the following topics:
- Checking for missing ratings in the Netflix dataset using isna() and indexing,
- Analyzing titles released in the Philippines in 2021, including fallback logic for the most recent year using conditional checks and value_counts(),
- Filtering movies released in 2020 with complete information using dropna() to remove missing values,
- Identifying the year with the most titles using value_counts() to find the most frequent release year,
- Calculating the average number of releases since 2010 using groupby() and mean(),
- Analyzing gender- and class-based survival rates from the Titanic dataset using groupby() and calculating the mean.

Make sure to install pandas.

VII. Assignment 7

This assignment file includes my code for the exercises involving Pandas DataFrame operations. The exercises cover the following Pandas topics:
- String operations in Pandas (e.g., str.split() and str[0]) for extracting initials from the professor's name,
- Merging dataframes using an index and combining them based on a shared column with join(),
- Combining dataframes using merge() based on a shared column,
- Extracting specific information from a column using string operations (str.split()).

Make sure to install pandas.

VIII. Assignment 8 

This assignment file includes my code for the exercises related to the analysis of student data, using various types of visualizations and statistical computations. This is composed of the following topics:

- Creating a line plot of study time against student names to visualize the study time distribution across students, and identifying the student with the highest study time.
- Creating a histogram of grade frequencies, identifying the grade range with the highest frequency of students using bins set to auto.
- Creating an ECDF plot to visualize the cumulative distribution of grades, and calculating the percentage of students scoring below 85.
- Creating a strip plot of grades by course to analyze the distribution of grades across different courses, and identifying the course with the most spread in grades.
- Creating a swarm plot to visualize study time by gender, and calculating the average study time for each gender, highlighting which gender has the highest average study time.
- Creating a point plot of grades per course to visualize the average grade for each course, and identifying the course with the highest average grade.

Make sure to install pandas, seaborn, and matplotlib.pyplot.
