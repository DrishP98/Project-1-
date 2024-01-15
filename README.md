# Project 1 - Crime Watchers

## Analysing Crime Data from WA

In this project the Western Australian crime data from the WA Police Force website will be analysed. Juypter Notebooks will be used to analyse the data which will be presented in class with a PowerPoint Slideshow. The following trends will be looked at:

* Does population or immigration affect the overall amount of crime in WA?
* What are the highest and lowest crimes in WA?
* What are the highest and lowest crime locations in WA?
* What was the top year for crime? Are there any yearly or monthly patterns?

Team

* Tyson Horeswell
* Drishti Patel
* Hail Hijo
* Mel Burge

Summary of findings

Tyson - Is population or  immigration correlated with crime?
No correlation was found between crime and either population or immigration with quarterly data between the 2010 to 2022.
Regression analysis showed a weak r2 value for both data points with values of 0.13 for immigration and 0.16 for population growth.
The higher crime between 2016 to 2020 was to do with policing policy and low of 2020 a result of COVID-19.

Drish - Types of crimes across the years
Cannington and Perth had high rates of Fraud related offences, followed closely by Fremantle and Mirrabooka.
Midland and Perth had higher Graffiti crimes than others.
Drug related crimes were higher in Joondalup, Perth and the South-West.
Stealing and burglary were similar with higher numbers in metro areas than regional, likely reflecting population size.
Non-Family assault was higher in Perth than other areas.
Family assault was highest in Kimberley, followed by Mandurah and Midland.

Drish - Types of crimes across the regions
Fraud related crime was lower in 2007-2012 compared to then onwards. It was highest in 2018.
Graffiti was higher in 2007-2010 and has since dropped in numbers.
Drug offences were higher in 2014-2021.
Stealing remains high and reasonably consistent over the years.
Burglary remains at a consistent high until a drop in numbers from 2020 onwards, this may be due to lockdown/Covid-19.
Family assault has been increasing over the years.

Hail - Total Crimes Across Regions
The 6 Rural locations have the Lowest total Crime
This can be down to many factors such as population density, older average population
These Areas bring down the average well below the mean.
Wheatbelt has the lowest total crimes, Kimberley being furthest away from CBD has fifth lowest.

Hail - Total Crimes Across Regions(Metro)
Average once the Rural areas had been removed is much closer in line with Median
Cannington has the highest crime, followed by Mirrabooka
These two are not close to each other
South_West, despite being in close proximity to Cannington, has significantly lower crime than Cannington.

Mel - Total Crimes For Each Year (2007-2023)
Significant Economic impacts for 2010 – Least year of crime: 
The commencement of the Mining Boom in 2010 signaled the start of a phase defined by increased incomes and a surplus of job opportunities in the mining sector. Even the 2020 lockdown amid the COVID-19 pandemic did not have as pronounced an impact on crime rates as the Mining Boom in 2010.
Significant Economic impacts for 2016 – Highest year of crime: 
During the worst economic downturn, Western Australia (WA) faced the aftermath of the concluded mining boom, finding itself in the largest deficit in its history, amounting to 3.9 billion dollars. Unemployment soared to a peak of 6.5%, reflecting the challenging economic conditions during this period.

Mel - Total Crimes For Each Month Collectively (2007-2023)
Significant Impacts for July: Least recorded crimes for the month of July. 
July's notable impacts include the lowest recorded crime rates for the month, with potential influencers being the coldest and wettest weather of the year in Western Australia (WA). Additionally, the commencement of tax returns in July might contribute to financial relief, potentially affecting crime rates.
Significant Impacts for March: Most recorded crimes for the month of March:
On the other hand, March experiences the highest recorded crimes, possibly influenced by cooler and drier weather. Contributing factors may include the financial strain from Christmas expenses and school fees, creating additional pressure on budgets during this period.

Acknowledge the limitations of the data / analysis

*	Only one source of crime data
*	Political bias in the data
*	Under or over reporting of crime in the data
*	Location data may not be accurate to the actual location on the crime

How to run the code

1. A Geoapify API key will be required to run some of the project
2. There are two folders with CSV files crime-data and other-data
3. Load each of the files analysis-1.ipynb and analysis-2.ipynb into Juypter in the dev environment
4. Each of the files should be able to be run to display the results