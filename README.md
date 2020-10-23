# Mid-term-project
#### Authors: Nathanael Alemayehu and Ahmad Sayeb 
Lighthouse Labs mid-term project.


**Hello and Welcome!!!**

The aim of this project is to predict delays on flights from the first 7 days of 2020 (1st of January - 7th of January).   

## [Final Delay Predictions for first 7 days of 2020](final_predictions.csv)  

This repository consists of following files:

- **exploratory_analysis.ipynb**: this file contains 10 questions we need to answer during the data exploration phase. They will help us to understand the data and become familiar with different variables.
- **modeling.ipynb**: this file contains instructions for modeling part of the project. We recommend to split modeling tasks into more notebooks.
- **data_description.md**: if you are looking for any information regarding specific attributes in the data this is the file to look in.
- **sample_submission.csv**: this file is an example how the submission for the modeling task should look like.

==================== **Exploratory Analysis Notebooks** ==================================
- [**eda_task1.ipynb**](eda_task1.ipynb)  
- [**eda_task2.ipynb**](eda_task2.ipynb)    
- [**EDA_task_3_with_weather_data_from_slack.ipynb**](EDA_task_3_with_weather_data_from_slack.ipynb)  
- [**EDA_task_3.ipynb**](EDA_task_3.ipynb)    
- [**eda_task4_time_corrected.ipynb**](eda_task4_time_corrected.ipynb)  
- [**eda_task4.ipynb**](eda_task4.ipynb)    
- [**eda_task5_task6.ipynb**](eda_task5_task6.ipynb)  
- [**EDA_task_7.ipynb**](EDA_task_7.ipynb)  
- [**EDA_task_9.ipynb**](EDA_task_9.ipynb)
- [**eda_task8.ipynb**](eda_task8.ipynb)    
- [**eda_task_10.ipynb**](eda_task_10.ipynb)  
- [**EDA_task_10_part_3_and_4.ipynb**](EDA_task_10_part_3_and_4.ipynb)

============================================================================  
   
================= Data Gathering, Cleaning & Feature Engineering Notebooks ====================   
- [**get_large_data.ipynb**](get_large_data.ipynb)   
- [**data_cleaning.ipynb**](data_cleaning.ipynb)
- [**data_cleaning_with_delays.ipynb**](data_cleaning_with_delays.ipynb)  
- [**multiclass_large_data_cleaning.ipynb**](multiclass_large_data_cleaning.ipynb)
- [**Reg_onehot_label.ipynb**](Reg_onehot_label.ipynb) 

============================================================================

================= Modeling Notebooks =============================================
- [**RandomForest_model_load.ipynb**](RandomForest_model_load.ipynb)  
- [**XGB_binary_Presentation.ipynb**](XGB_binary_Presentation.ipynb)                    
- [**XGboost_binary.ipynb**](XGboost_binary.ipynb)     
- [**XGBoost_reg_best.ipynb**](XGBoost_reg_best.ipynb)
- [**multiclass_large_data_model.ipynb**](multiclass_large_data_model.ipynb)                      
- [**Regressions_presentation.ipynb**](Regressions_presentation.ipynb) 
- [**SMOTE_XGB.ipynb**](SMOTE_XGB.ipynb)      
- [**Multiclass_Classification.ipynb**](Multiclass_Classification.ipynb)   

============================================================================   

================= Readme Files and Guide Notebooks====================================
- [**exploratory_analysis.ipynb**](exploratory_analysis.ipynb)      
- [**sample_submission.csv**](sample_submission.csv)
- [**presentation_guidelines.md**](presentation_guidelines.md) 
- [**data_description.md**](data_description.md)
- [**modeling.ipynb**](modeling.ipynb)
- [**LICENSE**](LICENSE)                               
- [**README.md**](README.md)  
- [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md)

============================================================================

================= Saved Models ==================================================
- [**XGBoost_regressor_final.sav**](XGBoost_regressor_final.sav)  
- [**Ridge_label_final.sav**](Ridge_label_final.sav)           
- [**XGBoost_onehot_reg.sav**](XGBoost_onehot_reg.sav)
- [**XGBoost_model_smote.sav**](XGBoost_model_smote.sav)
- [**Ridge_onehot_final.sav**](Ridge_onehot_final.sav)
- [**XGBoost_model.sav**](XGBoost_model.sav)  

============================================================================
                      

### System Requirements  
**Operating System**: Windows   
**Programing Language**: Python  

Please be carefull of the large datasets  
**Minimum 16GB Ram to run the large multiclasification files.**   


### Data

We will be working with data from air travel industry. We will have four separate tables:

1. **flights**: The departure and arrival information about flights in US in years 2018 and 2019.
2. **fuel_comsumption**: The fuel comsumption of different airlines from years 2015-2019 aggregated per month.
3. **passengers**: The passenger totals on different routes from years 2015-2019 aggregated per month.
5. **flights_test**: The departure and arrival information about flights in US in January 2020. This table will be used for evaluation. We are required to predict delays on flights from first 7 days of 2020 (1st of January - 7th of January). We can find sample submission in file _sample_submission.csv_    
