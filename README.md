# Stack-Overflow-devs-survey-
End to End Data analytics project on StackOverflow developer survey over last 4yrs.   

## Important links
* [Blog](https://dvboi.medium.com/portfolio-project-2-last-4yrs-stackoverflow-survey-analysis-53a250e9578f)
* [Tableau Dashboard](https://public.tableau.com/views/StackOverFlowAnalysisLast4Yrs/Story?:language=en-US&:display_count=n&:origin=viz_share_link)     

## Prerequisite packages and software
* Python
* Pandas,Numpy,Seaborn,Statsmodels,scipy,matplotlib,csv
* Tableau Public 

## Data Collection  
* Collected Last 4yrs of StackOverflow data and combined them from [here](https://www.kaggle.com/phuchuynguyen/datarelated-developers-survey-by-stack-overflow?select=survey_final.csv)      

## Data Cleaning and Preparation   
* Made data more stable by cleaning and transforming values wherever needed.
* Missing value imputation for data was done wherever needed. For example, for salary, as it was right skewed 'Group median Imputation' was performed on that data, grouping by years.      

## Exploratory Data Analysis     
* Analyzed Trends, distributions in the data for various programming languages & databases over the last 4yrs.
* Performed Descriptive and Inferential statistic on data like building 95% CI's and z-tests for hypothesis after transforming data.
* Answered a lot of questions like employment type of people, their education level, world's contribution on stackoverflow and impact of these factors on Salary.
* All Visuals/reports are published in a free cloud environment (Tableau Public) so that anyone/everyone can carry on their own analysis, a few visuals are --
    
    ![Avg. Salary by Major](https://github.com/Dvboi/Stack-Overflow-devs-survey-/blob/master/viz_snap/i1.png)     
        
     ![Tool Desire Vs Worked_With](https://github.com/Dvboi/Stack-Overflow-devs-survey-/blob/master/viz_snap/i2.png)    
     
     ![World Contribution](https://github.com/Dvboi/Stack-Overflow-devs-survey-/blob/master/viz_snap/i3.png)    
     
     ![Bootstrapped Salary](https://github.com/Dvboi/Stack-Overflow-devs-survey-/blob/master/viz_snap/i4.png)     
     
     
     
     


