# Visualization 1: Property Type Distribution in High-Concentration Wards

## Software Used
This visualization was created using Python (Pandas and Seaborn) in a Jupyter Notebook. Pandas was used to clean and organize the data, and Seaborn was used to create the heatmap.

## Intended Audience
This visualization is intended for Toronto residents, housing researchers, and policy makers who are interested in understanding how short-term rentals interact with different types of housing.

## Message / Purpose
This heatmap shows the property type distribution in the five wards with the highest share of short-term rental registrations. Instead of using raw counts, the data was converted to percentages so that each ward could be compared fairly.

The goal is to understand what kind of housing is being used for short-term rentals in the areas where they are most concentrated.

## Design Considerations
- Percentages were used instead of raw counts to allow comparison across wards.
- A simple blue color scale was used to show increasing intensity.
- Exact percentage values were included to make the chart easier to interpret.
- The layout was kept clean to avoid clutter.

## Reproducibility
All steps used to clean and transform the data are included in the Jupyter Notebook. The dataset is loaded locally and all calculations are shown, making the visualization fully reproducible.

## Accessibility
- A clear color palette was used.
- Numeric labels are included for clarity.
- The title and axis labels are descriptive and easy to read.

## Impacted Communities
This visualization highlights how short-term rentals may affect different neighborhoods in different ways. In some wards, condominiums dominate, while in others detached housing is more common. This may impact renters, homeowners, and long-term residents differently.

## Feature Selection
The analysis focuses on ward name and property type because they directly relate to housing structure. Other fields such as postal code and unit number were not used since they do not add meaningful insight to this question.

## Underwater Labour
This required grouping the data by ward, calculating percentages, selecting the top wards, and restructuring the data for visualization.