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
NOTE: The dashboard was not published to PowerBI Service, I thought it was acceptable to keep it in PowerBI Desktop as publishing is a simple task when its necessary
### Dashboard
![Dashboard Image](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/dashboard.png)

### Job Vacancy Detailed Report
![Job Vacancy Detailed Report Image](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/job_vacancy_report.png)

### Business Sector Detailed Report
![Business Sector Detailed Report Image](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/business_sector_report.png)

### Household Wellbeing Detailed Report
![Household Wellbeing Detailed Report Image](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/household_wellbeing_report.png)

### Household Financial Detailed Report
![Household Financial Detailed Report Image](https://github.com/yash-chaudhary/PowerBI_data_visualisation/blob/main/Assets/household_financial_report.png)

## Video Demo
[Video Demo](https://vimeo.com/605611957)

## Key Findings
As a disclaimer, since I've made most of my dashboard dynamic its a little bit hard to show you each and every graphs of my findings.

### Job Vacancy Findings
>In June of 2019, the number of job vacancies was sitting at 77,000 for New South Wales (NSW), 60,000 for Victoria (VIC) and 33,000 for Queensland (QLD). However in June of 2020 when the pandemic was in full swing, job vacancies dropped to 40,000 in NSW, 29,000 in VIC and 25,000 in QLD. Thats almost a 50% drop in open job positions in the span of 1 year due to COVID-19 as some businesses were forced to close down for good. However, as 2021 came around where vaccine were being rolled out and lockdowns across Australia were decreasing, things changed. Suddenly the job economy boomed as there were 110,000 job vacancies in NSW, 90,000 in VIC, and 70,000 in QLD. Jobs in smaller states increased by almost 5 times as casual workers had been laid off during lockdowns.
>
>During the pandemic, some industries had been hit worst than others. Particularly, the accommodation and food services industry as well as retail trade were impacted the most by lockdowns due to a lack of foot traffic and travelling. As as result their job vacancies dropped from 14,000 and 19,000 respectively in June 2019 to 5,0000 and 11,400 in June 2020. In stark contrast to this, administrative and support services as well as healthcare and social assistance sky-rocketed as a result of medical expertise and contact tracers being high in demand. 

### Business Sector Findings
>Without a question, the total sales in Australia in the large states (NSW, VIC, QLD) dropped as businesses were shutting down and consumers turned to international online vendors. What was worse was that the largest percent change in profits was -51.1% which occured in March of 2020 at the point where the pandemic was officially in infecting everyone globally. As mentioned previously, there were definitely some industries that benefited greatly from the pandemic, namely mining, wholesale trade and administrative and support services. The percent increase in profits was 4.01% for mining, 3.12% for wholesale trade and 10.77% for administrative services. The rise in these industries doesn't seem like a surpise since panic buying really help companies such as Coles and Woolworth make massive gains whilst the exports of iron to China had also ramped up. 
>
>The terms of trade rose 7.0% in June of 2021 and is now at its highest level in history. This can be attributed to the strong export prices for mining commodities drove the quarterly rise. As the Australian economy rose 0.7%, reflecting the continued easing of COVID-19 restrictions and the recovery in the labour market. In June of 2019, the total amount of sales was $743 billion dollars. However in 2020, that dropped to $668 billion dollars, about a 10.1% drop in total sales nationally. But in June of 2021, the total sales of Australia rose to $795 billion dollars. Thus Lockdowns had minimal impact on activity overall, but still impacting particular industries such as accommodation and food services as well as arts and recreational services.

### Household Findings
>Mental health and wellbeing is incredibly important factor to consider, especially in a household in lockdown during the pandemic. From 2017 to 2018, the proportion of people with mental illness has remained relatively consistent. However as soon as we hit 2020, the percentage of people experiencing mental illness spiked to 29.6% in New South Wales (NSW), 27% in Victoria (VIC) and 28.3% in Queensland (QLD). Hence the major states which coincidentally had the longest and most frequent pandemic lockdowns had the highest proportion of mental illness. Conversely, although smaller in population, mental illness increased in other states as well like in the Australian Capital Territory (ACT) where in 2019 13.9% of people had a mental illness but in 2020 that jumped to 20.3%.
>
>I also plotted the proportion of people who were having uneasy feelings over teh course of the pandemic. In September of 2020, when the pandemic had been going on for around 6 months, 40.7% of Australia felt that everything was an effort, 45.7% said they felt nervous and 41.1% felt restless or fidgety. We know that these feeling can be attributed to being lockdown in our homes as I'm sure many of us have had similar feelings to this at the height of COVID-19. Nevertheless these proportions went down significantly in March of 2021 when lockdowns were not longer occuring and a vaccine for COVID-19 was ready to be administered. In this quarter nervousness fell down to 26.5% and restlessness fell to 22.1%. However, in July of 2021, 25.8% of Australian's felt that the pandemic will stay for another year into 2022. However as the distribution of when COVID-19 will cease was relatively similar, meaning no one really is able to forecast what may happen, a large percentage of about 15.5% said that life will never return to normal suggesting that the pandemic had a deep impact on these individuals. However, a larger proportion of the Australia population was attending to more of the activities they took part in before the pandemic, for example shopping.
>
>The financial aspect of households showed that in June of 2020, household spending was at its lowest at $235.3 billion across Australia. This was a decrease of 12.3% from its previous quarter. At the same time the unemployment rate was also at its highest at 7.4% where around 12,376,000 people were employed. Exactly a year leate in june of 2021, things changed massively as now household spending had increased 1.1% to $271.5 billion where the unemployment rate also dropped to 4.9% with the total number of employed people sitting at 13,154,200.

### Summary
Therefore, we can clearly see the negative impact COVID-19 and the pandemic has on Australia as job vacancies and sales/profits of most businesses were down whilst mental illness increased. We can see how job vacancies, the business sector and households are all linked together as when the sales and profits of businesses fall, the number of job vacancies also falls and so unemployment rises and household expenditure decreases thus increases the proportion of mental illness.


