# Bay Area Juvenile Justice
## J124 Final Project
By Olivia "Liv" Freidenreich

This project was made possible by the Board of State and Community Corrections Juvenile Detention Profile Survey. 

## Story Pitch
The Juvenile Justice system in California has changed dramatically in the past two years, following Governor Newsome's announcement that all Department of Juvenile Justice facilities will be closed by June 30, 2023. Counties who have incarcerated youth in these high-security, prison-like facilities now have to find suitable housing for the youth that formerly lived in DJJ. Strict Title XV rules that outline requirements for hallway width, recreational time, and maximum cell hours are proving difficult to satisfy, so youth remain locked in juvenile halls and juvenile camps/ranches for the meantime.

I plan to look at data that breaks down population size of California incarcerated youth in the past 20 years. The data breaks down population between the three prior specified facilities and also between the status of youth trials. This project feels like the first part of a longer series of data analysis, analysis that will be possible after the next few years when I can look at how the DJJ's closure has impacted other youth facilities.

### Sources
**Laurel Arroyo**, _Alameda County Office of Public Defenders_ and _President of the Volunteer Board of Pacific Juvenile Defender Center_ <br>
(415) 595-3795<br>
Ms. Arroyo has worked as a Public Defender for over 20 years and has defended youth for a decade. She is the director of a group that writes and advocates for bills that protect the rights of juvenile offenders and increase their chances of rehabilitation. She knows the justice system very well and without breaking confidentiality, can tell me about the shortcomings of the system and facilities and how they have impacted her clients. 

**Tracy Gallardo**, _Legislative Assistant to Supervisor Shamann Walton_<br>
(415) 554-7670<br>
Ms. Gallardo has worked for the San Francisco County Board of Supervisors for years and knows the juvenile justice system very well. The Board of Supervisors are in charge of finding a replacement for the DJJ and she knows a lot about the Title XV requirements and status of finding a replacement facility. 

**Doug Styles**, _Director of Huckleberry Youth Program’s Community Assessment & Resource Center (CARC)_<br>
(415) 609-2423<br>
Mr. Styles is the Director of a community-based organization that provides diversion and rehabilitation programs for system-impacted youth in San Francisco. He is a great source for success stories of youth who have avoided lockup and have grown through rehabilitation programs. 

