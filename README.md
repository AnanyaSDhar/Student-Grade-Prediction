[![author](https://img.shields.io/badge/author-Ananya-ff69b4.svg?style=flat-square)](https://www.linkedin.com/in/ananya-sutradhar/)
[![GitHub followers](https://img.shields.io/github/followers/Ananya21?style=social)](https://github.com/AnanyaSDhar?tab=followers)
[![GitHub watchers](https://img.shields.io/github/watchers/AnanyaSDhar/Student-Grade-Prediction?style=social)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/watchers)
[![GitHub stars](https://img.shields.io/github/stars/AnanyaSDhar/Student-Grade-Prediction?style=social)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/AnanyaSDhar/Student-Grade-Prediction?style=social)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/network/members)

![GitHub language count](https://img.shields.io/github/languages/count/AnanyaSDhar/Student-Grade-Prediction?style=flat-square)
![GitHub top language](https://img.shields.io/github/languages/top/AnanyaSDhar/Student-Grade-Prediction?logoColor=9cf&style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/AnanyaSDhar/Student-Grade-Prediction?logoColor=important&style=flat-square)

[![GitHub issues](https://img.shields.io/github/issues/AnanyaSDhar/Student-Grade-Prediction?style=flat-square)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/issues?q=is%3Aopen+is%3Aissue)
[![GitHub closed issues](https://img.shields.io/github/issues-closed/AnanyaSDhar/Student-Grade-Prediction?style=flat-square)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/issues?q=is%3Aissue+is%3Aclosed)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/AnanyaSDhar/Student-Grade-Prediction?logoColor=yellow&style=flat-square)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/pulls?q=is%3Aopen+is%3Apr)
[![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/AnanyaSDhar/Student-Grade-Prediction?logoColor=yellow&style=flat-square)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/pulls?q=is%3Apr+is%3Aclosed)
[![LICENSE](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)](https://github.com/AnanyaSDhar/Student-Grade-Prediction/blob/master/LICENSE)
[![HitCount](http://hits.dwyl.com/AnanyaSDhar/Student-Grade-Prediction.svg)](http://hits.dwyl.com/AnanyaSDhar/Student-Grade-Prediction)

# Student-Grade-Prediction
### This is a machine learning project that predicts the grade of a student

![image](https://github.com/AnanyaSDhar/Student-Grade-Prediction/assets/90474789/8ef1d6f6-4539-4059-9d71-e1ed85d3bc8f)


## Objective
Prediction of the final grade of high school students

## Problem Statement
The problem statement can be defined as follows ”Given a dataset containing attribute of 396 students where using the features available from dataset and define classification algorithms to identify whether the student performs good in final grade exam, also to evaluate different machine learning models on the dataset.”


## Attribute Information:
* school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
* sex - student's sex (binary: 'F' - female or 'M' - male)
* age - student's age (numeric: from 15 to 22)
* address - student's home address type (binary: 'U' - urban or 'R' - rural)
* Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
* traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
* studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
* failures - number of past class failures (numeric: n if 1<=n<3, else 4)
* paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
* activities - extra-curricular activities (binary: yes or no)
* higher - wants to take higher education (binary: yes or no)
* internet - Internet access at home (binary: yes or no)
* famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
* freetime - free time after school (numeric: from 1 - very low to 5 - very high)
* goout - going out with friends (numeric: from 1 - very low to 5 - very high)
* health - current health status (numeric: from 1 - very bad to 5 - very good)
* absences - number of school absences (numeric: from 0 to 75)
* G1 - first period grade (numeric: from 0 to 20)
* G2 - second period grade (numeric: from 0 to 20)
* G3 - final grade (numeric: from 0 to 20, output target)

# Methodology

Different models can be developed to predict students’ grades in the enrolled courses, which provide valuable information to facilitate students’ retention in those courses. This information can be used to early identify students at-risk based on which a system can suggest the instructors to provide special attention to those students.

Using various packages such as seaborn & matplotlib to represent the data along with different attributes graphically or pictorially to analyse the dataset for predicting the Final Grade(G3).

## Machine Learning Algorithms used
1. Linear Regression
2. SVM
3. Random Forest

## Results for different models
![image](https://github.com/AnanyaSDhar/Student-Grade-Prediction/assets/90474789/31090660-53c9-4ba1-8523-2f67c51b0638)
![image](https://github.com/AnanyaSDhar/Student-Grade-Prediction/assets/90474789/ee9cab89-3f5d-4249-8e1a-fd7895e4f22e)

### Clearly Random Forest Regressor performs better than other models, therefore we deployed our web app using RFR model. 




