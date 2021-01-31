# PyBer Ride Share Analysis
## Overview and Scope of the Analysis
At the request of the PyBer companies CEO, we were to conduct an analysis of ride-sharing data for a given region. The main focus of this analysis was to look at and compare different key performance indicators for the rural, suburban and urban areas. The KPIs that we looked are were Total Fare by city type per week, total rides per area, avg fare per ride and average fare per driver per a given timeframe.
## Results
Following is a comparison of the original school district analysis to the revised analysis once the 9th grade scores from Thomas High School have been removed.

  ![Ride Share Summary Data](/analysis/Rideshare_summary.png)
  >Key metrics for the different city types.
  
  ![Total Fares by City Type](/analysis/PyBer_fare_summary.png)
  >Total Fares by City Type
  
  - Overall, the removal of the scores changed the district summary very little. The only observed change is a .1% drop in the district math score.

- **How is the school summary affected?**

  ![Original Thomas High School Summary](/Resources/Original_ths.png)
  >Original Thomas High School Summary
  
  ![Revised Thomas High School Summary](/Resources/Revised_ths.png)
  >Revised Thomas High School Summary

    - When we look at the changes within Thomas High School, we again see some very small changes. The average ***math*** score **dropped .1%**, average ***reading*** score **increased .1%**. The overall passing percentages are essentially unchanged.
    
- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

  ![Original Top Five Schools](/Resources/Original_top_five.png)
  >Original Top Five Performing Schools

  ![Revised Top Five Schools.](/Resources/Revised_top_five.png)
  >Original Top Five Performing Schools

    - Looking at how THS changed in relationship to other schools we see that very little actually changed. THS is still the second top performing school.
    
- **How does replacing the ninth-grade scores affect the following:**

  - **Math and reading scores by grade**
  
    ![Original Thomas High School Math Scores.](/Resources/Original_math_grade_ths.png)
    >Original Thomas High School Math Scores
  
    ![Revised School District Analysis.](/Resources/Revised_math_grade_ths.png)
    >Revised Thomas High School Math Scores 
    
    ![Original Thomas High School Reading Scores.](/Resources/Original_reading_grade_ths.png)
    >Original Thomas High School Reading Scores
  
    ![Revised Thomas High School Reading Scores.](/Resources/Revised_reading_ths.png)
    >Revised Thomas High School Reading Scores
  
    - The only changes in the Math and Reading scores in THS are obviously that the 9th grade scores have been removed. All other grades remain unchanged.
      
  - **Scores by school spending**
  
    ![Original Scores by School Spending](/Resources/Original_school_spending.png)
    >Orginal Scores by School Spending 
  
    ![Revised Scores by School Spending](/Resources/Revised_school_spending.png)
    >Revised Scores by School Spending
  
    - Scores by school spending are unchanged between the original and the revised analyses.
    
  - **Scores by school size**
  
    ![Original Scores by School Size.](/Resources/Original_school_size.png)
    >Original Scores by School Size
  
    ![Revised Scores by School Size.](/Resources/Revised_school_size.png)
    >Revised Scores by School Size
    
    - Scores by school size are unchanged between the original and the revised analyses.
  
  - **Scores by school type**
  
    ![Original Scores by School Type.](/Resources/Original_school_type.png)
    >Original Scores by School Type

    ![Revised Scores by School Type.](/Resources/Revised_school_type.png)
    >Revised Scores by School Type
      
    - Scores by school type are also unchanged between the original and the revised analyses.

## Summary

Below are screen shots showing how the THS numbers changed during the anaylsis process when the NaNs were added to the the 9th grade reading and math scores.

![Original THS Summary](/Resources/Original_ths.png)
>Original Thomas High School Scores

![THS after NaNs inserted](/Resources/ths_withnans.png)
>Thomas High School Scores when the analysis was run with the NaNs in the DataFrames.

We see that a number of the metrics changed:
1. Significant drop by about 26% in the percent of students with passing math scores.
2. Significant drop by about 27% in the percent of students with passing reading scores.
3. These numbers both impacted the overall passing percentage with a decrease of about 25%.
4. These numbers were then corrected in the script when the number of 9th grades at Thomas High School where removed from the THS school count, percentages where recalculated and then inserted into the school summary DataFrame.
