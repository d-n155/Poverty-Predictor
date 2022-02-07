### Possible features

- **Locale** (codes: 1 = large city, 2 = midsize city, 3 = urban fringe of large city, 4 = urban fringe of midsize city, 5 = large town, 6 = small town, 7 = rural)
- **Race percentages**
- **Student:teacher ratio**
- **Percentage of students with free/reduced lunches**


### Data Cleaning and Normalization

- Remove rows containing '†' and '-'
- **Locale:** text starts with code #, replace text with just # code designation
- **Race percentages:** Replace # of students of specific race with (# of students of race / total student population)
- **Student:teacher ratio:** Add column for student teacher ratio with (total student population / # of full-time teachers) and delete column for # of full-time teachers (for most recent years the ratio is its own column already)
- **Percentage of students with free/reduced lunches:** replace # of students with free/reduced lunches with percentage (divide by total student population)

### Feature Selection 


### Modeling


### Model Selection

