# School_District_Analysis

## Overview of the school district analysis: 
The school board had recently been notified that students_complete.csv file shows evidence of academic dishonesty. Although the extent of academic dishonesty has not been uncovered, they are specifically concerned about the math and reading scores for Thomas High School ninth graders. They had asked Maria's help to withhold state-testing standards for Thomas High School ninth graders. Maria had asked me to replace math and reading scores for Thomas High School ninth graders with NaNs and repeat the school district analysis allover again.

## Results: 

### District Summary - Old vs. Revised
The images below show the slight drop in average math scores and passing percentages on a district level when I replaced Thomas High School ninth graders math and reading scores with NaNs.

#### District Summary - before revision
![District_summary_old](https://user-images.githubusercontent.com/104685001/171088039-2162be4c-3d01-4868-9c5a-0b50514b0adb.png)


#### District Summary - after revision
![District_summary_revised](https://user-images.githubusercontent.com/104685001/171088057-cab72318-3dc2-49e0-92a0-7566eaf0e558.png)





_________________________________________________

### School Summary - Old vs. Revised vs. Revised and replaced
The images below show that Thomas High School passing percentages dropped to 60s compared to other high performing schools in their 90s. However when I excluded the number of 9th graders to calculate the passing percentages, Thomas High School performance improved significantly in line with other high performing peers.


#### School Summary - before revision
![School_summary_old](https://user-images.githubusercontent.com/104685001/171088077-89af39ae-a608-4758-ba60-2cf272cc2164.png)


#### School Summary - after revision
![School_summary_revised](https://user-images.githubusercontent.com/104685001/171088084-5d30f2ca-4459-43d3-a55e-6a6f48b4270f.png)


#### School Summary - after revision and replacement
![School_summary_revised_replaced](https://user-images.githubusercontent.com/104685001/171088124-9e3d6338-2b3a-4eaf-8686-59981c141fd1.png)





________________________________________________

### THS' Performance - Old vs. Revised
The images below show the significantly low passing percentages from Thomas High School when I just replaced Thomas High School ninth graders math and reading scores with NaNs. However when I excluded the number of 9th graders to calculate the passing percentages, it improved Thomas High School results significantly.

#### THS' Performance vs. Other schools - before revision
![THS_School_summary_old](https://user-images.githubusercontent.com/104685001/171088151-1411197b-0570-4ae2-a375-6cb710cd678b.png)


#### THS' Performance vs. Other schools - after revision
![THS_School_summary_revised](https://user-images.githubusercontent.com/104685001/171088177-7f12d4a9-dcdf-4f18-bec7-2049a14d59c2.png)


#### THS' Performance vs. Other schools - after revision and replacement
![THS_School_summary_revised_replaced](https://user-images.githubusercontent.com/104685001/171090703-113a90b7-e2d9-4bb3-a56e-b974aee79a80.png)


________________________________________________

### Math and Reading Scores by Grade - Old vs. Revised
The images below show that only THS 9th grades math and reading scores have been replaced. Every other value in the dataframe stays the same.

#### Math and Reading Scores by Grade - before revision
![Scores_by_grade_old](https://user-images.githubusercontent.com/104685001/171097649-6c6fe373-9b02-4bb2-9347-ddd44f046641.png)



#### Math and Reading Scores by Grade - after revision
![Scores_by_grade_revised](https://user-images.githubusercontent.com/104685001/171097658-ccd3e3b8-9058-4c94-bdcb-14c5eb0a8c83.png)






________________________________________________

### Scores by School Spending - Old vs. Revised
The images below show that the revision only slightly changed the average reading score in <$585 and $586-630 bins and % Passing Math in $631-645 bin.

#### Scores by School Spending - before revision
![Scores_by_spending_old](https://user-images.githubusercontent.com/104685001/171088283-a6289c14-f0e8-429c-9687-be53dde023c1.png)


#### Scores by School Spending - after revision
![Scores_by_spending_revised](https://user-images.githubusercontent.com/104685001/171098104-d3638a39-09b3-4634-9048-f92abeb99ea4.png)





________________________________________________

### Scores by School Size - Old vs. Revised
The images below show that the revision only slightly changed the % Passing reading in medium sized schools.

#### Scores by School Size - before revision
![Scores_by_size_old](https://user-images.githubusercontent.com/104685001/171088314-f677af6c-4e6e-421b-97ba-ca7fb4c39969.png)


#### Scores by School Size - after revision
![Scores_by_size_revised](https://user-images.githubusercontent.com/104685001/171088321-f7afe7d3-3a0e-4f1b-880b-28eb47fee95a.png)





________________________________________________

### Scores by School Type - Old vs. Revised
The images below show that the revision only slightly changed the Average Math Score in District schools and % Passing Reading in Charter schools.

#### Scores by School Type - before revision
![Scores_by_type_old](https://user-images.githubusercontent.com/104685001/171088368-9b1ee26c-a839-439f-aa1c-31cae1ee3ae2.png)


#### Scores by School Type - after revision
![Scores_by_type_revised](https://user-images.githubusercontent.com/104685001/171088382-0d039379-dac2-4837-b954-8e42d9bf39ef.png)



________________________________________________


## Summary: 
* Slight drop in average math scores and passing percentages on a district level when I replaced Thomas High School ninth graders math and reading scores with NaNs.
* Thomas High School passing percentages dropped to 60s compared to other high performing schools in their 90s when I just changed ninth graders math and reading scores with NaNs. However when I excluded the number of 9th graders to calculate the passing percentages, Thomas High School performance improved significantly in line with other high performing peers.
* The revision only slightly changed the average reading score in <$585 and $586-630 bins and % Passing Math in $631-645 bin.
* The revision only slightly changed the % Passing reading in medium sized schools.
