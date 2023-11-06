# pyBNB
This is a repo for Project 1 of the Data Analytics Boot Camp through Washington University in St. Louis, partnered with edX. 

## Authors

Chris Burk, https://github.com/burk992

Emma Holtgrieve, https://github.com/eholtgrieve

Simon Murray, https://github.com/simonmurray25

## Introduction 

In the dynamic landscape of San Francisco's real estate market, the proliferation of short-term rental platforms, such as AirBNB, has emerged as a defining feature of the city's housing ecosystem. This phenomenon has raised questions about its potential impact on the availability of long-term rental housing for residents. As the allure of AirBNB has grown, so too have concerns that traditional rental properties are being diverted into the lucrative short-term rental market, exacerbating the scarcity of affordable housing.

This data analysis project seeks to unravel the intricate relationship between the expanding AirBNB market and the availability of conventional rental housing in San Francisco. Our primary objective is to empirically investigate whether the surge in AirBNB listings is indeed correlated with a reduced supply of long-term rental units. By harnessing a rich array of data sources and employing rigorous analytical techniques, we aim to shed light on the extent of this phenomenon and its implications for the housing landscape in one of the country's most dynamic and densely populated cities. Through this analysis, we aspire to provide insights that can inform discussions, policies, and potential solutions regarding the balance between the short-term rental industry and the long-term housing needs of San Francisco's residents.

## Analysis

### Q1 Analysis:

The primary focus of our analysis in this phase of the project is to compare the pricing of short-term rentals, such as AirBNB listings, with the average rent for comparable properties in the San Francisco City area. Our goal is to determine whether renting an AirBNB for residential purposes is more cost-effective than traditional rental options. To answer these questions, we initially gathered data from AirBNB listings, although this data isn't publicly available through the official AirBNB company website. Instead, we found a third-party source that frequently updates and provides extensive information through web scraping.

To obtain information regarding the pricing of current listings in the San Francisco City area, we extracted the price per night for each AirBNB listing from the scraped data. To create a comprehensive perspective, we calculated the price per month for each listing by multiplying the nightly rate by 30. We then categorized the listings based on these monthly rates to enhance data visualization. Our analysis revealed that out of the total 7,418 AirBNB listings, over 76% were priced at $3,000 or more per month.

For the second part of our analysis, we accessed the most recent census data available, specifically focusing on reported rent in the United States and narrowing it down to rent within the San Francisco City area. Using this dataset, we identified the gross reported rent for 748,165 residents in the city and classified them into categories similar to those used for AirBNB prices. The results demonstrated that although a similar percentage of people reported paying monthly rents ranging from $1,500 to $2,500, a significant 22% of residents were paying $3,000 or more for rent.

Upon examining both sets of data, it becomes evident that a substantial portion of people in San Francisco City are paying approximately the same amount for renting an apartment as they would for an AirBNB for the same duration. This could signify that AirBNB pricing may not have a direct influence on the pricing of traditional apartments, or it may highlight a potential housing shortage within the city, which could be driving up prices.

### Q2 Analysis:

In this section of our project, we shift our focus to comparing the vacancy rates of AirBNB properties with those of conventional rental units in San Francisco. To address this question, we utilized the dataset obtained through web scraping AirBNB listings and supplemented it with housing data sourced from the Census Data. To gain further insights, we introduced a novel statistical metric to determine the actual vacancy rate for each AirBNB, considering that the original data only provided the total number of vacant days in a year.

Upon breaking down the data by neighborhoods, we observed that most AirBNB properties, when aggregated by neighborhood, exhibited vacancy rates ranging from 40% to 60%. The overall mean vacancy rate for all AirBNB properties stood at 48.12%. In contrast, the Census Data indicated that the vacancy rate for conventional rental units in San Francisco in 2023 was only 6.6%. This substantial difference could potentially have implications for pricing, as it suggests a disparity in supply and demand within the area.

### Q3 Analysis:

The third question we aim to address pertains to the average income generated from an AirBNB listing in comparison to the average household income of residents in the San Francisco area. To answer this query, we again employed data scraped from live AirBNB listings and compared it with readily available data from the United States Census.

In our quest to gather the necessary data for comparing incomes in the San Francisco City area, we singled out the nightly rate for each AirBNB listing from the scraped data. By performing a simple calculation, we converted the nightly rate into an annual rate by multiplying it by 365. We then categorized these listings to align with the United States Census data for ease of visualization. After careful data analysis, we discovered that out of 7,418 total listings, a significant portion remained vacant for a substantial part, if not the entirety, of the year covered by the AirBNB scrape.

Our analysis revealed that the average yearly income per AirBNB listing was approximately $66,000, significantly lower than the mean household income in the city, which is approximately $184,000. It's important to note that this analysis is based on individual AirBNB listings and doesn't account for hosts who may have multiple properties for rent simultaneously. Future analyses should consider aggregating the income from hosts with multiple listings to provide a more accurate "household" analysis, which would likely result in a higher average yearly income for listings.

Additionally, our data showed a relatively high average income despite the presence of many listings with a high vacancy rate throughout the year. This observation is significant because if these AirBNB properties were on the market as conventional rental units, they would likely have a much lower vacancy rate and, consequently, a higher actual yearly income per property.
