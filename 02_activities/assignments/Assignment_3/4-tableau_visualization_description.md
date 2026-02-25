# Visualization 2: Spatial Distribution of Short-Term Rental Registrations in Toronto

## Software Used
This visualization was created using Tableau Public. The original dataset was uploaded directly into Tableau, and the map was generated using postal code geographic data. Aggregation was handled within Tableau by counting registrations per postal code.

## Intended Audience
This visualization is intended for Toronto residents, urban planners, and housing policy researchers who are interested in understanding where short-term rentals are concentrated geographically.

## Message / Purpose
This map shows the spatial distribution of short-term rental registrations across Toronto. Color intensity represents the number of registrations within each postal code area.

The goal is to highlight areas with high concentrations of short-term rentals and compare them to lower-density areas. This helps identify geographic clustering patterns within the city.

## Design Considerations
- A sequential color palette was used to represent increasing registration counts.
- Full color range was enabled to improve visual separation.
- White borders were added to clearly distinguish postal code areas.
- The map background was kept minimal to reduce distraction.
I was inted to use viridis palette but the tableau public doesn't provide it and when I wanted to create a customized one I lost the mid colors.

## Reproducibility
The visualization can be reproduced by uploading the original CSV file into Tableau Public and using SUM(Registrations) as the color measure. All aggregation is handled automatically within Tableau.

## Accessibility
I was inted to use viridis palette but the tableau public doesn't provide it and when I wanted to create a customized one I lost the mid colors.

- A single-hue sequential color palette was used to avoid misleading interpretation.
- The legend clearly explains what the color scale represents.
- The title explicitly states the purpose of the map.

## Impacted Communities
This visualization highlights neighborhoods where short-term rentals are highly concentrated. These areas may experience increased housing pressure, changes in neighborhood character, and impacts on long-term rental availability.

## Feature Selection
The visualization focuses on postal code and registration count. Other variables such as property type were excluded in order to keep the geographic message clear and focused.

## Underwater Labour
The process required exploring geographic roles in Tableau, creating an aggregated measure for registrations, adjusting the color scale for clarity, and refining the map layout for readability.