# School_District_Analysis

## School District Analysis Overview
After review by the school board, data regarding math and reading grades for Thomas High School 9th graders were deemed to have been altered.  Due to the this academic dishonesty, and without knowing the full extent regarding which grades have been altered, the request was made to replace this data with NaNs.  By replacing all of the data in question, the school board will be in compliance with state-testing standards.

### Resources
- Data Source:  [students_complete](Resources/students_complete.csv) 
- Data Source:  [schools_complete](Resources/schools_complete.csv)
- Software:  Python 3.8.8, Visual Studio Code, 1.58.2, Jupyter Notebook

## Results
The results of the analysis are as follows:

- District Summary:  No discernible change [district_summary](Resources/district_summary.png)
- School Summary:  The only impact to the school summary was in regards to Thomas High Schools data [school_summary](Resources/school_summary.png)
- Thomas High Schools Performance:  Percent Passing reading scores dropped by nearly 30%  [thomas_summary](Resources/thomas_summary.png)
- Math scores by grade did not change but reading scores for the 9th grade were impacted as the Thomas High School 9th grade scores were removed

## Summary
In summary, the greatest impact was to the data for Thomas High School, specifically relating to the reading scores as the 9th grade scores were replaced.  This action showed a significant drop in the percent passing reading scores for THS.  Scores, when aggregated by grade where also affected but only the 9th grade scores.
