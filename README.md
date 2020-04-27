# Monitoring Critical Trends in COVID-19 Pandemic Through Geospatial Analysis
## Background
Data Analysis with the continuously updating information on confirmed case and death reports encourage policymakers, health officials, as well as the general public to better visualize the spread of the virus across counties in order to identify potential patterns and enforce practices to help minimize the spread. 
Visualizations are crucial as it helps state and city leadership better manage the toll of the spread in their respective areas. It allows counties to be identify other communities that might need supplies or support and also be prepare if there's an increasing amount of cases in their own areas. 

**Business Question**
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

**Data Question**
Which data and metrics can we use to identiy trends and visualize the spread of the virus throughout US coutnies?

## Data Answer
<img width="1036" alt="Screen Shot 2020-04-25 at 2 13 15 PM" src="https://user-images.githubusercontent.com/60996310/80331247-86792b00-8815-11ea-80d9-4497096a17fd.png">

<img width="1140" alt="Screen Shot 2020-04-26 at 11 24 35 PM" src="https://user-images.githubusercontent.com/60996310/80331095-22eefd80-8815-11ea-8518-7e062c9a1e91.png">

The scatterplot and heatmap reveal the major hotspots of spread with the most cases being in Washington (presumable the Seattle area) and the northern major cities like New York and Boston. The heatmap is a better indicator of level of severity in different states with its numerical scale which helps with comparing the 

## Business Answer
How might our data visualizations help county and state leadership or business owners in the US? 
The data visualizations allow county and state leadership, business owners, and individuals 

## Further Analysis
There are some states like Wyoming and West Virginia that don't have any areas that indicate that the virus has spread in their county. While this could be to those areas being less travelled to, another possibility that should be explored is whether or not those states and counties perform a lot of testing on their people which could unveil much higher numbers of confirmed cases. Cross-referencing data on the amount of COVID-19 testing in every county would be useful in determining the reliability of the data of the spread while also highlighting the need for testing in certain areas. This data would be best represented in an animated choropleth map to track which counties are the fastest at responding to crises and which that don't have a lot of resources or attention to effectively address the medical threats.  

### Data Sources
**Google Colab**: https://colab.research.google.com/drive/1j0BeWg_UoHrazOhDnjpKFhUrTM4lNKea

JHU: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
NYT: https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv
Geospatial Data: https://raw.githubusercontent.com/plotly/datasets/master/geojson-counties-fips.json
