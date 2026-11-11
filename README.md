# Student Performance Analytics Dashboard

## Project Overview
This project presents an interactive Student Performance Analytics Dashboard developed using Tableau. It explores students' academic performance across mathematics, reading, and writing, highlighting patterns associated with gender, test preparation, parental education, and lunch type.

## Tools & Technologies
- Tableau – Data visualization and interactive dashboard development
- Microsoft Excel – Dataset inspection
- CSV – Dataset format

## Dataset
The project uses the Students Performance in Exams dataset containing 1,000 student records and 8 original attributes.

**Key attributes:**
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Visualizations

The dashboard includes five visualizations:

1. **Average Scores by Subject** – Compares average mathematics, reading, and writing scores.
2. **Performance by Gender** – Examines average subject scores across genders.
3. **Test Preparation Analysis** – Compares scores of students who completed test preparation with those who did not.
4. **Parental Education Analysis** – Explores academic performance across parental education levels.
5. **Lunch Type Analysis** – Compares student scores across standard and free/reduced lunch categories.

## Interactive Features
- Gender filter
- Test preparation course filter
- Lunch type filter
- Interactive dashboard visualizations

## Key Insights
- Reading has the highest overall average score among the three subjects.
- Students who completed test preparation have higher average scores across all three subjects.
- Female students have higher average reading and writing scores, while male students have a higher average mathematics score in this dataset.
- Students whose parents have a master's degree show the highest overall average score among the parental education groups.
- Students receiving standard lunch have higher average scores across all three subjects.

These findings describe associations in the dataset and do not establish causation.

## Project Structure

```text
CodeAlpha_DataVisualization/
├── dashboard/
│   ├── Student_Performance_Dashboard.twb
│   └── Student_Performance_Dashboard.png
├── data/
│   └── StudentsPerformance.csv
└── README.md
```

## How to Run
1. Clone or download this repository.
2. Open the Tableau workbook (`Student_Performance_Dashboard.twb`) using Tableau Desktop.
3. If Tableau requests the data source, reconnect it to `data/StudentsPerformance.csv`.
4. Open the Student Performance Dashboard to explore the visualizations and filters.

## Conclusion
This project demonstrates how Tableau can transform raw academic data into meaningful visual insights through interactive charts and dashboards.

---
**Created as part of the CodeAlpha Data Analytics Internship – Task 3.**