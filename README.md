# 🎓 EXPECTATION DECIDER

## Integrated Probability Analysis Report

**Project Title:** Expectation Decider
**Project Type:** Probability & Statistical Analysis
**Dataset Size:** 200 Students
**Tools Used:** Python, Pandas, NumPy, Matplotlib, SciPy, Matplotlib-Venn

## 📌 Project Overview

The **Expectation Decider** project analyzes the probability patterns and academic performance of **200 students**.

The analysis focuses on different factors that may be associated with student performance, including:

* 📚 Study Hours
* 📊 Attendance Percentage
* 👥 Group Discussion Participation
* 📝 Previous Test Scores
* 🎯 Final Examination Result

The project applies different probability and statistical techniques to understand student performance and estimate the likelihood of academic success.

## 🎯 Project Objectives

The main objectives of this project are:

1. Understand the basic concepts of Probability.
2. Calculate empirical and theoretical probabilities.
3. Define and analyze random variables.
4. Construct a probability distribution.
5. Calculate the mean and variance of a random variable.
6. Analyze events using a Venn Diagram.
7. Create a contingency table.
8. Calculate joint, marginal, and conditional probabilities.
9. Determine whether events are independent or dependent.
10. Check whether events are mutually exclusive.
11. Apply Bayes' Theorem to student performance data.
12. Draw meaningful conclusions from the analysis.

## 📂 Dataset Description

The dataset contains **200 student records** with the following variables:

| Column             | Description                                           |
| ------------------ | ----------------------------------------------------- |
| `study_hours`      | Number of hours studied per week                      |
| `attendance`       | Student attendance percentage                         |
| `group_discussion` | Whether the student participated in group discussions |
| `previous_test`    | Previous test score                                   |
| `final_exam_pass`  | Final examination result: Pass/Fail                   |

---

## 🛠️ Technologies & Libraries Used

The project was developed using Python and the following libraries:

* **Pandas** – Data loading, manipulation and analysis
* **NumPy** – Numerical calculations
* **Matplotlib** – Data visualization
* **SciPy** – Statistical calculations
* **Math** – Combination calculations
* **Matplotlib-Venn** – Venn diagram visualization
* 
## 🔬 Analysis Performed

### 1. Probability

Probability measures how likely an event is to occur.

In this project, examples of events include:

* A randomly selected student passes the final exam.
* A student studies more than 10 hours per week.
* A student has attendance above 80%.

---

### 2. Empirical Probability

The empirical probability of passing was calculated using the observed dataset.

* Total Students = **200**
* Students Passed = **120**

Therefore:

**P(Pass) = 120 / 200 = 0.60**

### Result

**Probability of Passing = 60%**

**Probability of Failing = 40%**

### 3. Theoretical Probability

A theoretical probability was calculated for selecting **3 students** from the population.

The random variable:

> **X = Number of students who pass out of 3 randomly selected students**

The Hypergeometric Distribution was used because students were selected from a finite population containing known numbers of passing and failing students.

For example:

**P(X = 2) = 43.49%**

## 📊 Random Variable & Probability Distribution

The random variable **X** can take the following values:

**X = 0, 1, 2, 3**

A probability distribution was constructed using the Hypergeometric Distribution.

### Mean

The expected value of X is:

**E(X) = 1.8**

### Interpretation

When 3 students are randomly selected, the expected number of students who pass is **1.8**.

### Variance

The calculated variance is approximately:

**Variance = 0.7128**

The variance represents the spread of the number of passing students around the expected value.

## 🔵 Venn Diagram Analysis

Two events were analyzed:

### Set A

Students who study **more than 10 hours per week**.

### Set B

Students whose attendance is **above 80%**.

The analysis found:

* Students studying >10 hours = **73**
* Students with attendance >80% = **90**
* Students satisfying both conditions = **32**

The intersection:

**A ∩ B = 32 students**

shows the number of students who both study more than 10 hours and have attendance above 80%.

## 📋 Contingency Table

A contingency table was created to analyze the relationship between:

**Group Discussion Participation × Final Exam Result**

The results included:

* Group Discussion + Pass = **85 students**
* Group Discussion + Fail = **36 students**

This table was used for further probability calculations.

## 🔗 Joint Probability

Joint probability measures the probability that two events occur together.

In this project, the joint event was:

> Student participates in group discussion **AND** passes the final examination.

### Result

**Joint Probability = 42.50%**

## 📌 Marginal Probability

