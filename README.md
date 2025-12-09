## Project Overview

This project analyzes **intake and outcome data** from three major animal shelters:  

- **Louisville Metro Animal Shelter**  
- **Bloomington Animal Care & Control**  
- **City of Austin Animal Center**  

**Goals / Key Insights:**  
- Identify the most common intake reasons by species  
- Examine outcome distributions across species  
- Calculate average length of stay in shelters  
- Compare adoption and euthanization trends over time  
- Provide actionable insights for shelter management and policy planning 
---

## How to Use

1. Clone Repository
   git clone https://github.com/Kat910/Capstone-Animal-Shelter-Analysis/tree/main/data

2. Install required Python packages:  
   pip install -r requirements.txt

3. Open shelter_analysis_project.ipynb in Jupyter Notebook or JupyterLab.

4. Output: Analysis and Charts included in the Python code and saved in plots/
---

## Data Sources

1. Yearly shelter data (2021 - 2025) CSV file kentucky_shelter_data.csv 
   - Stored in data/
   - Downloaded from the Louisville Metro site https://data.louisvilleky.gov

2. Yearly shelter data (2017 - 2025) CSV file BloomingtonIN_Animal_Shelter_Animals.csv 
   - Stored in data/ 
   - Downloaded from the City of Bloomington site https://data.bloomington.in.gov

3. Yearly shelter data (2013-2025) CSV files Austin_Animal_Center_Intakes.csv and Austin_Animal_Center_Outcomes 
   - Stored in data/ 
   - Downloaded from the City of Austin open data portal site https://data.austintexas.gov

   Note: Data was filtered due to size, for analysis, to the range of 1.1.23 - 7.31.25
---

## SQL Lite
1. Database file: data/animalshelterdata.db
2. Tables: Animal, Shelter, Intake, Outcome
3. ERD: available in the additional_documents folder.

## SQL Queries 
1. Most common intake reason by species (Google, Stackoverflow and AI consulted)
2. Most common outcome for an animal by species
3. Average length of stay for each species by shelter
4. Average length of stay by species for the outcomes: Adoption, Return to Owner and Euthanized
5. Average yearly adoption rates by species for each shelter
6. Average yearly euthanization rates by species for each shelter

## Visualizations 
1. Intake Total and Category Total by Year: Stacked Bar Chart
2. Heatmap of Species Outcomes:  Heatmap
3. Positive vs Negative Outcome Types Ratio: Pie Chart
4. Average Days in Shelter by Species: Bar Chart
5. Adoptions by Day of the Week: Bar Chart
---

## Author
   Katrinia Reppen

## License
   Open Data Commons Public Domain Dedication and License
