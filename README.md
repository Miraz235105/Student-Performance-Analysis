# Analysis of Factors Influencing Student Academic Performance
This data tracks students' demographics, family, school, and academic performance. The analysis examines how factors like study habits, support, health, and attendance influence grades and highlights key patterns for improving outcomes.

<img width="1341" height="594" alt="Dashboard of Students&#39; Academic Perfomance Analysis" src="https://github.com/user-attachments/assets/65268033-9ef6-4c1b-a2af-f7a6222e9a6f" />

### Introduction
This project analyzes student academic performance data to identify key factors influencing final grades. The aim is to uncover patterns that explain academic success or poor performance and provide insights to support better educational decision-making. The analysis was conducted using Microsoft Excel, utilizing data cleaning, pivot tables, charts, and descriptive analysis techniques.

### Story of Data
This section describes the student academic performance dataset used in the analysis. The data was sourced from a publicly available Kaggle dataset and compiled from school academic records and structured questionnaires completed by students and their guardians. Each row represents an individual student, while the columns capture demographic details, family background, academic history, lifestyle factors, attendance records, and grades (G1, G2, and G3). Key features such as study time, past failures, parental education, health status, and absences help explain variations in student performance, with the final grade (G3) serving as the primary outcome measure. Additional engineered variables, including Average Grade and Grade Improvement, were created to enhance the analysis. No significant data limitations were identified.

### Data Splitting and Preprocessing
The student performance dataset was reviewed to ensure data quality and consistency, with no duplicates, invalid entries, or missing values identified. Numerical codes used for categorical variables were recoded into meaningful labels to improve readability and interpretation. Additional variables, including Average Grade and Grade Improvement, were created to provide a clearer view of overall academic performance and student progress over time. Independent variables capture students' demographic characteristics, family background, school support, and lifestyle factors, while dependent variables include academic grades (G1, G2, and final grade G3). Situated within the education sector, this analysis offers valuable insights into the factors influencing student achievement. Key stakeholders include teachers, school administrators, academic counselors, and education policymakers. The findings can support early interventions, better resource allocation, and strategies aimed at improving academic outcomes and student retention.

### Pre-Analysis
In the pre-analysis phase, an initial exploration of the student performance dataset revealed key trends influencing academic outcomes. Students with higher study time, fewer past failures, and lower absences generally achieved better final grades, while those receiving school or family support showed improved performance. Early observations also suggested potential relationships between parental education and student achievement, as well as a negative link between higher alcohol consumption and academic performance. Overall, study habits, attendance, family background, and lifestyle behaviors emerged as the most influential factors to be examined further in the detailed analysis of student academic performance.

### In-Analysis
**Key Patterns Observed:**
- Students with higher study time generally achieve better final grades, though results vary by age group and school.
- Lower absences and fewer past failures are consistently associated with stronger academic performance.
- Family and school support appear to positively influence grades, especially for students with prior academic challenges.
- Higher alcohol consumption levels tend to align with lower academic performance, suggesting a potential negative impact.
- While most students with high absences perform poorly, a small group maintains good grades despite frequent absences, indicating other influencing factors.

**Preliminary Recommendations:**
- Encourage effective study habits through structured study programs and time-management support.
- Strengthen family and school support systems, particularly for students with past failures or declining performance.
- Monitor attendance closely and introduce early interventions for students with rising absence levels.
- Promote healthy lifestyle choices through student awareness and counseling programs.
- Conduct deeper statistical analysis to validate observed patterns and better target academic interventions.

### Post-Analysis and Insights
**Key Findings:** Based on the completed analysis, several significant insights emerged:
- Academic performance is highest and most concentrated among students aged 16–17, while contributions drop sharply at older ages, likely due to fewer students rather than lower ability.
- Gabriel Pereira has more students overall, and female students outnumber males in both schools, with the gender gap more pronounced at Mousinho da Silveira.
- Most students improved their grades, with over half showing improvement, while fewer students experienced no change or a decline.
- Students with no past failures have the lowest average absences, while those with previous failures, especially combined with poorer health, tend to miss school more, showing that failures and health status are linked to higher absenteeism.
- Most students are from urban areas, with urban students making up the clear majority of the dataset compared to rural students.
- Most students chose their school because of the course offered, with home location and school reputation being secondary reasons.
- Participation in extracurricular activities shows little to no difference in grade improvement, as students with and without activities have nearly identical improvement, no-change, and decline counts.
- Overall, students' average grades steadily improve over time, rising from 11.40 in G1 to 11.57 in G2 and 11.91 in G3.

**Comparison with Initial Findings:**
- Initial expectations that higher study time, regular attendance, strong family or school support, and higher parental education lead to better academic performance were confirmed.
- Some counter-intuitive patterns emerged, as several students with high absences still achieved good grades, and participation in extracurricular activities showed minimal impact on grade improvement.
- Overall, academic success is most strongly driven by study habits, attendance, family support, and parental background, highlighting the need for targeted monitoring and support for at-risk students.

### Data Visualizations & Charts
Visual representations were created in Microsoft Excel to simplify complex data relationships and highlight key patterns related to Student Performance. The Area Chart showed the Progression of Grade Performance, the Clustered Column Chart showed the Gender Population by School and Impact of Parental Status on Grade Improvement, the Stacked Column Chart showed the Grade Improvement by Activities Participation, the Doughnut Chart showed Student Distribution by Location, the Pie Chart showed the Distribution of Students by School Selection Reason, and the Histogram showed the Age Distribution of Average Grade.
The dashboard provides a comprehensive overview of how demographic, family, school, and lifestyle factors influence students' academic performance. It allows stakeholders to quickly identify high-performing and at-risk student groups, observe performance patterns, and understand the key drivers shaping academic outcomes across the dataset.

### Recommendations
**Actionable Insights:**
- Promote structured study schedules and time management to help students improve grades, particularly for those showing minimal grade improvement.
- Provide targeted interventions for students with multiple past failures, high absences, or poor health, as they are more likely to struggle academically.
- Collaborate with families and teachers to offer consistent guidance and academic assistance, especially for students from less supportive backgrounds.
- Implement attendance monitoring and early warning systems to address absenteeism before it impacts performance.

**Optimizations / Business Decisions:**
- Focus academic support programs and counseling services on the age groups and students showing the highest risk (e.g., multiple failures, high absences).
- Adjust teaching methods and study materials to account for varying student backgrounds, parental education, and learning needs.
- Use student performance dashboards to continuously track improvements, enabling proactive measures rather than reactive support.

### Conclusion
The analysis shows that academic performance is strongest among students aged 16-17, with study time, attendance, parental education, and family or school support emerging as the most influential factors. Higher absences, past failures, and poor health are closely linked to lower performance, highlighting clear at-risk groups. Limitations include uneven age-group representation, lack of socio-economic and instructional quality data, and the descriptive nature of the analysis. Future research should incorporate broader contextual variables, apply predictive models to identify struggling students early, and use longitudinal data to better track performance trends over time.

### References
Data Source: https://www.kaggle.com/datasets/larsen0966/student-performance-data-set
Tools Used: Microsoft Excel (Pivot Tables, Charts, Dashboard).
External Resources: Sources include research and articles on student performance, academic achievement factors, school support systems, and lifestyle influences, as well as tutorials and documentation for Excel analytical functions.

**Appendices:** Additional charts, tables, and raw data snapshots