The marginal probability of passing was calculated independently of group discussion participation.

### Result

**P(Pass) = 60%**

## 🎯 Conditional Probability

The conditional probability calculated was:

> Probability of passing given that the student participated in group discussion.

### Result

**P(Pass | Group Discussion = Yes) = 70.25%**

This is higher than the overall passing probability of 60%.

Therefore, students who participated in group discussions had a higher observed probability of passing in this dataset.

## 🔍 Independent vs Dependent Events

The following probabilities were compared:

**P(Pass) = 60%**

**P(Pass | Group Discussion = Yes) = 70.25%**

Since these two probabilities are different, group discussion participation and passing the final exam are considered:

### ✅ Dependent Events

This means that, in this dataset, the observed passing probability changes when group discussion participation is conside-

## 🚫 Mutually Exclusive Events

Group discussion participation and passing are **not mutually exclusive**.

Reason:

Some students participated in group discussions and also passed the final examination.

There were:

**85 students**

who both participated in group discussions and passed.

Therefore:

### ❌ The events are NOT mutually exclusive.

## 🧮 Bayes' Theorem

Bayes' Theorem was applied using the historical probabilities provided in the project.

The variables were defined as:

* **P** = Student passes the exam
* **F** = Student fails the exam
* **H** = Student has high attendance (>80%)

Given:

* P(High Attendance | Pass) = 0.70
* P(High Attendance | Fail) = 0.40
* P(High Attendance) = 0.60

The calculations resulted in:

### P(Pass) = 66.67%

and:

### P(Pass | High Attendance) = 77.78%

This indicates that, according to the given historical probabilities, high attendance is associated with a higher probability of passing.

## 📈 Key Findings

| Measure                         |    Result |
| ------------------------------- | --------: |
| Total Students                  |       200 |
| Passed                          |       120 |
| Passing Probability             |       60% |
| Failed                          |        80 |
| Failing Probability             |       40% |
| Study >10 Hours                 |        73 |
| Attendance >80%                 |        90 |
| Both Conditions                 |        32 |
| Discussion + Pass               |        85 |
| Joint Probability               |    42.50% |
| Marginal Probability of Pass    |       60% |
| Conditional Probability         |    70.25% |
| Mean of Random Variable X       |       1.8 |
| Variance of X                   |    0.7128 |
| Bayes P(Pass | High Attendance) |    77.78% |
| Relationship                    | Dependent |

---

## 💡 Major Insights

1. **60% of students passed** the final examination.
2. **73 students** studied more than 10 hours per week.
3. **90 students** had attendance above 80%.
4. **32 students** satisfied both the study-hour and attendance conditions.
5. Students participating in group discussions had a **70.25% conditional probability of passing**, higher than the overall 60%.
6. Group discussion participation and passing were identified as **dependent events** in this dataset.
7. The two events were **not mutually exclusive** because students could participate in group discussions and pass at the same time.
8. The expected number of passing students among 3 randomly selected students was **1.8**.
9. The variance of the random variable was approximately **0.7128**.
10. Bayes' Theorem produced a **77.78% probability of passing given high attendance** based on the historical probabilities used in the project.

## 🏁 Overall Conclusion

The **Expectation Decider** project demonstrates how probability and statistical techniques can be applied to student performance data.

The analysis covered:

* Probability
* Empirical Probability
* Theoretical Probability
* Random Variables
* Probability Distribution
* Mean
* Variance
* Venn Diagram
* Contingency Table
* Joint Probability
* Marginal Probability
* Conditional Probability
* Independent and Dependent Events
* Mutually Exclusive Events
* Bayes' Theorem

The results suggest that **study habits, attendance, and group discussion participation are useful factors for understanding academic performance**.

Overall, this project provides a statistical foundation for an **"Expectation Decider" model**, which can be used to understand and estimate the likelihood of student success.

## 📁 Project Structure

```text
EXPECTATION-DECIDER/
│
├── EXPECTATION_DECIDER_IPYNB.ipynb
├── expectation_decider_students_200.csv
├── Expectation_Decider_Final_Summary.docx
└── README.md
```

---

## 👨‍💻 Project Author

**Sahil Pathan**

**Project:** Expectation Decider
**Domain:** Probability & Statistical Analysis
**Dataset:** Student Performance – 200 Records

---

## ⭐ Final Statement

> **Expectation Decider uses probability and statistical analysis to understand student performance and estimate the likelihood of academic success.**
