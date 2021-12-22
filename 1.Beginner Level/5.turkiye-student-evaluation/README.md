# Turkiye Student Evaluation

## 1.Business Problem

### 1.1 Description
This dataset is based on an evaluation form filled out by students for different courses. It has different attributes including attendance, difficulty, score for each evaluation question, among others. This is an unsupervised learning problem. The dataset has 5820 rows and 33 columns.

### 1.2 Sources
https://archive.ics.uci.edu/ml/datasets/Turkiye+Student+Evaluation

## 2.Machine Learning Problem

### 2.1 Data
#### 2.1.1 Data Overviews
Contain one files 
* <b>turkiye-student-evaluation_generic.csv</b>-containing 5820 data points & 33 Features</br>

#### Attribute-information
* instr: Instructor's identifier; values taken from {1,2,3}</br>
* class: Course code (descriptor); values taken from {1-13} </br>
* repeat: Number of times the student is taking this course; values taken from {0,1,2,3,...}</br> 
* attendance: Code of the level of attendance; values from {0, 1, 2, 3, 4} </br>
* difficulty: Level of difficulty of the course as perceived by the student; values taken from {1,2,3,4,5} </br>
* Q1: The semester course content, teaching method and evaluation system were provided at the start. </br>
* Q2: The course aims and objectives were clearly stated at the beginning of the period. </br>
* Q3: The course was worth the amount of credit assigned to it. </br>
* Q4: The course was taught according to the syllabus announced on the first day of class. </br>
* Q5:	The class discussions, homework assignments, applications and studies were satisfactory. </br>
* Q6: The textbook and other courses resources were sufficient and up to date.	</br>
* Q7: The course allowed field work, applications, laboratory, discussion and other studies. </br>
* Q8: The quizzes, assignments, projects and exams contributed to helping the learning.	</br>
* Q9: I greatly enjoyed the class and was eager to actively participate during the lectures. </br>
* Q10: My initial expectations about the course were met at the end of the period or year. </br>
* Q11: The course was relevant and beneficial to my professional development. </br>
* Q12: The course helped me look at life and the world with a new perspective. </br>
* Q13: The Instructor's knowledge was relevant and up to date. </br>
* Q14: The Instructor came prepared for classes. </br>
* Q15: The Instructor taught in accordance with the announced lesson plan.</br> 
* Q16: The Instructor was committed to the course and was understandable. </br>
* Q17: The Instructor arrived on time for classes. </br>
* Q18: The Instructor has a smooth and easy to follow delivery/speech.</br> 
* Q19: The Instructor made effective use of class hours. </br>
* Q20: The Instructor explained the course and was eager to be helpful to students.</br> 
* Q21: The Instructor demonstrated a positive approach to students. </br>
* Q22: The Instructor was open and respectful of the views of students about the course. </br>
* Q23: The Instructor encouraged participation in the course. </br>
* Q24: The Instructor gave relevant homework assignments/projects, and helped/guided students.</br> 
* Q25: The Instructor responded to questions about the course inside and outside of the course. </br>
* Q26: The Instructor's evaluation system (midterm and final questions, projects, assignments, etc.) effectively measured the course objectives. </br>
* Q27: The Instructor provided solutions to exams and discussed them with students.</br> 
* Q28: The Instructor treated all students in a right and objective manner. </br>

### 2.2 Mapping the real-world problem to a Machine Learning Problem
#### 2.2.1 Type of Machine Learning Problem
Use classification and clustering techniques to deal with the data.
