CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Datasets Analyzed + Citation of Outside Research
 * Data Dictionary 
 * Problem Statement
 * brief summary of your analysis
 * Conclusion + Suggestions
 * FAQ
 * Project Creator's Basic Info

# Introduction:
The SAT and ACT are standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.

The SAT has two sections of the test: Evidence-Based Reading and Writing and Math ([*source*](https://www.princetonreview.com/college/sat-sections)). The ACT has 4 sections: English, Mathematics, Reading, and Science, with an additional optional writing section ([*source*](https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html)). They have different score ranges, which you can read more about on their websites or additional outside sources (a quick Google search will help you understand the scores for each test):
* [SAT](https://collegereadiness.collegeboard.org/sat)
* [ACT](https://www.act.org/content/act/en.html)

Standardized tests have long been a controversial topic for students, administrators, and legislators. Since the 1940's, an increasing number of colleges have been using scores from sudents' performances on tests like the SAT and the ACT as a measure for college readiness and aptitude ([*source*](https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/)). Supporters of these tests argue that these scores can be used as an objective measure to determine college admittance. Opponents of these tests claim that these tests are not accurate measures of students potential or ability and serve as an inequitable barrier to entry.


---

### The datasets used and analyzed:

* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State ([source](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows))
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))
* [`sat_2019_by_intended_college_major.csv`](./data/sat_2019_by_intended_college_major.csv): 2019 SAT Scores by Intended College Major ([source](https://reports.collegeboard.org/pdf/2019-total-group-sat-suite-assessments-annual-report.pdf))


### The outside research used and analyzed:

Source name: enrollment-of-undergraduate-students-in-2-year-colleges-us-1990-2020.xlsx (from US Census Bureau: NCES © Statista 2022)

Source name: united-states---birth-rate-1990-2020.xlsx (from US Department of Health and Human Services: NCES © Statista 1990-2020)

Source name: 10 Industries AL will disrupt the most by 2030 (Source from SpiceWork)

Source name: Analysis of US Graduate Schools Admission + Prediction Model.ipynb (By me 2 years ago)

** My analysis include:
<br>The overall SAT/ACT performance for 50 states
<br>The statistics for 2017-2019 SAT scores
<br>The statistics for 2019 ACT scores
<br>The correlation between the scores and the participation rate
<br>The most popular intended majors / least preferred intended majors

---

## Data Dictionary 

| Column Name | Data Type | Description |
| --- | --- | --- |
| State_(2017-2019) | Object | 50 states across USA |
| Participation_(2017-2019) | Float | The Participation rate Across 50 states  |
| ebrw_2017-2019 | Integer | The SAT Evidence-Based Reading and Writing Score from 2017-2019 Across 50 states |
| math_(2017-2019) | Integer | The SAT Math Score from 2017-2019 Across 50 states  |
| total_(2017-2019) | Integer | The SAT Math Score from 2017-2019 Across 50 states |
| intendedcollegemajor | Integer | The Names of the Intended College Major  |
| testtakers_2019 | float64 | he Raw Number of People who have taken the SAT and delcared that particular Major  |
| percent | float64 | The Percentage of people who have taken the SAT and delcared that particular Major  |
| total_score_2019 | float64 | The Percentage of people who have taken the SAT and delcared that particular Major  |
| readingwriting_2019 | Integer | The Average Score of Students on Reading and Writing 2019 SAT tests|
| math_score_2019 | Integer |The Average Score of Students on 2019 Math SAT tests  |
| act_participation_2019 | float64 | The Participation Rate on 2019 ACT tests|
| composite | float64 |The Overall Score of ACT | 


---

### The problem statement: <font color='red'> Which state(s) and learning field(s) should the Department of Education put more resources in to make the country/students stay competitive overall ?</font>

Particularly in terms of **(1) Participation Rate (2) Overall SAT/ACT performance and (3) Future Curriculum Development**

---

### brief summary of your analysis:
 In 2019-20, 11 states used SAT School Day to measure student achievement under the Every Student Succeeds Act. As an employee of the College Board, my aim of this project is to recommend where money is best spent to improve (1) Participation Rate (2) Overall SAT/ACT performance and (3) Future Curriculum Development. 
 
 Apart from the original datasets, I will also use the outside research from US Census Bureau to make recommendations about how the College Board might work to increase the participation rate in a South Dakota specifically, and provide fundings in some popular learning fields - such as 'Health Professions', 'Business' and 'Engineering', while 'libarianship's resources should either be reallocated or revamped with AI, so as to make US's education stay competitive. 
 
 ---

### Conclusions and Recommendations:
Conclusions:
<br>(1) The higher score that the states tend to have, the lower participation rate that they exhibtied.
<br>(2) South Dakota has a lower participation rate in both SAT and ACT. 
<br>(3) Librarianship, precision production and transportation are the least preferred majors. 
<br>(4) Medical, business and engineering programs are popular among students.
<br>(5) The number of students going into post-secondary programs are declining. 
<br>(6) The birth rate is decreasing.

To tackle the addressed conclusions - my suggestions are **3-folded**:

Suggestions for **Schools**:
1. To improve states with lower test performamces: Offer free, compulsory SAT/ACT Preparatory Test Day:
By providing free test days, students can get familiarized with both SAT/ACT and see which test suits them the most, and better prepared for the test. 
According to research from the College Board, 63% of students increase their SAT test score when taking the exam twice.

2. Mandatory SAT/ACT Graduation Policies: Improve Participation Rate:
Extend the mandate to not only 11 states, but all other states (especially South Dakota), where students will require to complete SAT/ACT to graduate high school.


3. Empower students, who are NOT interested in pursuing traditional college path, with college alternatives:
Provide vocational training schools, skill-based study paths, rather than restricting students to merely go for academia route.

Suggestions for **Colleges**:
1. Adopt holistic college admission strategy
Apart from solely considering SAT/ACT, they should look at the candidate as a whole, including their
<br>a. High school grade point average (GPA)
<br>b. High school course load and curriculum
<br>c. Participation in extracurricular activities
<br>d. Recommendation letters (Unquantified qualities)
<br>e. Application essays and personal statements (Unquantified qualities)

Suggestions for **future Curriculum Development**:
1. Revamp the unpopular programs such as librarianship, precision production and transportation with AI elements.
2. Add more fundings to enhance the current medical, business and engineering programs and import high quality teaching with an additional focus on AI.
---

### FAQ:
Q. Where can I find your detailed breakdown of graphs and plots?
<br>A. From the Data Analysis Code.ipynb file.

Q. Where can I find a copy of your presentation slides?
<br>A. It's in this folder, named PDF slides.pdf.

---

 ### Project Creator's Basic Info
 Name: Cathy Kam
 E-mail address: cathykam2006@gmail.com
 


