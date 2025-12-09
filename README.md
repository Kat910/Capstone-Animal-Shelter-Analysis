## Project Overview

This project analyzes **intake and outcome data** from three animal shelters in different states:  

- **Louisville Metro Animal Shelter**  
- **Bloomington Animal Care & Control**  
- **City of Austin Animal Center**  

**Goals:**  
- Identify the most common intake reasons by species  
- Examine outcome distributions across species  
- Calculate average length of stay in shelters  
- Compare positive (adoption) and negative (euthanization) trends over time
- Examine Peak Adoption months of the year and days of the week

**Conclusion Summary** 

For the period January 1, 2023 through July 31, 2025, the combined datasets from the three shelters resulted in 51,527 records across 18 columns, which were loaded into a SQLite database for analysis. Using a combination of SQL queries and data visualization techniques, several key insights emerged.

Intake Patterns:

Across all species, the most common reasons for intake were stray animals and owner surrenders due to non-behavioral factors. These patterns remained consistent throughout the study period.

Length of Stay:

Length of stay varied significantly by species. Dogs had an average stay of approximately 24 days, while cats stayed an average of 10 days. Exotic species and livestock had substantially longer stays, typically ranging from 30 to 70 days before being adopted or transferred.

Outcome Trends:

Overall, outcomes were predominantly positive. Positive outcomes accounted for 94% of all records, while negative outcomes represented 1.3%, and unknown outcomes 4.4%. Among the positive outcomes, adoption and return-to-owner were the most frequent. Although relatively low, euthanasia occurred at all shelters included in the analysis.

Seasonal and Weekly Adoption Patterns:

Adoption activity peaked in July, followed closely by January; the remaining months had little variation. In terms of weekly patterns, Friday and Saturday recorded the highest adoption volumes.

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
6. Adoptions by Month of the Year: Bar Chart
---

## Author
   Katrinia Reppen

## License
   Open Data Commons Public Domain Dedication and License
