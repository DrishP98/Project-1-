# Project 1 - Crime Watchers

## Analysing Crime Data from WA

In this project the Western Australian crime data from the WA Police Force website will be analysed. Juypter Notebooks will be used to analyse the data which will be presented in class with a PowerPoint Slideshow. The following trends will be looked at:

* Does population or immigration affect the overall amount of crime in WA?
* What are the highest types of crimes in WA? What are the trends seen in areas and years for different types of crimes?
* What are the highest and lowest crime locations in WA?
* What was the top year for crime? Are there any yearly or monthly patterns?

## Team

* Drishti Patel
* Hail Hijo
* Mel Burge
* Tyson Horsewell

## Summary of findings

#### Types of crimes: 
Types of crimes were visualised using categories due to a large number of individual crimes making results less reader friendly and much diffiuclt to interpret. The data had some columns which were additions of others like metroplitan and rgeional or like miscellaneous crimes, which were filtered out to make the date more valuable. The highest 5 types of crimes (in type categories) were Stealing, Property Damage, Burglary, Drug Offences and Fraud and Related Offences, in that order. Stealing was a large (30% of the total) portion of the total. Certain types of crimes had much higher numbers and some had very minimal therefore an outlier test was conducted and it was revealed that there were no outliers in this set. Cannington and Perth had high rates of Fraud related offenses, followed closely by Fremantle and Mirrabooka. Midland and Perth had higher Graffiti crimes than others. Drug related crimes were higher in Joondalup, Perth and the South-West. Stealing and burglary were similar in that they were prominent in metro areas than regional, likely reflecting population size. Non-Family assault was higher in Perth than other areas.
Family assault was highest in Kimberley, followed by Mandurah and Midland. Fraud related crime was lower in 2007-2012 compared to then onwards. It was highest in 2018. Graffiti was higher in 2007-2010 and has since dropped in numbers. Drug offences were higher in 2014-2021.
Stealing remains high and reasonably consistent over the years. Burglary remains consistently present across the years however drops in numbers from 2020 onwards, may be due to lockdown/Covid-19. Family assault has been increasing over the years.

## Highest and lowest Crime Locations:
The crimes were grouped by region and then the total of those crimes over the 7 years was found. Geo_api was used to find the latitude and Longitude of these regions and then plot them on a map that was scaled by the total crimes. This allowed us to see the proximity and size of these crime locations against each other. These were placed onto a bar graph which showed the total crimes of the 15 regions. This allowed us to visualise and compare the totals against each other in an easy to interpret format. From these you can split the data set into two further categories, you have a cluster of dots near perth which is your Perth Metro area and 6 dots outside called the regional area. The total crime in the regional area was significantly lower than the metro area. This can be down to factors such as the average age in these areas being higher than in metro areas, majority of these areas being farms and people on these farms are more well off and have less desire to commit crimes and the population density of these areas being lower. Less people means less total crimes. The area that had the lowest crime in the last 17 years was Wheatbelt, followed by Great Southern . The area that had the most was Cannington, followed by Mirrabooka.



## Acknowledge the limitations of the data / analysis

*	Only one source of crime data
*	Political bias in the data
*	Under or over reporting of crime in the data
*	Location data may not be accurate to the actual location on the crime
*	The 2023 data was only until Sepetmber, all others were for all months.

## How to run the code

1. A Geoapify API key will be required to run some of the project
2. There are two folders with CSV files crime-data and other-data
3. Load each of the files analysis-1.ipynb and analysis-2.ipynb into Juypter in the dev environment
4. Each of the files should be able to be run to display the results

## References

* https://www.police.wa.gov.au/Crime/CrimeStatistics https://www.abs.gov.au/statistics/people/population/national-state-and-territory-population/latest-release
* https://www.abs.gov.au/statistics/people/population/migration-australia/latest-release
* https://www.perthnow.com.au/news/wa/public-satisfaction-with-police-up-but-new-model-needs-improving-ng-36a3bbb3119fc33453283c45345f159a 
* https://www.abc.net.au/news/2016-02-11/wa-police-commissioner-backs-down-on-new-policing-model/7159736
* https://wamnnews.com.au/news/wa-police-overhauls-front-line-model-to-combat-rising-crime-rate/
* https://thewest.com.au/politics/law-and-order/secret-police-files-liza-harvey-says-frontline-2020-policing-model-was-never-given-a-chance-ng-b881236411z
* https://www.abc.net.au/news/2020-04-08/coronavirus-shutdown-sees-crime-rate-drop-in-wa/12132410

