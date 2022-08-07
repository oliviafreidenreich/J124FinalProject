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


### Question 1: In 2021, which California counties had the highest population of juvenile inmates on an average day? Which had the lowest population?
#### Analysis Process:
1. Sorted column B (“Average Daily Population 2021”) in Table 4 (“2021CountiesJuvenileFacilities”) from Z to A. This revealed which counties had the highest and lowest population.

<img width="253" alt="Counties with the highest and lowest average daily populations. Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third." src="https://user-images.githubusercontent.com/109619870/183314469-7595461f-b063-47e2-b83a-b0d6bfb9bbd3.png"> <img width="252" alt="Yolo, Tehama, and San Benito counties have the lowest ADP" src="https://user-images.githubusercontent.com/109619870/183314327-922e1f0e-f2af-4d22-95e6-4c6ba89d2a2d.png">

> Los Angeles County has by far the largest ADP at 366 in 2021. Orange and San Diego Counties are second and third, while Yolo, Tehama, and San Benito counties have the lowest ADP. 


### Question 2: Which counties are closest to Berkeley, California? Where do they fall in the 2021 data of incarcerated youth? Look at ADP and differences between Pre and Post Disposition.

![J124BayAreaCounties](https://user-images.githubusercontent.com/109619870/183314522-864afd9a-e8d7-4202-a1fa-814557ae94e2.gif)

#### Data Analysis Process
1. I used the Bay Area Census website for a map of Bay Area counties. 
2. I chose Alameda County, the county Berkeley resides in, as well as 4 neighboring Bay Area counties: Contra Costa, Marin, San Francisco, and San Mateo. 
3. I created a pivot table of Table 4 and added "Counties" to the Rows section. In the values section, I put "ADP (Average Daily Population) 2021," "Pre-Disposition as a Percent of ADP," and "Post-Disposition as a Percent of ADP" and selected "SUM" of each category. 
4. I sorted the Counties row by each of my three values in descending order, so the table showed the county with the highest numbers at the top. I highlighted to see where my 5 Bay Area counties fell in each category. 

<img width="300" alt="Counties sorted by ADP" src="https://user-images.githubusercontent.com/109619870/183314669-6e761f39-1b7f-4d1f-8da1-14d7b0302aa1.png"> <img width="300" alt="Counties sorted by Pre-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314671-416485c7-8e7e-406e-90a4-9de27fd77e05.png"> <img width="300" alt="Counties sorted by Post-Disposition as a Percent of ADP" src="https://user-images.githubusercontent.com/109619870/183314674-b1b09c84-9963-4b27-86ce-a2e5a4845acc.png">

My Bay Area counties were 




