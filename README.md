# VIRGINIA-CLIMATE-CENTER-INDICATOR-DASHBOARD

Collaborators:

Sai Deepak Nyatha (G01353631)-  snyatha@gmu.edu (Scrum Master)

Namrata Reddy Palle (G01284937)-  pnamrata@gmu.edu (Product Owner)

Esther Tanvi Marlapudi (G01337846) - emarlapu@gmu.edu (Developer)

Akhilesh Godishala (G01353173)-  agodisha@gmu.edu (Developer)

Nitin Reddy (G01371098)- ntadasin@gmu.edu (Developer)


# Team Virginia Weather Watchers Project

## Project Overview
The project analyzes heat waves, cold waves, and extreme rainfall events in Virginia from 1951 to 2023. It utilizes NOAA's NClimGrid dataset to study these climatic phenomena's frequency, intensity, duration, and spatial distribution.

## Prerequisites
- Python (preferably 3.8 or newer)
- Jupyter Notebook
- Pandas library
- Tableau (for visualization)

## Setup Instructions
1. **Create a Project Folder**: Create a folder on your desktop or preferred location for project files (e.g., `VirginiaWeatherProject`).

2. **Download the NOAA Data**: Access and download the all the required NOAA NClimGrid data files. Save this data within a subfolder named `Data` inside your project folder.

3. **Clone or Download Project Files**: Clone or download the provided Jupyter notebooks, data cleaning and visualization i.e. tableau workbook files into your project folder.

## Execution Workflow
1. **Data Extraction and Formatting (`Data Extraction and Formatting.ipynb`)**:
   - Launch Jupyter Notebook.
   - Open the `Data Extraction and Formatting.ipynb` file.
   - Execute the cells in sequence to extract and format the climate data.
   - The script will save processed data files in the `Data` folder.

2. **Data Cleaning (`data_cleaning.html`)**:
   - Review the `data_cleaning.html` file for instructions and Python code to clean the extracted data.
   - Apply these cleaning steps to the data in your `Data` folder.

3. **Heat and Cold Wave Analysis (`Heat cold waves.ipynb`)**:
   - Open the `Heat cold waves.ipynb` file in Jupyter Notebook.
   - Execute the notebook cells to perform the heat and cold wave analysis.
   - The script identifies heat and cold wave events and calculates their characteristics.
   - The results will be saved in a CSV file, typically in the same folder.
   - Alternatively, you can also approach this analysis using the other heatwave and cold wave data calulation python file.
   - You can create the seperate csv files used for the time series dashboard using this python script.

4. **Data Visualization with Tableau**:
   - Open the tableau workbook file provided and connect the data sources respectively, make sure the data filenames match for the dashboard to work accurately.
   - Use Tableau to open the CSV file generated from the previous step.
   - Manipulate visualizations as per your requirements.

## Project Outputs
The project outputs include:
- Processed climate data in CSV format.
- Analyzed data on heat and cold waves in Virginia.
- Visualizations in Tableau showcasing trends and patterns.

## Tips for New Users
- Ensure all dependencies (like Pandas) are installed in your Python environment.
- Familiarize yourself with Jupyter Notebook's interface for executing the Python notebooks.
- In Tableau, explore various types of visualizations to best represent the data.

## Conclusion
This README guides users through setting up their environment, executing the provided scripts, and analyzing climate trends in Virginia. The project aims to equip policymakers and the public with insights into the changing climate patterns in Virginia.

