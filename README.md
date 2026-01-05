# Capstone-Healthcare
This a Capstone project using World Health related data

Scope is Identifying Most prevalence issue in USA and analyzing the same with data from other countries world wide, and connecting to individual habbit by country to see any pattern to establish the probable reason.
##	The research question intended to be answered (in one sentence, if possible)
      Identifying Most prevalence health issue in US and identifying correlation by country  world wide, and Identifying individual habit or any pattern to establish the probable reason.  
      Here is the URL for the Jupyter Notebook for this research 
      <a href="https://github.com/sganesan64/Capstone-Healthcare/blob/main/Capstone_WorlHealthcare.ipynb" target="_blank">Click Here</a>
      
##	Expected data source(s) (as either a link to existing data or a sentence describing where you will source the data from)
      Using World Health related data from
###	SOURCE 1: 
https://www.kaggle.com/datasets/prasad22/healthcare-dataset
       8,399,221 healthcare_dataset.csv
Columns : 
Name ,Age  ,Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital,
Insurance, Provider,  Billing Amount,  Room Number, Admission Type, Discharge Date,   Medication,  Test Results
###	SOURCE 2:
https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics
      134,395,536 Global Health Statistics.csv
Country , Year, Disease Name, Disease Category,  Prevalence Rate (%),  Incidence Rate (%),  Mortality Rate (%),  Age Group, Gender,  Population Affected , ... , Hospital Beds per 1000, 
Treatment Type,  Average Treatment Cost (USD), Availability of Vaccines/ Treatment,   Recovery Rate (%) DALYs, Improvement in 5 Years (%),  Per Capita Income (USD) , Education Index,  
Urbanization Rate (%) 
###	SOURCE 3:
https://www.kaggle.com/datasets/utkarshxy/who-worldhealth-statistics-2020-complete
39 Files 
## Author's View
### About Dataset
This dataset covers the most recent and updated health statistics of the world (countries recognized by WHO- all), BUT the data could not be directly used as the major indicator of various subtopics in the dataset was mixed so I have filtered based on various indicators and hence, divided into subcategories. I know so many datasets seem overwhelming, but I will be giving the various categories they belong to and what they represent so do not worry!)

## The techniques expected to be used in this analysis
Beginning with Scatter plots, proceeding with Decision tree to decide the features to focus on out of overwhelming list of columns and Data available.
Using Regression and/or Lasso techniques to train and test using the available data.
Using Sickit-learn libraries for identifying Scores, Predicting , splitting  and for Transforming given data with Preprocessing, feature extraction, Clustering, Model selection, Dimensionality Reduction and plotting to observe the results.

## The expected results Why this question is important
Healthcare is becoming costlier in the world and in US for more and more Population , Healthcare is becoming not affordable.
It is important Identifying most prevalence disease or Diagnosis and what it takes to heal the same.
Appendix Author’s Views:
### SOURCE 1:
https://www.kaggle.com/datasets/prasad22/healthcare-dataset
       8,399,221 healthcare_dataset.csv
Columns : 
Name ,Age  ,Gender, Blood Type, Medical Condition, Date of Admission, Doctor, Hospital,
Insurance, Provider,  Billing Amount,  Room Number, Admission Type, Discharge Date,   Medication,  Test Results

#### Author's View 
    Context:
This synthetic healthcare dataset has been created to serve as a valuable resource for data science, machine learning, and data analysis enthusiasts. It is designed to mimic real-world healthcare data, enabling users to practice, develop, and showcase their data manipulation and analysis skills in the context of the healthcare industry.
         Acknowledgments:
•	I acknowledge the importance of healthcare data privacy and security and emphasize that this dataset is entirely synthetic. It does not contain any real patient information or violate any privacy regulations.
•	I hope that this dataset contributes to the advancement of data science and healthcare analytics and inspires new ideas. Feel free to explore, analyze, and share your findings with the Kaggle community.


### SOURCE 2:
https://www.kaggle.com/datasets/malaiarasugraj/global-health-statistics
      134,395,536 Global Health Statistics.csv
Country , Year, Disease Name, Disease Category,  Prevalence Rate (%),  Incidence Rate (%),  Mortality Rate (%),  Age Group, Gender,  Population Affected , ... , Hospital Beds per 1000, 
Treatment Type,  Average Treatment Cost (USD), Availability of Vaccines/ Treatment,   Recovery Rate (%) DALYs, Improvement in 5 Years (%),  Per Capita Income (USD) , Education Index,  
Urbanization Rate (%) 

#### Author's View 
    
