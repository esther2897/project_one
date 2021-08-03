# Change in Overall Homeless Population Analysis

## Background

### PIT Counts

The data referenced in this analysis is taken from PIT counts. These counts are submitted once a year by homeless shelters across the country to show how many people are using their services. This means it does not show the complete homeless population, as it would be hard to get data on all homeless persons from one source, but it does give a broad overview of the situation in each state. 

### Bed Counts and CoCs

Although they are not part of this analysis, I would like to shed some light on the bed count values and the CoC values that are available in these datasets. 

The bed count value is the total number of available beds in homeless shelters in that respective state. This can be used to see the resources that the State and community are putting into providing homeless people with some support. 

The CoC value references the state Continuum of Care programs. These programs are State-provided and give funding to homeless shelters to help them stay open and provide resources to the homeless population. This is another value that can be used to show what each state is doing to combat homelessness. 

## Showing Overall Homeless Population using US Heatmap

Using data from 2017-2020 from PIT counts, showed the total homeless population for each state with a slider to move throughout the 4 years. This allows for a quick and easy view of where the homeless populations are the highest in the United States.

![Alt text](charts/total_homeless.png?raw=true "Overall Homeless Map")

### Key Findings

1. The states with the most land mass or major cities tended to have the highest homeless populations. 

2. Most States increased their homeless population for each year in the analysis (2017-2020)

3. California has the largest homeless population, but also the most CoCs.

## Showing Change in Homeless Population using US Heatmap

Using the Change.csv file, which contains the percent change from the respective year to the most recent year (2020), we can see what year had the most increases of decreases in homeless population by state. In the analysis, the datasets are supplied to the map by year to provide a slider functionality to move through the years.

![Alt text](charts/change_gif.gif?raw=true "Change in Homeless Homeless Gif")

### Key Findings

1. Large increases in New Mexico, California, Texas, and Arizona for each year in the analysis. 

2. Delaware has dramatic increase of 26.5% from 2019-2020. 

3. North Dakota dropped -50.3% in 2017

## Showing change in Homeless Population using Bar Chart

Using the change.csv file, created bar charts to show side by side which years had the most change for each state. This helps to show which states had steady increases all 3 years and which states had some years of decrease. 

![Alt text](charts/percent_change.png?raw=true "Percent Change Bar")

### Key Findings

1. Steady decrease in North Dakota. 

2. Steady increast in problem states (California, Arizona, New Mexico, Texas)

3. Major outlier for MP, The Northern Mariana Islands. Shows high increase in 2017, but not needed for this analysis as we are focusing on the main 50 states.

## Extra Analysis: CoCs per state using Bar Chart

Using the CoC column in the datasets, created a bar graph the show the number of CoCs provided by State per year. 

![Alt text](charts/percent_change.png?raw=true "CoC Bar")

### Key Findings 

1. The number of CoCs decreased in total throughout the time frame as the homeless population rose. 

2. California has the most CoCs in place, increasing slightly by year. 

3. New York decreased their CoCs in 2020. 

