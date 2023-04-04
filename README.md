# Students Performance Indicator in Exams End to End ML Project

### Created a Environment
```
conda create -p venv python==3.8

conda activate venv/
```
### Install All Necessary Libraries
```
pip install -r requirements.txt

```

### About data :
- This dataset consists of the marks secured by the students in 3 subjects, Math, Reading, Writing.
- It'll be used to understand the influence of the parents background, test preparation etc on students performance.

### Objectives

- How good did students score in the 3 exames ?
- Do students who took test preparation course score better ?
- Do different races score different in exams ?
- Do different genders score diffrent in exams ?
- Do students with parents of higher level of education score better in exams ?
- Do students who score better in math score good in the rest of subjects ?

### Life cycle of Machine learning Project

- Understanding the Problem Statement
- Data Collection
- Data Checks to perform
- Exploratory data analysis
- Data Pre-Processing
- Model Training
- Choose best model

### 1) Problem statement
- This project understands how the student's performance (test scores) is affected by other variables such as Gender, Ethnicity, Parental level of education, Lunch and Test preparation course.


### 2) Data Collection
- Dataset Source - https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977
- The data consists of 8 column and 1000 rows.

 #### 2.1 Import Data and Required Packages
 - Importing Pandas, Numpy, Matplotlib, Seaborn and Warings Library.
 #### 2.2 Dataset information
 - gender : sex of students  -> (Male/female)
- race/ethnicity : ethnicity of students -> (Group A, B,C, D,E)
- parental level of education : parents' final education ->(bachelor's degree,some college,master's degree,associate's degree,high school)
- lunch : having lunch before test (standard or free/reduced) 
- test preparation course : complete or not complete before test
- math score
- reading score
- writing score

### 3. Data Checks to perform

- Check Missing values
- Check Duplicates
- Check data type
- Check the number of unique values of each column
- Check statistics of data set
- Check various categories present in the different categorical column

### 4. Exploring Data ( Visualization )
#### 4.1 Visualize average score distribution to make some conclusion. 
- Histogram
- Kernel Distribution Function (KDE)
#### 4.2 Violinplot
#### 4.3 Multivariate Analysis Using Pieplot
#### 4.4 Feature Wise Visualization
- UNIVARIATE ANALYSIS ( How is distribution of Gender ? )
- BIVARIATE ANALYSIS ( Is gender has any impact on student's performance ? )
- UNIVARIATE ANALYSIS ( How is Group wise distribution ?)
- BIVARIATE ANALYSIS ( Is Race/Ehnicity has any impact on student's performance ? )
- UNIVARIATE ANALYSIS ( What is educational background of student's parent ? )
- BIVARIATE ANALYSIS ( Is parental education has any impact on student's performance ? )
- UNIVARIATE ANALYSIS ( Which type of lunch is most common amoung students ? )
- BIVARIATE ANALYSIS ( Is lunch type intake has any impact on student's performance ? )
- BIVARIATE ANALYSIS ( Is Test prepration course has any impact on student's performance ? )
- CHECKING OUTLIERS
- MUTIVARIATE ANALYSIS USING PAIRPLOT

### 5. Conclusions
- Student's Performance is related with lunch, race, parental level education
- Females lead in pass percentage and also are top-scorers
- Student's Performance is not much related with test preparation course
- Finishing preparation course is benefitial.
