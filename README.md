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
[Heat Map](file:///Users/vesnatran/Downloads/density_heatmap_covid19_april14-3.html)

The **scatterplot and heat map** reveal the major hotspots of spread with the most cases being in Washington (presumable the Seattle area) and the northern major cities like New York and Boston. The heatmap is a better indicator of level of severity in different states with its numerical scale. They can identify the similarities in these counties (i.e. policies implemented, social practices) that lead to such higher number of cases and use that information to implement preventative measures in non/less affected counties. Identifying these areas that are most affected also help leadership in other counties reach out and help in supplying those regions with workers and resources if there's strain.  

<img width="971" alt="Screen Shot 2020-04-26 at 11 49 55 PM" src="https://user-images.githubusercontent.com/60996310/80332365-abbb6880-8818-11ea-9d4a-72d9dd31c57d.png">
[Choropleth Map](file:///Users/vesnatran/Downloads/covid19_cases_us_county.html)

The **animated choropleth map** illustrate the number of cumulative confirmed cases per 1000 over time. Standardizing the data helps measure the level of severity in each county on more a baseline as opposed to using raw data which is biased as it doesn't consider population size. Looking at the choropleth map, it's evident that the spread originated from major cities with major international airports in New York, Seattle, Texas, etc., and over time, it diffuses inwards until more rural areas are reporting cases. 

## Business Answer
 
The data visualizations allow county and state leadership, business owners, and individuals interpret which counties are the most impacted by the virus over time. The bubble map and heat map are efficient in illustrating the toll each county experiences compared to the rest of the nation by highlighting the number of cases. The animated map is most effective in identifying any common characteristics between the cities that are most heavily impacted (i.e. denser population, many tourist attractions) and certain migration patterns that have encouraged the spread. California, the first state that was colored in entirely on the map, was the first to order businesses to temporarily close while enforcing health guidelines that helped protect its people and its healthcare system from being overwhelmed.  

## Further Analysis
There are some states like Wyoming and West Virginia that don't have many areas that indicate that the virus has spread in their county. While this could be that those areas are less travelled to, another possibility that should be explored is whether or not those states and counties perform a lot of testing on their people which could unveil much higher numbers of confirmed cases. Cross-referencing data on the amount of COVID-19 testing and protocols in every county would be useful in determining the reliability of the data of the spread while also highlighting the need for testing in certain areas. This data would be best represented in an animated choropleth map to track which counties are the fastest at responding to crises and which that don't have a lot of resources or attention to effectively address the medical threats.  

Acquiring data on the number of recovered cases would also be useful as it identifies certain counties that are leaders in controlling the spread. It would be ideal to study what policies and practices (medically, socially, economically) that helped them recover after being heavily impacted so that other counties can model after.  

### Data Sources
**Google Colab**: https://colab.research.google.com/drive/1j0BeWg_UoHrazOhDnjpKFhUrTM4lNKea

JHU: https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports
NYT: https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv
Geospatial Data: https://raw.githubusercontent.com/plotly/datasets/master/geojson-counties-fips.json
