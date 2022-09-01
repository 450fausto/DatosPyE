About Dataset <br>
Context: <br>
The data were obtained in a survey of students math and portuguese language courses in secondary school. It contains a lot of interesting social, gender and study information about students. You can use it for some EDA or try to predict students final grade. <br>
<br>
Content: <br>
Attributes for both student-mat.csv (Math course) and student-por.csv (Portuguese language course) datasets:<br>
<br>
school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)<br>
sex - student's sex (binary: 'F' - female or 'M' - male)<br>
age - student's age (numeric: from 15 to 22)<br>
address - student's home address type (binary: 'U' - urban or 'R' - rural)<br>
famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)<br>
Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)<br>
Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)<br>
Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)<br>
Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')<br>
Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')<br>
reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')<br>
guardian - student's guardian (nominal: 'mother', 'father' or 'other')<br>
traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)<br>
studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)<br>
failures - number of past class failures (numeric: n if 1<=n<3, else 4)<br>
schoolsup - extra educational support (binary: yes or no)<br>
famsup - family educational support (binary: yes or no)<br>
paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)<br>
activities - extra-curricular activities (binary: yes or no)<br>
nursery - attended nursery school (binary: yes or no)<br>
higher - wants to take higher education (binary: yes or no)<br>
internet - Internet access at home (binary: yes or no)<br>
romantic - with a romantic relationship (binary: yes or no)<br>
famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)<br>
freetime - free time after school (numeric: from 1 - very low to 5 - very high)<br>
goout - going out with friends (numeric: from 1 - very low to 5 - very high)<br>
Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)<br>
Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)<br>
health - current health status (numeric: from 1 - very bad to 5 - very good)<br>
absences - number of school absences (numeric: from 0 to 93)<br>
These grades are related with the course subject, Math or Portuguese:<br>
<br>
G1 - first period grade (numeric: from 0 to 20)<br>
G2 - second period grade (numeric: from 0 to 20)<br>
G3 - final grade (numeric: from 0 to 20, output target)<br>
Additional note: there are several (382) students that belong to both datasets .<br>
These students can be identified by searching for identical attributes<br>
that characterize each student, as shown in the annexed R file.<br>
<br>
Source Information<br>
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7.<br>
<br>
Fabio Pagnotta, Hossain Mohammad Amran. <br>
Email:fabio.pagnotta@studenti.unicam.it, mohammadamra.hossain '@' studenti.unicam.it <br>
University Of Camerino<br>
<br>
https://archive.ics.uci.edu/ml/datasets/STUDENT+ALCOHOL+CONSUMPTION<br>
