# PowerBI Data Visualisation Project
Project 2: Data analysis and visualisation

## Project Specification
> In light of COVID-19, many people have created dashboards and infographics documenting the spread of the virus with respect to case numbers and deaths all around the world. However, there haven't been many detailed data visualisations illustrating the impacts of COVID-19 on a business, household and individual level. My dashboard will solely focus on exploring how COVID-19 has affected Australian households and businesses to really understand the monetary and mental tolls inflicted upon Australians during the pandemic. A complex mix of continuous and discrete data collected from reputable government databases was used to compare data pre-COIVD-19 and during the pandemic as well as forecasting post-pandemic behaviours of households and businesses. The insights from this dashboard should show you the exact point in time where the pandemic really hit Australians the hardest and I hope you can appreciate the "Aussie spirit" in banding together to fight the pandemic and getting our nation back on track.

## Data Discovery
>As mentioned above, many dashboards explore COVID-19 and its effect on the mortality. However, I decided to explore the effect of COVID-19 on households and the business sector to see which stakeholders in Australia have been worse off due to the pandemic. I thought this would be an interesting insight to map mental health data against financial and socio-economic data to find any key relationships.
>
>I couldn't find a dataset big enough for the analysis I wanted to make, so I made my own. The dataset I made was a compliation of many many data sources from government institutions. I required financial data and socio-economic data to analyse the impacts of COVID-19 on businesses and households respectively whilst also cross-checking specific dates with the existence of COVID-19. In the end I chose a 5-year window between 2017 and 2021 to clearly show the impact of the pandemic on the nation. 
>
>All the financial datasets were found on the Australia Bureau of Statistics (ABS) website which includes excel spreads of things like total sales by industry and total percent change in sales by state. The financial aspect of the household data was also found on the ABS website. But as I said, I wanted to explore the pandemic's effect on an individual level too. So I managed to find some data on mental illness and wellbeing during the pandemic on the ABS website too, however, this wasn't sufficient enough to make a valid analysis. I ended up finding data on suicide rates and mental illness on the Australian Institute of Health and Welfate (AIHW) which allowed me to make a more sound analysis on the mental toll of COVID-19. The data discovery phase was arguable the most cumbersome task that had to be completed and I spent many hours finding data that was valuable, relevant and representative of the Australian populace. 

## Data Modeling
>Upon reading many excel spreadsheets and choosing my data, I had to clean, process and prepare the data before I could use PowerBI. I used excel to transform the relevant data into tables so PowerBI could understand what the data was conveying. Since I was focusing on Australia, I transformed the data with respect to the states of Australia as well as the quarters (March, June, September, December) of the years 2017 to 2021. To create a dynamic dashboard, I created relationships between different tables that existed in my large compiled dataset to make the data visualisation more meaningful. Transforming the data took the longest time because I had to decide what would be valuable and relevant as well and also having to format the data so it was readable by PowerBI. 

## Data Visualisation
>As mentioned above, I aimed to show the data based on Australian states and the quarterly months between 2017 and 2021. The dashboard was essentially a summary of relevant data relating the business and households. The user is able to select a state by clicking on the map of Australia which conditionally visualises the total sales and job vacancy depending on the selected state. Furthermore, the user is also able to select a quarterly month between 2017 and 2020 to conditionally view specific years of interest. This "slicer" as its called in PowerBI is useful to compare pre-pandemic and pandemic time. 
>
>As the dashboard is merely a summary of a lot of data, I also wanted to create detailed reports that allows users to drill down to specific aspects of the dashboard that were only briefly explored for the sake of a summary. As a result, I created 4 reports that supplemented the main dashboard. The visuals on the dashboard relate to "Job Vacancy by State", "Mental Illness by State" and "Total and Percent Change of Sales by State". Hence tp supplement these visuals, the following detailed reports were created: Job Vacancy Detailed Report, Business Sector Detailed Report, Household Wellbeing Detailed Report and Household Finance Detailed Report. The detailed reports show what the dashboard couldn't, details about the metrics to properly understand how COVID-19 impacted Australia.
>
>I experimented with a bunch of visuals before finally deciding on the ones which actually suited the data. The data contained a variety of categorical and numerical data, so I had a range of options to try out. A common visual of mine was the line and stacked column chart which allowed me to show trends as well as categorical data all in one visual. I experimented with other powerBI features such as Drill Throughs, Drill Downs and Drill Ups and using DAX (Data Analysis Expressions) to combine data and create "New Measures" that allowed me to summarise all the data in a column with options such as total counts and averages.

>Overall I think the dashboards and reports look pretty nice and allows us to see how 2020 and 2021 (pandemic times) influenced households and business in stark contrast to pre-pandemic times (2017 to 2019)

## Solution Architecture
![Solution Architecture Diagram](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/System%20Architecture%20Diagram%20IoT%20App.png)

## The Dashboard and Detailed Reports
>Dashboard




>Job Vacancy Detailed Report




>Business Sector Detailed Report



>Household Wellbeing Detailed Report




>Household Financial Detailed Report





## Key Findings
>key insights from the data that is represented in the dashboard

