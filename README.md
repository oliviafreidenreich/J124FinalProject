# [TITLE]
## J124 Final Project
By Olivia "Liv" Freidenreich

This project was made possible by the Board of State and Community Corrections Juvenile Detention Profile Survey. 

## Story Pitch
The Juvenile Justice system in California has changed dramatically in the past two years, following Governor Newsome's announcement that all Department of Juvenile Justice facilities will be closed by June 30, 2023. Counties who have incarcerated youth in these high-security, prison-like facilities now have to find suitable housing that abides by Title XV rules 


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


### Question 1: In 2021, which California counties had the highest population of juvenile inmates on an average day? Which had the lowest population? Which individual counties had the most drastic differences between their misdemeanor and felony charges? Which had the biggest differences between pre-disposition inmates and post-disposition inmates?
#### Analysis Process:
1. Sorted column B (“Average Daily Population 2021”) in Table 4 (“2021CountiesJuvenileFacilities”) from Z to A. This revealed which counties had the highest and lowest population.

<img width="253" alt="Counties with the highest and lowest average daily populations. Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third." src="https://user-images.githubusercontent.com/109619870/183314469-7595461f-b063-47e2-b83a-b0d6bfb9bbd3.png"> <img width="253" alt="Yolo, Tehama, and San Benito counties have the lowest ADP" src="https://user-images.githubusercontent.com/109619870/183314327-922e1f0e-f2af-4d22-95e6-4c6ba89d2a2d.png">

> Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third, while Yolo, Tehama, and San Benito counties have the lowest ADP. 

2. To answer the second part of this question, I sorted the Pre-Disposition by Percent of ADP column A-Z, and verified my findings by then sorting the Post-Disposition by Percent of ADP column by Z-A. 
    i. I verified my numbers like this because I didn't create the percentage calculations. I first wanted to be sure that the percentages added to 100%, because inmates can either be pre- or post-disposition (there is no room for nuance), and also be sure that the values were the most extreme in each column. 

<img width="613" alt="Merced with 16% Pre-Disposition and 84% Post-Disposition" src="https://user-images.githubusercontent.com/109619870/183328764-fc97c4bf-2c0a-4f25-84db-7f1f72dae955.png">
<img width="613" alt="Santa Cruz with 88% Pre-Disposition and 12% Post-Disposition" src="https://user-images.githubusercontent.com/109619870/183328820-dc646753-d604-499d-9852-dbdccebba657.png">

> Merced and Santa Cruz counties have the largest range in their pre-disposition and post-disposition population totals. Across all types of facilities (juvenile justice facilities run by the state or county, juvenile halls, and camps or ranches), Merced held large numbers of youth _after_ a conviction, and few were awaiting disposition. This dataset doesn't answer where arrested youth are held or if they are held in custody at all, but I am curious to know why this difference is so drastic. Santa Cruz was on the opposite side of Merced: a large number of youth in juvenile centers are awaiting their disposition, but few in-custody have already been through the court process. Again, this dataset doesn't answer the obvious question – why – but it is a striking point nonetheless. 

3. I solved the misdemeanor and felony charges part of the question similarly to the above question. Sort the data set using the columns that report percentage totals, not actual totals. 

<img width="1163" alt="Butte County with 0% misdemeanor charges and 100% felony charges" src="https://user-images.githubusercontent.com/109619870/183330053-35446840-bc2a-42eb-a0ad-afd2b99877ac.png">
<img width="1163" alt="Del Norte County with 85% misdemeanor charges and 15% felony charges" src="https://user-images.githubusercontent.com/109619870/183330085-c34d1b7d-7ea2-4ede-8b53-41a059ec40e0.png">

> I should point out here that although these percentages are striking, due to the large range they contain, the actual population numbers of youth is small, so the percentages are drastic. This is the same for the previous question. Here, we would be rational to find the 0% to 100% range between misdemeanor and felony charges in Butte County significant. But upon closer look, there are only 11 individuals total in the population. We should take these ranges with a grain of salt, because they represent such a small amount of people. If the population was over 100, for instance, the percentages would matter more – we would have more credibility in taking this as a pattern, rather than chance. 

### Question 2: Which counties are closest to Berkeley, California? Where do they fall in the 2021 data of incarcerated youth? Look at ADP and differences between Pre and Post Disposition.

![J124BayAreaCounties](https://user-images.githubusercontent.com/109619870/183314522-864afd9a-e8d7-4202-a1fa-814557ae94e2.gif)

#### Analysis Process:
1. I used the Bay Area Census website for a map of Bay Area counties (pictured above). 
2. I chose Alameda County, the county Berkeley resides in, as well as 4 neighboring Bay Area counties for my study: Contra Costa, Marin, San Francisco, and San Mateo. This felt like a good amount of counties (importing the data sheet by sheet was very time-consuming so I wanted to narrow my data focus) and it included Marin, which is an area I know to be very different than Alameda county in terms of demographics: racial diversity and economic status in particular. 
3. I created a pivot table of Table 4 and added "Counties" to the Rows section. In the values section, I put "ADP (Average Daily Population) 2021," "Pre-Disposition as a Percent of ADP," and "Post-Disposition as a Percent of ADP" and selected "SUM" of each category. 
    i. I decided to use the percent of overall ADP for both pre- and post-disposition instead of the whole number because I wanted to avoid creating outliers or dramatically different data points due solely to the varying populations of counties and facilities. Comparing the raw population numbers could have created these issues. Using the _percentages_ for these values was an equalizer for the data. 
4. I sorted the Counties row by each of my three values in descending order, so the table showed the county with the highest numbers at the top. I highlighted to see where my 5 Bay Area counties fell in each category (these counties will be referred to as "Bay Area Counties" from here on).

<img width="300" alt="Counties sorted by ADP" src="https://user-images.githubusercontent.com/109619870/183314669-6e761f39-1b7f-4d1f-8da1-14d7b0302aa1.png"> <img width="300" alt="Counties sorted by Pre-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314671-416485c7-8e7e-406e-90a4-9de27fd77e05.png"> <img width="300" alt="Counties sorted by Post-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314674-b1b09c84-9963-4b27-86ce-a2e5a4845acc.png">

> explanation of Q2 answer

### Question 3: Let's look at data from 2002 – 2021 across all California counties. How does the average population compare across both _population counts taken_ and _types of facilities_?

1. To look at this data, I duplicated Table 1 which held the data of statewide sum of populations within juvenile facilities from 2002 to 2021. 
2. I then copied and pasted in the data from the statewide combined population of juvenile halls and of juvenile camps/ranches. I would have used a VLOOKUP command if I needed to, but it was easier to just copy and paste it in, because the data was all sorted by year from 2002 – 2021. 
3. 
4. My new dataset looked great!



<img width="338" alt="Screen Shot 2022-08-07 at 8 21 09 PM" src="https://user-images.githubusercontent.com/109619870/183331888-ef7d8bfc-4d3b-4562-b203-936fed7e17ca.png">


