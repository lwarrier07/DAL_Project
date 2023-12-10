# DAL_Project_Team6
# Comprehensive Environmental Insight Project: Unveiling India's Ecological Footprint

## Programmed by
1. Homita Ganguly (Reg no. 22112314) 
2. Lakshmi Madhu Warrier (Reg no. 22112320)
3. Siddhi Jhanwar (Reg no. 22112334)
4. Simran Adwani (Reg no. 22112335) 

## Description
The Environmental Impact Data Analytics Project delves into the intricate analysis of air quality, land quality and environmental factors across various states and union territories (UTs) in India. This data-driven exploration aims to uncover insights that contribute to a deeper understanding of environmental challenges. The comprehensive project involves data cleaning, descriptive statistics, exploratory data analysis (EDA), and predictive modeling, providing valuable tools for addressing environmental concerns.

## Dataset Description
The dataset encompasses a comprehensive array of parameters, integrating air quality indicators (SO2, NO2, PM10, PM2.5), pesticides consumption, population, state area, and diverse environmental features such as land use, forest cover, wetlands, and water bodies. The main Django project utilizes the cleaned_data.csv file, featuring an extensive set of headers like State/UT, SO2, NO2, PM10, PM2.5, Pesticides Consumption, Population, State Area, and various environmental characteristics. This dataset's diversity facilitates a holistic examination of environmental conditions.
For the land erosion prediction component, the project folder incorporates .ipynb files utilizing the cleaneddata.csv dataset. This dataset includes headers such as S. No., State/UT, State Area km², Water Erosion, Wind Erosion, Water Logging, Salinisation/Alkalisation, Acidification, Anthropogenic, Others, Total, SO2, NO2, PM10, PM2.5, Year, Annual temperature (min), Annual temperature (max), and Annual rainfall. These parameters contribute to a nuanced analysis, providing insights into various erosion factors and climatic conditions over different time periods.

## Project Structure

 **Data Cleaning and Exploration:**

  - Data Tab View:
   - Provides an overview of the dataset.
   - Showcases the first and last ten rows.
   - Detailed column information included.

 **Data Profile:**

  - Profile View:
   - Generates a Pandas profiling report.
   - Offers insights into data types, missing values, correlations, and variable distributions.

 **Descriptive Statistics:**

  - Descriptive Statistics Tab View:
   - Presents summary metrics like mean, standard deviation, and quartiles.
   - Focuses on numerical columns.

 **Exploratory Data Analysis (EDA):**

  - Exploratory Data Analysis Tab View:
   - Utilizes interactive visualizations:
     - Histograms
     - Scatter plots
     - Pie charts
   - Explores data distribution patterns and relationships.

 **Data Profiling:**

  - Integral for Comprehensive Analysis:
   - Unveils crucial insights into:
     - Data types
     - Missing values
     - Correlations
     - Distributions

 **Predictive Modeling:**

  - Predict Air Quality View:
   - Implements a RandomForestRegressor.
   - Allows users to input values for various features.
   - Obtains predictions, and the trained model is saved for future use.

  **Additional**
   - Land Erosion Prediction (Jupyter Notebook):
      - land_prediction folder:
        - Contains .ipynb files providing codes and analysis for predicting land erosion.
        - Includes data preprocessing, feature engineering, and model training using machine learning techniques.


## Functionality

- *Data Profiling:*
  - Access the data profiling report at http://yourdomain.com/data-profiling/.

- *Data Cleaning and Exploration:*
  - Use the data_tab view to explore the first and last ten rows of the dataset.

- *Descriptive Statistics:*
  - Utilize the descriptive_statistics_tab view to get summary statistics.

- *Exploratory Data Analysis (EDA):*
  - Navigate to the exploratory_data_analysis_tab view to explore interactive visualizations.

- *Predictive Modeling:*
  - Use the predict_air_quality view to input values for various features and get predictions.

- *Data Export:*
  - Export cleaned data to CSV or Excel using the export_to_csv and export_to_excel views.

## Usage

1. Clone this repository to your local machine.
2. Ensure the cleaneddata.csv and cleaned_data.csv files are in the data_analysis_project folder.
3. Install the required packages: pandas, ydataprocessing.
4. Run the Django project.
5. Access various functionalities through the provided views.

## Project Layout
  - ![Screenshot (104)](https://github.com/lwarrier07/DAL_Project/assets/118895179/8aebe47e-ca50-4758-8d9f-1c410de73727)
    
  - ![Screenshot (102)](https://github.com/lwarrier07/DAL_Project/assets/118895179/d83abbf7-3e0f-45f4-a24f-e32480689270)
    
  - ![Screenshot (103)](https://github.com/lwarrier07/DAL_Project/assets/118895179/f9631488-b4ab-47eb-992d-ba77f29a69cc)
    
  - ![Screenshot (105)](https://github.com/lwarrier07/DAL_Project/assets/118895179/6b6acea3-ad3f-4529-aac9-0bf47ce1ef2b)
    
  - ![Screenshot (106)](https://github.com/lwarrier07/DAL_Project/assets/118895179/0ceb9126-d82f-4fb3-971e-5550dcce3fab)
    
  - ![Screenshot (107)](https://github.com/lwarrier07/DAL_Project/assets/118895179/f65cecb9-de9a-444c-88b9-4495efcc4f67)
    
  - ![Screenshot (109)](https://github.com/lwarrier07/DAL_Project/assets/118895179/02f7500c-16d5-43cd-b54c-298ba60402ea)
    
  - ![Screenshot (110)](https://github.com/lwarrier07/DAL_Project/assets/118895179/ea3ef4cb-7914-4c3c-9d15-e113b8f51fa4)
    
  - ![Screenshot (108)](https://github.com/lwarrier07/DAL_Project/assets/118895179/b452db90-52ce-44cc-8673-b991d06d98bc)



