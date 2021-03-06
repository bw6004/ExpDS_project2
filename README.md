==================================================================
##Data Science Specialization: Exploratory Data Analysis Project 2

The overall goal of this assignment is to explore the National Emissions Inventory database and see what it say about fine particulate matter pollution in the United states over the 10-year period 1999–2008. I have used the doBy,ggplot2 and data.table packages for this analysis

===================================================================
#Introduction


Fine particulate matter (PM2.5) is an ambient air pollutant for which there is strong evidence that it is harmful to human health. In the United States, the Environmental Protection Agency (EPA) is tasked with setting national ambient air quality standards for fine PM and for tracking the emissions of this pollutant into the atmosphere. Approximatly every 3 years, the EPA releases its database on emissions of PM2.5. This database is known as the National Emissions Inventory (NEI). You can read more information about the NEI at the EPA National Emissions Inventory web site.

For each year and for each type of PM source, the NEI records how many tons of PM2.5 were emitted from that source over the course of the entire year. The data thatused for this assignment are for 1999, 2002, 2005, and 2008.
Data
The data for this assignment are available from the course web site as a single zip file:
Data for source was from [a link](https://d396qusza40orc.cloudfront.net/exdata%2Fdata%2FNEI_data.zip)

===================================================================
#Variables


The following are key variables of interest  taken used:
-fips: A five-digit number (represented as a string) indicating the U.S. county
-SCC: The name of the source as indicated by a digit string (see source code classification table)
-Pollutant: A string indicating the pollutant
-Emissions: Amount of PM2.5 emitted, in tons
-type: The type of source (point, non-point, on-road, or non-road)
-year: The year of emissions recorded
Source Classification Code Table (Source\\_Classification\\_Code.rds): This table provides a mapping from the SCC digit strings int he Emissions table to the actual name of the PM2.5 source. The sources are categorized in a few different ways from more general to more specific and you may choose to explore whatever categories you think are most useful. For example, source “10100101” is known as “Ext Comb /Electric Gen /Anthracit

====================================================================
#Files 


plot\\*.png and plot\\*.r 1,2,3,4,5 and 6 shows the different graphs and files for creating the graphs respectively
The graphs shows the following
1. Have total emissions from PM2.5 decreased in the United States from 1999 to 2008? Using the base plotting system, make a plot showing the total PM2.5 emission from all sources for each of the years 1999, 2002, 2005, and 2008.
2. Have total emissions from PM2.5 decreased in the Baltimore City, Maryland  from 1999 to 2008? 
3.Of the four types of sources indicated by the type (point, nonpoint, onroad, nonroad) variable, which of these four sources have seen decreases in emissions from 1999–2008 for Baltimore City? Which have seen increases in emissions from 1999–2008? 
4.Across the United States, how have emissions from coal combustion-related sources changed from 1999–2008?
5. How have emissions from motor vehicle sources changed from 1999–2008 in Baltimore City?
6.Compare emissions from motor vehicle sources in Baltimore City with emissions from motor vehicle sources in Los Angeles County, California . Which city has seen greater changes over time in motor vehicle emissions?

==================================================================
@kenniajin
