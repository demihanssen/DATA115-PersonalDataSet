# Personal Dataset Project

# Motivation
For the purposes of this personal data set project, I have analyzed data sets from the United States FBI of violent crimes in approximately the previous 60 years, versus the number of firearm licenses present in the United States in the same timeframe. It would commonly be expected that as the number of gun licenses increases, the frequency of violent crimes would increase. For the purposes of this project, we will only focus on these two factors, but in general it is important to note that correlation does not always equal causation. In 2021, guns are currently a “hot topic”, which is what lead me to be curious if the data would fit the mainstream narrative in regards to guns. In the crime data set, the total violent crimes include murder, rape, assault, robbery, and burglary.

# Data Process
I downloaded the data from each of their designated sources, then transposed the data in Excel so the format was easier to work with. I then noticed there were many blank/white spaces in the dataset, so I used the Find & Replace function in excel to remove those. In order to calculate correlation in the analysis portion, I combined the data from the Crime Statistics with the Firearm Licenses in the GvC Excel Workbook. Once I was satisfied with the datasets, and scanned for obvious errors/typos, I uploaded the data as a .csv file to RStudio to begin my analysis. 

# Data Sources
-The violent crime statistics were retrieved from the FBI website.
-The firearm licenses, deaths, and background check statistics were received from USA Facts website.
A more detailed summary of resources can be found below.

# Visualizations Part 1
![Firearm Licenses in United States](https://raw.githubusercontent.com/demihanssen/DATA115-PersonalDataSet/main/GunLicense.png)

![Violent Crime in United States](https://raw.githubusercontent.com/demihanssen/DATA115-PersonalDataSet/main/Crime.png)

In the line plots above, we can observe a spike in violent crimes in the early 1990’s, simultaneously the number of guns licenses is reaching a peak in the same timeframe. After the peak in violent crimes in the 1990’s we see a drastic drop in crime, as well as a significant drop in gun licenses with licenses beginning to rise again in the early 2000’s. With only these charts to base initial understanding, there does seem to be an obvious trend. Let’s take a closer look into more data to see if this trend will continue to be supported.

# Visualizations Part 2
![Firearm Background Checks in US](https://raw.githubusercontent.com/demihanssen/DATA115-PersonalDataSet/main/BackgroundChecks.png)

![Deaths Directly Related to Firearms in US](https://raw.githubusercontent.com/demihanssen/DATA115-PersonalDataSet/main/Direct.png)

I also wanted to take into account the number of background checks on firearms purchases, as well as the number of deaths directly related to firearms in the United States. In the line graph above, we can see that the number of background checks has drastically increased in the past 22 years. This could be once of the reasons we saw a steady decline in the number of firearms licenses, since increased background checks could cause increased difficulty in legally purchasing a gun. Despite the increase in background checks, and a decrease in firearm licenses, the second plot above shows that the number of gun related deaths have been steadily increasing since the year 2000.

# Analysis
![US Firearm Statistics](https://raw.githubusercontent.com/demihanssen/DATA115-PersonalDataSet/main/StatisticCor.png)

In the analysis above, I was curious to know the correlation between the number of firearms licenses in the US and the number of violent crimes. I did not include the other two datasets previously discussed on background checks and deaths directly related to gun use because the time frames were slightly different. Above we can see that the highest correlation of 0.815 is between firearms licenses and murder, while the next highest correlation of 0.759 is between firearms licenses and total violent crimes.

# Resources
Federal Crime Data. 4 Sept. 2018, ucr.fbi.gov/crime-in-the-u.s/2019/crime-in-the-u.s.-2019/additional-data-collections/federal-crime-data. 

USAFacts. “Firearm Background Checks.” USAFacts, usafacts.org/data/topics/security-safety/crime-and-justice/firearms/firearm-background-checks/. 

USAFacts. “Firearms Licenses.” USAFacts, usafacts.org/data/topics/security-safety/crime-and-justice/firearms/firearms-licenses/. 

USAFacts. “US Gun Deaths.” USAFacts, usafacts.org/data/topics/security-safety/crime-and-justice/firearms/firearm-deaths/. 



