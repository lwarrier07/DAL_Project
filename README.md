# DAL_Project_Team6
# Comprehensive Environmental Insight Project: Unveiling India's Ecological Footprint

## Programmed by
1. Homita Ganguly (Reg no. 22112314) 
2. Lakshmi Madhu Warrier (Reg no. 22112320)
3. Siddhi Jhanwar (Reg no. 22112334)
4. Simran Adwani (Reg no. 22112335) 

## Description
The Environmental Impact Data Analytics Project delves into the intricate analysis of air quality and environmental factors across various states and union territories (UTs) in India. This data-driven exploration aims to uncover insights that contribute to a deeper understanding of environmental challenges. The comprehensive project involves data cleaning, descriptive statistics, exploratory data analysis (EDA), and predictive modeling, providing valuable tools for addressing environmental concerns.

## Dataset Description
The dataset incorporates a multitude of parameters, including air quality indicators (SO2, NO2, PM10, PM2.5), pesticides consumption, population, state area, and various environmental features such as land use, forest cover, wetlands, and water bodies. The diversity of these parameters allows for a holistic examination of environmental conditions.

## Project Structure

* *Data Cleaning and Exploration:*
   * The data_tab view provides an overview of the dataset, showcasing the first and last ten rows along with detailed information about each column, including data types and null counts.
* *Data Profile:*
   * The profile_view view generates a Pandas profiling report, offering insights into data types, missing values, correlations, and variable distributions.
* *Descriptive Statistics:*
   * The descriptive_statistics_tab view performs descriptive statistics, presenting summary metrics like mean, standard deviation, minimum, maximum, and quartiles for numerical columns.
* *Exploratory Data Analysis (EDA):*
   * The exploratory_data_analysis_tab view employs interactive visualizations such as histograms, box plots, scatter plots, and pie charts, enabling users to explore distribution patterns and relationships within the data.
* *Exploratory Data Analysis (EDA):*
   * The exploratory_data_analysis_tab view employs interactive visualizations such as histograms, box plots, scatter plots, and pie charts, enabling users to explore distribution patterns and relationships within the data.
* *Data Profiling*
   * In this project is pivotal for comprehensive analysis. It unveils crucial insights into data types, missing values, correlations, and distributions, ensuring a nuanced understand
* *Predictive Modeling:*
   * The predict_air_quality and predict_land_erosion view implements a predictive model using a RandomForestRegressor. Users can input values for various features, and the model predicts the target variable. The trained model is saved for future predictions.

## Functionality

- *Data Profiling:*
  - Access the data profiling report at http://yourdomain.com/data-profiling/.

- *Data Cleaning and Exploration:*
  - Use the data_tab view to explore the first and last ten rows of the dataset.

- *Descriptive Statistics:*
  - Utilize the descriptive_statistics_tab view to get summary statistics.

- *Exploratory Data Analysis (EDA):*
  - Navigate to the exploratory_data_analysis_tab view to explore interactive visualizations.

- *Box Plot:*
  - Create an interactive box plot using the box_plot view.

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
