# Student-Success-Prediction
Predicting the Student Success (Final Grade) using different Regression Techniques

## Data Source : 
UCI Machine Learning (https://archive.ics.uci.edu/ml/datasets/student+performance)

## Data Columns :
#### Predictor or Regressor Variables:
**school** - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)

**sex** - student's sex (binary: 'F' - female or 'M' - male)

**age** - student's age (numeric: from 15 to 22)

**address** - student's home address type (binary: 'U' - urban or 'R' - rural)

**famsize** - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)

**Pstatus** - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)

**Medu** - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - 5th to 9th grade, 3- secondary education or 4 -higher education)

**Fedu** - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2- 5th to 9th grade, 3 - secondary education or 4 - higher education)

**Mjob** - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')

**Fjob** - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')

**reason** - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')

**guardian** - student's guardian (nominal: 'mother', 'father' or 'other')

**traveltime** - home to school travel time (numeric: 1 - 1 hour)

**studytime** - weekly study time (numeric: 1 - 10 hours)

**failures** - number of past class failures (numeric: n if 1<=n<3, else 4)

**schoolsup** - extra educational support (binary: yes or no)

**famsup** - family educational support (binary: yes or no)

**paid** - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)

**activities** - extra-curricular activities (binary: yes or no)

**nursery** - attended nursery school (binary: yes or no)

**higher** - wants to take higher education (binary: yes or no)

**internet** - Internet access at home (binary: yes or no)

**romantic** - with a romantic relationship (binary: yes or no)

**famrel** - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)

**freetime** - free time after school (numeric: from 1 - very low to 5 - very high)

**goout** - going out with friends (numeric: from 1 - very low to 5 - very high)

**Dalc** - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)

**Walc** - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)

**health** - current health status (numeric: from 1 - very bad to 5 - very good)

**absences** - number of school absences (numeric: from 0 to 93)

**G1** - first period grade (numeric: from 0 to 20)

**G2** - second period grade (numeric: from 0 to 20)


#### Target or Response Variable
**G3** - final grade (numeric: from 0 to 20)


## Methodology

1. Importing Libraries

2. Importing Data

3. Exploratory Data Analysis

4. One hot Encoding

5. Splitting Train and Test Data

6. Feature Scaling

7. Multiple Linear Regression

8. Support Vector Regression

9. Decision Tree Regression

10. Random Forest Regression