### Data Sources
["Alameda County At The Crossroads Of Juvenile Justice Reform"]([url](http://www.cjcj.org/uploads/cjcj/documents/alameda_cross.pdf)) by: Center on Juvenile and Criminal Justice, Ella Baker Center for Human Rights, Books Not Bars Campaign, National Center for Youth Law, National Council on Crime, and Delinquency Youth Law Center
> The Center for Juvenile and Criminal Justice has released several interesting reports, but I found this one most relevant to my focus on Alameda County. It identifies specific examples of the county failing to treat youth with care and resources and proposes solutions to the problems raised. 

[California State Association of Counties Report]([url](https://www.counties.org/sites/main/files/file-attachments/juvenile_hall_report_and_toolkit_2019.pdf)) breaks down the types of facilities in each county, how they are instructed to treat youth, and the services they offer.
> This source is important to me because it provides a fairly distanced, unbiased account of juvenile facilities in California. I want to be sure to include a variety of perspectives in my reporting and this is a pretty standard example of such a report.

[November 2021 Report on Financial Restrictions limiting Justice in Juvenile cases](November 2021 Report on Financial Restrictions limiting Justice in Juvenile cases.) by the California Policy Lab. 
> This report is a little less relevant to the topics I've been researching, but gives an interesting, factual perspective on finances impacting youth's access to justice. It is fairly short and would be good reading for background information. 

## Cleaning Data

Once I found my dataset, I began importing the data to my GoogleSheets document and cleaning it. I used Adobe Illustrator to copy the data into csv format and then uploaded it to google drive and pasted it sheet by sheet onto a cohesive document. 

I froze and bolded the headings on each sheet. I used the original titles for each, but made my own titles to label the bottom tabs for easy access. I also made duplicates of each sheet before I cleaned it and labeled those “Copy” and the table they were replicating.

<img width="1012" alt="Sample table names include Alameda Hall and Copy T1" src="https://user-images.githubusercontent.com/109619870/183314538-7199b1d9-631c-4533-8a00-44f6cebfc5a3.png">

To begin cleaning, I converted all of the percent columns into percentages and reduced the trailing zeroes so they were whole numbers. I also rounded all of the decimals of non-percentage numbers into whole numbers, because they were each representing averages of people. 


## Interviewing the Data

#### General inquiry: What is ADP and how is it calculated?
> Answer found in notes section of report: “Average Daily Population (ADP) is calculated by taking a count of the number of juveniles in custody at 0600 hours each day of the month, adding these daily counts together, and dividing the sum by the number of days in each month. A one-day snapshot is the number of juveniles in custody at 0600 hours on the 15th day of the month. For the misdemeanor and felony populations the one-day snapshot each month provides an estimate of the monthly population and is used to estimate the average monthly population (AMP) for the year” (JDPS Data, March 2022).

Other information: “JuvenileCamps/Ranches only house Post-Disposition juveniles, therefore their Total ADP is only composed of Post-Disposition juveniles” (JDPS Data, March 2022). 
> This is why in every table for Camps/Ranches, there are zeroes in the Pre-Disposition columns – they are not mistakes or missing data!


### Question 1: In 2021, which California counties had the highest population of juvenile inmates on an average day? Which had the lowest population? 
#### Analysis Process:
1. Sorted column B (“Average Daily Population 2021”) in Table 4 (“2021CountiesJuvenileFacilities”) from Z to A. This revealed which counties had the highest and lowest population.

<img width="253" alt="Counties with the highest and lowest average daily populations. Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third." src="https://user-images.githubusercontent.com/109619870/183314469-7595461f-b063-47e2-b83a-b0d6bfb9bbd3.png"> <img width="253" alt="Yolo, Tehama, and San Benito counties have the lowest ADP" src="https://user-images.githubusercontent.com/109619870/183314327-922e1f0e-f2af-4d22-95e6-4c6ba89d2a2d.png">

> Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third, while Yolo, Tehama, and San Benito counties have the lowest ADP. 

#### Visual Representation of Question 1:

![D70aQ-why-is-los-angeles-locking-up-kids-twice-as-often-as-other-counties-](https://user-images.githubusercontent.com/109619870/183396470-624f243a-c36f-4f86-ad65-62d9248387c6.png)(<"https://datawrapper.dwcdn.net/D70aQ/1/")



### Question 2: Which individual counties had the most drastic differences between their misdemeanor and felony charges? Which had the biggest differences between pre-disposition inmates and post-disposition inmates?
#### Analysis Process:
1. I sorted the Pre-Disposition by Percent of ADP column A-Z, and verified my findings by then sorting the Post-Disposition by Percent of ADP column by Z-A. 
    i. I verified my numbers like this because I didn't create the percentage calculations. I first wanted to be sure that the percentages added to 100%, because inmates can either be pre- or post-disposition (there is no room for nuance), and also be sure that the values were the most extreme in each column. 

<img width="613" alt="Merced with 16% Pre-Disposition and 84% Post-Disposition" src="https://user-images.githubusercontent.com/109619870/183328764-fc97c4bf-2c0a-4f25-84db-7f1f72dae955.png">
<img width="613" alt="Santa Cruz with 88% Pre-Disposition and 12% Post-Disposition" src="https://user-images.githubusercontent.com/109619870/183328820-dc646753-d604-499d-9852-dbdccebba657.png">

> Merced and Santa Cruz counties have the largest range in their pre-disposition and post-disposition population totals. Across all types of facilities (juvenile justice facilities run by the state or county, juvenile halls, and camps or ranches), Merced held large numbers of youth _after_ a conviction, and few were awaiting disposition. This dataset doesn't answer where arrested youth are held or if they are held in custody at all, but I am curious to know why this difference is so drastic. Santa Cruz was on the opposite side of Merced: a large number of youth in juvenile centers are awaiting their disposition, but few in-custody have already been through the court process. Again, this dataset doesn't answer the obvious question – why – but it is a striking point nonetheless. 

2. I solved the misdemeanor and felony charges part of the question similarly to the above question. Sort the data set using the columns that report percentage totals, not actual totals. 

<img width="1163" alt="Butte County with 0% misdemeanor charges and 100% felony charges" src="https://user-images.githubusercontent.com/109619870/183330053-35446840-bc2a-42eb-a0ad-afd2b99877ac.png">
<img width="1163" alt="Del Norte County with 85% misdemeanor charges and 15% felony charges" src="https://user-images.githubusercontent.com/109619870/183330085-c34d1b7d-7ea2-4ede-8b53-41a059ec40e0.png">

> I should point out here that although these percentages are striking, due to the large range they contain, the actual population numbers of youth is small, so the percentages are drastic. This is the same for the previous question. Here, we would be rational to find the 0% to 100% range between misdemeanor and felony charges in Butte County significant. But upon closer look, there are only 11 individuals total in the population. We should take these ranges with a grain of salt, because they represent such a small amount of people. If the population was over 100, for instance, the percentages would matter more – we would have more credibility in taking this as a pattern, rather than chance. 

### Question 3: Which counties are closest to Berkeley, California? Where do they fall in the 2021 data of incarcerated youth? Look at ADP and differences between Pre and Post Disposition.

![J124BayAreaCounties](https://user-images.githubusercontent.com/109619870/183314522-864afd9a-e8d7-4202-a1fa-814557ae94e2.gif)

#### Analysis Process:
1. I used the Bay Area Census website for a map of Bay Area counties (pictured above). 
2. I chose Alameda County, the county Berkeley resides in, as well as 4 neighboring Bay Area counties for my study: Contra Costa, Marin, San Francisco, and San Mateo. This felt like a good amount of counties (importing the data sheet by sheet was very time-consuming so I wanted to narrow my data focus) and it included Marin, which is an area I know to be very different than Alameda county in terms of demographics: racial diversity and economic status in particular. 
3. I created a pivot table of Table 4 and added "Counties" to the Rows section. In the values section, I put "ADP (Average Daily Population) 2021," "Pre-Disposition as a Percent of ADP," and "Post-Disposition as a Percent of ADP" and selected "SUM" of each category. 
    i. I decided to use the percent of overall ADP for both pre- and post-disposition instead of the whole number because I wanted to avoid creating outliers or dramatically different data points due solely to the varying populations of counties and facilities. Comparing the raw population numbers could have created these issues. Using the _percentages_ for these values was an equalizer for the data. 
4. I sorted the Counties row by each of my three values in descending order, so the table showed the county with the highest numbers at the top. I highlighted to see where my 5 Bay Area counties fell in each category (these counties will be referred to as "Bay Area Counties" from here on).

<img width="300" alt="Counties sorted by ADP" src="https://user-images.githubusercontent.com/109619870/183314669-6e761f39-1b7f-4d1f-8da1-14d7b0302aa1.png"> <img width="300" alt="Counties sorted by Pre-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314671-416485c7-8e7e-406e-90a4-9de27fd77e05.png"> <img width="300" alt="Counties sorted by Post-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314674-b1b09c84-9963-4b27-86ce-a2e5a4845acc.png">

> The pivot table didn’t reveal much of a pattern across Bay Area counties and their relative pre-disposition or post-disposition juveniles. There is a big difference between the raw, average data for all facilities, though. Alameda county reported 63 youth on average in 2021, while Marin county only had 6. 


### Question 4: Let's look at data from 2002 – 2021 across all California counties. How does the average population compare across both _population counts taken_ and _types of facilities_?
#### Analysis Process:
1. To look at this data, I duplicated Table 1 which held the data of statewide sum of populations within juvenile facilities from 2002 to 2021. 
2. I then copied and pasted in the data from the statewide combined population of juvenile halls and of juvenile camps/ranches. I would have used a VLOOKUP command if I needed to, but it was easier to just copy and paste it in, because the data was all sorted by year from 2002 – 2021. 
3. I then made a "Total ADP" column by adding CAFacilities ADP, CAHalls ADP, and CACamp/Ranch ADP. 
4. Once I had a Total ADP representing the average population across all 3 types of facilities, I began calculating the percentage breakdown among the three types of facilities. I was interested in learning whether one type held the majority of incarcerated youth, and if these divisions shifted over the past 20 years. 
    i. To calculate these percentages, I input “=C2/B2” into a new column, D, with C2 being the Facility ADP in 2002 and B2 being the total ADP in 2002. I then copied the formula for the rest of the column and turned the data into percentage form. 
    ii. I usually would have reduced the decimal places until my percentage was a whole number, but I was struck by the almost perfect 50% that the Facility Percent of Total ADP represented. I was convinced I made an error and rechecked the origins of my data, my transfer methods, and my calculations and continued to get an almost perfect 50%. 
5. I moved on from this confusion (though I would like to figure it out, because it seems strange that a population size would match up so perfectly year after year) and added new columns and calculated the percentage of the total ADP for juvenile halls and juvenile camps/ranches. 

<img width="888" alt="Screen Shot 2022-08-08 at 12 47 48 AM" src="https://user-images.githubusercontent.com/109619870/183366926-33ac67da-1995-4893-93dc-401949ee4844.png">

> I found that while juvenile facilities made up a strangely consistent half of the total population of juvenile centers, juvenile halls quite steadily increased in population size while juvenile camps/ranches steadily decreased. I remained curious _why_ this steady change was this way. Was it because rules and regulations surrounding populations size of detention centers are strict, so there was little room for change? Does the living assignment for youth depend on some strict measurement, like specific types of crimes committed, that would be steady enough to produce this type of data?

### Question 5: Juvenile halls are short-term lockups located in county court buildings. After the announcement of the closure of the DJJ, pressure was added to county facilities like juvenile halls to hold youth who were formerly detained at DJJ until a different solution presents itself. How does data compare across Bay Area counties' juvenile halls? Specifically look at pre- and post-disposition youth. 
#### Analysis Process:
1. I imported data from my 5 Bay Area counties and focused on their juvenile hall data only (I excluded Camps/Ranches because they only hold post-disposition youth and excluded Juvenile Facilities as well).
2. With each table sorted chronologically by year, I carefully copied and pasted in the average daily population counts for both Pre and Post Disposition for each county, checking along the way that the data was correctly transfered. 

 <img width="1300" alt="Screen Shot 2022-08-08 at 6 41 20 AM" src="https://user-images.githubusercontent.com/109619870/183431890-598fc881-f1ac-434e-b2e3-b35c2a58ae6d.png">

3. I then imported my data into Datawrapper to better visualize my data. I could see a general decrease in the average daily populations for each county and each type of detainment, but wasn't sure how dramatically it decreased over time.
4. I made these charts line graphs to illustrate individual counties and their change in a value (ADP) over time. The line graph was the best chart for these parameters. 
5. I duplicated the first graph and altered it to make the second one, because I wanted them to go one after the other so readers could easily compare the two. I copied the hex code for the colors so they matched across graphs and did my best to mimic the labeling and ALT text for each. When I tested for colorblind readers, I realized the colors I chose were good to differentiate between counties for non-colorblind eyes, but were confusing under colorblind tests. I added "texture" to the lines to show visual, non-color based differences. 
> Here are my findings, presented in graph form:

![qzG8y-bay-area-counties-are-locking-fewer-and-fewer-of-their-youth-awaiting-trial-in-juvenile-halls](https://user-images.githubusercontent.com/109619870/183430523-7671c292-20f9-4867-b8ea-0f263be6dc41.png)
[Link to Bay Area by Pre-Disposition chart](https://datawrapper.dwcdn.net/qzG8y/1/)

![1QSpM-average-daily-populations-in-bay-area-juvenile-halls-varied-for-juveniles-post-disposition-but-declined-overall-in-the-past-20-years](https://user-images.githubusercontent.com/109619870/183434814-2d1df6c0-d4c7-45a2-b816-36f5ee7dcc0d.png)
[Link to Bay Area by Post-Disposition chart](https://www.datawrapper.de/_/1QSpM/)

> My graphs show a decline in the average daily population of youth in Bay Area counties, regardless of pre or post-disposition status. 

### Conclusion
I was drawn to do this project because I am interested in juvenile justice. I became more concerned with the facilities and resources for system-impacted youth when I learned of the DJJ closure. I see myself coming back to this dataset in a few years, when we can really see the impact of the DJJ's closure on youth. By then, I am optimistic for a rehabilatative, restorative-justice based approach to helping youth stay out of the criminal justice system. 
