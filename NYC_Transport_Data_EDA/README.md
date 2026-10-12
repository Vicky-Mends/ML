# NYC Transport Data Analysis — Exploratory Data Analysis (EDA)

## Overview

This project explores pedestrian count and environmental data from New York City. Using Python and data analysis libraries, I investigate patterns in pedestrian activity and examine how factors such as time, temperature, precipitation, weather conditions, and events relate to pedestrian counts.

## Dataset

The dataset is retrieved from **NYC Open Data**.

- **Source:** [NYC Open Data — Bridge Data](https://data.cityofnewyork.us/api/views/6fi9-q3ta/rows.csv?accessType=DOWNLOAD)
- **Data includes:** Pedestrian counts, timestamps, temperature, precipitation, weather summaries, and event information.
- **Time coverage examined:** October 2017 through December 2019.

## Tools and Technologies

- Python
- Pandas — data loading, cleaning, transformation, and analysis
- NumPy — numerical operations
- Matplotlib and Seaborn — data visualization
- Jupyter Notebook — analysis and documentation

## Work Completed

### 1. Data Exploration
- Inspected the dataset's dimensions, columns, data types, and sample records.
- Examined descriptive statistics and distributions of variables.

### 2. Datetime Processing
- Converted `hour_beginning` to a datetime data type.
- Extracted time-based features, including year, month, day, hour, and day of the week.
- Examined the time range and checked for missing hourly timestamps.

### 3. Data Quality Checks
- Identified missing values across relevant columns.
- Investigated missing environmental data and whether missing values occurred together.
- Checked for duplicate timestamps and examined a repeated timestamp associated with the daylight saving time transition.

### 4. Data Cleaning
- Sorted records chronologically.
- Reset the DataFrame index.
- Forward-filled missing values in temperature, precipitation, and weather summary columns.

### 5. Exploratory Analysis and Visualization
- Examined pedestrian counts across days of the week, weather conditions, and events.
- Compared temperature patterns across months and hours.
- Explored relationships among pedestrian counts, temperature, precipitation, and time-based features using visualizations.

## Key Learning Outcomes

This project provided hands-on practice with:
- Exploratory data analysis (EDA)
- Datetime feature engineering
- Missing-data and duplicate-timestamp investigation
- Data cleaning with Pandas
- Grouped descriptive statistics
- Visual exploration of relationships in transportation and environmental data

## Project Status

**Completed:** Initial data exploration, data quality checks, cleaning, feature extraction, and exploratory analysis.

**Potential next steps:** Investigate pedestrian activity trends more deeply, assess the assumptions behind missing-value handling, and develop further analyses based on the findings.

## Repository Contents

- `NYC_Transport_data.ipynb` — Jupyter Notebook containing the analysis.
- `README.md` — Project overview, methodology, tools, and status.
