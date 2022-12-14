# School_District_Analysis

## Project Overview
The school board has supplied Maria with evidence of academic dishonesty, therefore, she has given us the task of upholding state-testing standards. We are to:
  1. Replace all mathh and reading scores for Thomas High School with NaNs.
  2. Repeat the school district analysis.
  3. Display the changes that affected the overall analysis.

## Resources
- Data Sources: students_complete.csv, schools_complete.csv
- Software: Anaconda3, Jupyter Notebook

## Results
### How is the district summary affected?
- Provided the in the image below, we can see that the score and percentage for each subject is passing, but the overall passing percentage is only 64.9. Due to the altered scores, the scores themselves have increased, but not the overall passing percentage.

![School_District_Summary](https://user-images.githubusercontent.com/110737061/189000780-5e01ed93-6ba6-4941-9532-2a8ddf095292.png)

### How is the school summary affected?
- Looking closely at the data frame provided below, we can see all 15 of the listed schools and their grades. We can tell  that the charter schools seem to be better academically as opposed to the district schools which seem to struggle in math; all except for Thomas High School, which also seems to be the only charter school with a struggling math grade. Because of this, it seems to be affecting the overall passing percentage.
    
![Per_School_Summary](https://user-images.githubusercontent.com/110737061/189002569-45247ed0-2ff2-4428-98e0-b355195347cf.png)

### How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
- We can see in our data frame that removing all of the ninth grade scores in reading and writing had no overall change in the rest of the schools performance relative to the other schools. They seem to perform just as well.

![Average_Math_Score](https://user-images.githubusercontent.com/110737061/189005755-884783a7-0d64-43bb-9bbd-5289b633720b.png)
![Average_Reading_Score](https://user-images.githubusercontent.com/110737061/189005635-06ccc4b9-464e-4dbc-9105-f461b018c05f.png)

### How does replacing the ninth-grade scores affect the following:
- Math and Reading Scores by Grade
- Scores by School Spending
- Scores by School Size
- Scores by School Type
  -Overall, replacing the ninth-grade scores does not really affect any of the things listed above. The math and reading scores for the other grades are unaffected, there isnt a lack of or increase in money for the school, the school size doesn't change, and the school type remains the same.
  - However, based off the school type, the district schools seem to have an overall lower performance when it comes to academics as opposed to charter schools. Seeing as how district schools are larger than charter schools, this may of some influence on the number of students that are passing and failing. It also seems like the district schools actually have a larger budget than the charter schools, yet still have a lesser academic score than other schools.

## Summary
In the end, the updated school district analysis saw no real change to a majority of the district, just primarily Thomas High School. We saw that the average math and reading scores increased for THS once replaced with NaNs, as well as an overall passing percentage increase for the school. We can also notice that THS is no longer a top five school.