<B>About Dataset<\B>
This dataset provides comprehensive statistics on global health, focusing on various diseases, treatments, and outcomes. The data spans multiple countries and years, offering valuable insights for health research, epidemiology studies, and machine learning applications. The dataset includes information on the prevalence, incidence, and mortality rates of major diseases, as well as the effectiveness of treatments and healthcare infrastructure.
Dataset Use Cases:
This dataset can be used for:
•	Healthcare Policy Analysis: Understanding which diseases are most prevalent and which countries require more investment in healthcare infrastructure.
•	Epidemiological Studies: Studying the correlation between disease prevalence and socio-economic factors like income, education, and urbanization.
•	Machine Learning Models: Training predictive models to forecast disease trends, mortality rates, and treatment effectiveness based on historical data.
•	Global Health Research: Identifying regions that need targeted interventions or public health campaigns.


### SOURCE 3:
https://www.kaggle.com/datasets/utkarshxy/who-worldhealth-statistics-2020-complete
39 Files 
#### Author's View
<B>About Dataset<\B>
This dataset covers the most recent and updated health statistics of the world (countries recognized by WHO- all), BUT the data could not be directly used as the major indicator of various subtopics in the dataset was mixed so I have filtered based on various indicators and hence, divided into subcategories. I know so many datasets seem overwhelming, but I will be giving the various categories they belong to and what they represent so do not worry!)

08/06/2025  10:58 PM           476,371 30-70cancerChdEtc.csv
08/06/2025  10:58 PM           169,102 adolescentBirthRate.csv
08/06/2025  10:58 PM         1,060,465 airPollutionDeathRate.csv
08/06/2025  10:58 PM           264,347 alcoholSubstanceAbuse.csv
08/06/2025  10:58 PM           791,135 atLeastBasicSanitizationServices.csv
08/06/2025  10:58 PM           285,484 basicDrinkingWaterServices.csv
08/06/2025  10:58 PM           232,342 basicHandWashing.csv
08/06/2025  10:58 PM           121,833 birthAttendedBySkilledPersonal.csv
08/06/2025  10:58 PM           371,597 cleanFuelAndTech.csv
08/06/2025  10:58 PM           201,836 crudeSuicideRates.csv
08/06/2025  10:58 PM            17,051 dataAvailibilityForUhc.csv
08/06/2025  10:58 PM            96,587 dentists.csv
08/06/2025  10:58 PM           119,550 eliminateViolenceAgainstWomen.csv
08/06/2025  10:58 PM           172,711 HALElifeExpectancyAtBirth.csv
08/06/2025  10:58 PM             7,383 HALeWHOregionLifeExpectancyAtBirth.csv
08/06/2025  10:58 PM            22,124 hepatitusBsurfaceAntigen.csv
08/06/2025  10:58 PM           145,077 incedenceOfMalaria.csv
08/06/2025  10:58 PM           345,399 incedenceOfTuberculosis.csv
08/06/2025  10:58 PM         3,998,299 infantMortalityRate.csv
08/06/2025  10:58 PM           149,801 interventionAgianstNTDs.csv
08/06/2025  10:58 PM           139,870 lifeExpectancyAtBirth.csv
08/06/2025  10:58 PM           263,372 maternalMortalityRatio.csv
08/06/2025  10:58 PM           133,538 medicalDoctors.csv
08/06/2025  10:58 PM           295,606 mortalityRatePoisoning.csv
08/06/2025  10:58 PM            70,906 mortalityRateUnsafeWash.csv
08/06/2025  10:58 PM           855,594 neonatalMortalityRate.csv
08/06/2025  10:58 PM           230,302 newHivInfections.csv
08/06/2025  10:58 PM           179,202 nursingAndMidwife.csv
08/06/2025  10:58 PM             7,383 ofHaleInLifeExpectancy.csv
08/06/2025  10:58 PM            88,676 pharmacists.csv
08/06/2025  10:58 PM           286,751 population10SDG3.8.2.csv
08/06/2025  10:58 PM           308,736 population25SDG3.8.2.csv
08/06/2025  10:58 PM            16,876 reproductiveAgeWomen.csv
08/06/2025  10:58 PM            14,136 roadTrafficDeaths.csv
08/06/2025  10:58 PM           309,073 safelySanitization.csv
08/06/2025  10:58 PM           487,759 tobaccoAge15.csv
08/06/2025  10:58 PM            22,024 uhcCoverage.csv
08/06/2025  10:58 PM         3,669,778 under5MortalityRate.csv
08/06/2025  10:58 PM             4,758 WHOregionLifeExpectancyAtBirth.csv


