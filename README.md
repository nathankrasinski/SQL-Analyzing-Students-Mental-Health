# SQL-Analyzing-Students-Mental-Health
![Illustration of silhouetted heads](mentalhealth.jpg)

Does going to university in a different country affect your mental health? A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.

The study found that international students have a higher risk of mental health difficulties than the general population. Explore the `students` data using PostgreSQL to find out if this is true and see if the length of stay is a contributing factor.

Here is a data description of the fields you may find helpful. The full dataset is in one table with 50 fields and, according to the survey, 268 records. Each row is a student.

| Field Name    | Description                                      | 
| ------------- | ------------------------------------------------ |
| inter_dom     | Types of students                                |
| japanese_cate | Japanese language proficiency                    | 
| english_cate  | English language proficiency                     |
| academic      | Current academic level                           | 
| age           | Current age of student                           |
| stay          | Current length of stay in years                  |
| todep         | Total score of depression (PHQ-9 test)           |
| tosc          | Total score of social connectedness (SCS test)   |
| toas          | Total score of Acculturative Stress (ASISS test) |

Your task will be to do the following exploratory analysis:

- Count the number of all records, and all records per student type
- Filter the data to see how it differs between the student types
- Find the summary statistics of the diagnostic tests for all students
- Summarize the data for international students
- See if length of stay impacts the test scores

Please See notebook for SQL code
