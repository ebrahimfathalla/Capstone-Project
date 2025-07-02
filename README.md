# A Data-Driven Analysis of Road Accidents in the UK
## __Project Overview__

This project seeks to identify patterns, trends, and key contributing factors that influence the severity and frequency of road traffic accidents across the United Kingdom. It analyzes road accident data from 2021–2022, sourced from the UK Department for Transport. The analysis focuses on aspects such as road type, speed limits, weather and lighting conditions, and accident timing to better understand how and why accidents happen, and to propose data-driven recommendations for reducing accident risks.

## __Objectives__

1. Identify recurring patterns and trends in UK road traffic accidents.
2. Determine the key environmental and situational factors that influence accident severity.
3. To visualize accident characteristics for better public and institutional understanding.
4. To support decision-makers with data-driven insights aimed at reducing road-related incidents.

## __Dataset and Data Dictionary__
UK Accident [Dataset](https://www.kaggle.com/datasets/ismayilbayramov1/uk-road-accident-project?select=UK+data+accident.xlsx):
307,974 rows across 23 columns, with each row representing a unique traffic accident reported between 2021 and 2022.
Source: UK Road Accident Dataset on Kaggle
## Key Columns:
1. Accident_Index – Unique identifier for each accident.
2. Date / Time – Timestamp of when the accident occurred.
3. Severity – Categorized as Slight, Serious, or Fatal.
4. Road_Type – Classification of the road (e.g., A-road, B-road, Motorway).
5. Speed_Limit – Legal speed at the accident site.
6. Weather_Conditions – Clear, rainy, foggy, etc.
7. Light_Conditions – Daylight, darkness with/without lighting.
8. Urban_or_Rural – Classification of the area.
9. Number_of_Vehicles – Count of vehicles involved.
10. Number_of_Casualties – Number of injured or deceased individuals.
11. Other relevant columns include location-related and infrastructure details.

## Data Types:
Mixed types including categorical like (Severity, Weather) and numerical (Number_of_Casualties), and datetime.

## __Analysis__
The majority of accidents were categorized as Slight, but Serious and Fatal accidents were more common in rural and poorly lit areas. Accidents peaked during weekday rush hours, particularly between 8–10 AM and 4–6 PM. Also Roads with higher speed limits had a greater proportion of serious outcomes. Even adverse weather (rain, fog) and dark lighting conditions significantly contributed to accident severityand the most affected regions were those with low visibility and limited safety infrastructure. Vehicle types and location-specific data showed that some police jurisdictions consistently recorded more casualties than others.

## __Conclusion__
In conclusion, this analysis shows that speed, weather, vehicle type, location, and lighting all affect road accident patterns in the UK. By understanding these trends, we can help improve safety through better planning, awareness, and targeted actions.

## __How to Run__
1. Clone the repository.
2. Open the Excel dataset to review raw and cleaned data.
3. Run the Power BI .pbix file to interact with dashboards and visualizations.

## __Dependencies__
1. Microsoft Excel
2. Microsoft Power BI

