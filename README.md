# Student Motivation Project

## Definition of features
| Column                 | Description                                                                                                                                                                 |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `student_id`           | Unique identifier for each student.                                                                                                                                         |
| `platform`             | The platform from which the current record was generated.                                                                                                                   |
| `subject`              | Course subject the student is enrolled in. Values include: `MATH`, `ENGL`, `PHYS`, `CHEM`, `CS`, `CSAdv` (the latter represents an advanced-level computer science course). |
| `required`             | Indicates whether the course is required for the student’s program: `0` = elective, `1` = required.                                                                         |
| `activity_time_level`  | Categorical label (1–3) indicating the student’s activity time in this course relative to classmates. `3` represents the highest activity time.                             |
| `participation_level`  | Categorical label (1–3) indicating the student’s participation level (e.g., discussions, submissions) relative to peers. `3` indicates the highest participation.           |
| `page_views_level`     | Categorical label (1–3) indicating how frequently the student viewed course materials compared to peers. `3` indicates the most frequent views.                             |
| `assignment_on_time`   | A float between 0 and 1 representing the proportion of assignments submitted on time.                                                                                       |
| `failed`               | Binary flag indicating course outcome: `1` = student failed the course, `0` = passed.                                                                                       |
| `motivation_statement` | Free-text response in which students explain their reasons for enrolling in the course, such as degree requirements, career goals, or personal interest.                    |
| `expectancy`           | Categorical label reflecting confidence in course success: `1` = high confidence, `0` = low confidence, `null` = not mentioned.                                             |
| `utility_value`        | Boolean value: `1` = utility value (e.g., career relevance) was mentioned, `0` = not mentioned.                                                                             |
| `intrinsic_value`      | Boolean value: `1` = intrinsic value (e.g., enjoyment or interest) was mentioned, `0` = not mentioned.                                                                      |
| `imposed_value`        | Boolean value: `1` = imposed value (e.g., external pressure or requirement) was mentioned, `0` = not mentioned.                                                             |
| `cost`                 | Boolean value: `1` = cost (e.g., effort, stress, opportunity cost) was mentioned, `0` = not mentioned.                                                                      |
