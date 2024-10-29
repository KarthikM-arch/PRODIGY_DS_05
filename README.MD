# PRODIGY_DS_05

# Task-05 Analysis_of_US_Accidents

## Project Overview

Traffic Accident Data Analysis
This project analyzes traffic accident data in the United States to identify patterns and contributing factors related to road conditions, weather, and time of day. It also visualizes accident hotspots and examines the distribution of accidents by severity.

Dataset
The dataset used for this analysis can be found on Kaggle. It contains data on accidents across the United States, including features such as Start_Time, Start_Lat, Start_Lng, Severity, Weather_Condition, and others.

Project Structure
Analysis_of_US_Accidents.ipynb: Main Jupyter notebook with all data loading, preprocessing, analysis, and visualization steps.
README.md: Documentation for the project.
Installation
To run this analysis, you'll need Python and several libraries. Use the following commands to install the required packages:

# Create a virtual environment (optional but recommended)
python -m venv env
source env/bin/activate  # On Windows, use 'env\Scripts\activate'

# Install required packages
pip install pandas seaborn matplotlib scikit-learn
Usage
Load the dataset: Ensure the dataset is named US_Accidents.csv and is in the same directory as the notebook.
Run the notebook: Open Analysis_of_US_Accidents.ipynb in Jupyter Notebook or Jupyter Lab and execute the cells.
Analysis Steps
Data Cleaning:

Parse date columns and handle any missing or erroneous values.
Extract time-based features like the hour of the day and day of the week.
Exploratory Data Analysis (EDA):

Accident counts by hour and day of the week.
Accident severity by different weather conditions.
Heatmap of accident severity across weather types.
Hotspot Analysis:

Accident density using hexbin plots for geographical hotspots.
Cluster analysis using DBSCAN to identify accident-prone areas.
Visualizations
The analysis includes several visualizations to help interpret the data:

Accident Distribution by Hour: Shows peak accident hours.
Severity by Weather Condition: Displays how weather affects accident severity.
Day of the Week Analysis: Highlights accident frequencies across weekdays.
Geographical Hotspots: Uses a hexbin plot to identify accident-prone areas.
DBSCAN Clusters: Identifies and plots clusters of accidents as potential hotspots.
Findings
The analysis reveals insights into the conditions under which accidents are most likely to occur, such as:

Peak accident hours.
The impact of various weather conditions on accident severity.
Accident hotspots across the map, which could inform city planning and road safety measures.
License
This project is licensed under the MIT License.

Acknowledgements
Data from Kaggle.
Libraries: pandas, seaborn, matplotlib, and scikit-learn.