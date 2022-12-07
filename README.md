# ppol564_group1_new

## 1. Overview
    
   State: Kentucky

   Variables: Air Quality and people's health status

   Outcome: Any correlations and potential policy suggestions

## 2. Data:
#### Google Drive For Data: 
https://drive.google.com/drive/folders/1_r7lX19z70et-daZjuolweQsYZMqT72M?usp=sharing


  1. Air Quality Data
      Source: United States Environmental Protection Agency
      
      Original Link: https://aqs.epa.gov/aqsweb/airdata/download_files.html 
      
      Data Year: 2019
      
      Main Geolocation Data: County Name, Defining Site.

  2. Health Data: 
        
        Original Link: https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-Census-Tract-D/cwsq-ngmh
      
        Data Year: 2019
        
        Main Variables: StateDesc, Short_Question_Text
        
  3. Sulfur Data: 
  
        Original Link: https://aqs.epa.gov/aqsweb/airdata/download_files.html#Daily
      
        Data Year: 2019
        
        Main Variables: County Name, Site Num, AQI


## 3. Code:

Each file has been stored in a working ipynb file for further experimentation and then rendered into an html (placed in output folder) for easier read. 

1. 0_Final_Data_Cleaning: \
        Cleaning and condensing of data for further analysis

2. 1_Final_Data_Merging:
        1.2: Merging Air Quality data with health data based on County Name
        1.3: Merging previously-joined data with sulfur data based on County Name, that is then refined to precisely locate collection points within 15 miles of each other

3. 2_Final Data Visualizations:
        Data visualizations for better insight into data: 
        (Visualizations in HTML format placed in Output folder for direct use):
        2.2: Heat_Map_of__Monthly_Average_AQI_for_Kentucky_by_County.html
        2.3: Heat_Map_of_Categorical_Average_AQI_for_Kentucky_by_County.html
        2.4: Health_SO2.html
        

4. 3_Regression:
        Finding linear relationship netween different health measures and Air Quality/Sulfur measurements


## 4.Output:
        Code rendered in HTML:
                0_Final_Data_Cleaning.html
                1_Final_Data_Merging.html
                2_Final_Data_Visualization.html
                3_Regression.html
        Outputs in HTML & PNG:
            Visualizations:
                    2.2: Heat_Map_of__Monthly_Average_AQI_for_Kentucky_by_County.html
                    2.3: Heat_Map_of_Categorical_Average_AQI_for_Kentucky_by_County.html
                    2.4: Health_SO2.html
            Regression Results:
                    4.2.0: Air Quality Index & General Health
                    4.2.6: Air Quality Index & Mental HEalth
                    4.3.1: Sulfur & General Health
