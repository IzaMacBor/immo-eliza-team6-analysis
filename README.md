
# Immo Eliza Data Analyst

## Description

This project is part of the AI Bootcamp at BeCode, focusing on analyzing real estate prices across Belgium.
The goal is to perform data analysis that can estimate property prices based on various factors. The 
project involves analyzing a scraped dataset that provides useful insights into the real estate market.


## Data

The dataset includes the following columns:

- **id**: Unique identifier for each listing.
- **locality_name**: Name of the locality where the property is located.
- **Postal_code**: The postal code corresponding to the property's location.
- **Price**: The listed price of the property.
- **Subtype**: The subtype of the property (e.g., apartment, house).
- **Number_of_rooms**: Total number of rooms in the property.
- **Number_of_bedrooms**: Number of bedrooms in the property.
- **Living_area**: The living area (in square meters) of the property.
- **sale_annuity**: Indicates if the sale includes annuity.
- **Type_of_sale**: Type of sale (e.g., public or private).
- **street**: Street address of the property.
- **number**: Street number.
- **latitude**: Latitude coordinates of the property.
- **longitude**: Longitude coordinates of the property.
- **Open_fire**: Whether the property has an open fire.
- **Swimming_Pool**: Indicates if the property has a swimming pool.
- **hasTerrace**: Whether the property includes a terrace.
- **terraceSurface**: Size of the terrace, if present.
- **hasGarden**: Whether the property includes a garden.
- **gardenSurface**: Size of the garden, if present.
- **Kitchen_type**: Type of kitchen (e.g., fully equipped, semi-equipped).
- **Number_of_facades**: Number of facades of the building.
- **State_of_building**: The current condition or state of the building (e.g., new, to renovate).
- **Furnished**: Whether the property is furnished.
- **Starting_price**: Starting price in the case of a bidding sale.
- **epc**: Energy performance certificate rating of the property.

## Collaborators

This project is a team effort with the following contributors:
- [Petra](https://github.com/Pe789)
- [Rik](https://github.com/ricosaxo)
- [Tom](https://github.com/CyclingCodeCrusader)
- [Izabela](https://github.com/IzaMacBor)

## Approach

1. **Data Preprocessing**: 
   - Clean and prepare the dataset by handling missing values, categorizing data, and generating new features where necessary.
   - Explore correlations between variables to identify which factors influence property prices the most.

2. **Exploratory Data Analysis**:
   - Provide insights into the current state of the Belgian real estate market.
   - Visualize trends in property prices based on locality, property type, and other key features.
   - Identify outliers and anomalies in the dataset.

3. **Visualization and Reporting**:
   - Present the key findings and predictions in a clear and concise manner using graphs and charts.
   - Highlight the most important variables that influence property prices.
   - Answer the key questions posed by Immo Eliza’s management regarding the real estate market and variable importance.

## Repo structure

```
.
├── analysis/
│ └── personal_notebooks/
│                    └── Izabela.ipynb
│                    └── Petra.ipynb
│                    └── Rik.ipynb
│                    └── Tom.ipynb
│ └── Team_6_Step_1_cleanup.ipynb
│ └── Team_6_Step_2_enhancing.ipynb
│ └── Team_6_Step_3a_outliers_num.ipynb
│ └── Team_6_Step_3b_outliers_cat.ipynb
│ └── Team_6_Step_4_correlation.ipynb
│ └── Team_6_Step_4_visualization.ipynb
├── data/
│ └── clean/
|        └── after_step_1_cleaning_houses.csv
|        └── after_step_1_cleaning_houses.pkl
|        └── after_step_1_cleaning.csv
|        └── after_step_1_cleaning.csv
|        └── after_step_2_enhancing.csv
|        └── after_step_2_enhancing.pkl
|        └── after_step_3a_outliers_num.csv
|        └── after_step_3a_outliers_num.pkl
|        └── after_step_3b_outliers_cat.csv
|        └── after_step_3b_outliers_cat.pkl
|        └── after_step_4_correlation.csv
|        └── after_step_4_correlation.pkl
| └── raw/ 
|        └── immo_scraper_merged_test.csv       
├── reports
|        └── BeCode Immo Team 6.pdf
├── .gitignore
├── README.md
└── requirements.txt
```

## Usage

1. **Clone the repository**:

2. **Create a virtual environment (optional but recommended)**

3. **Install the required libraries**
   - Check `requirements.txt`.

4. **Start in `analysis` folder:**
   - Run the notebooks from `Step 1` to `Step 5`

5. **Clean data**:
   - The clean data are saved in `after_step_4_correlation.csv`.

6. **Report**:
   - Here you can find our resultat and conclusions.
