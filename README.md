# [TITLE]
## J124 Final Project
By Olivia "Liv" Freidenreich

This project was made possible by the Board of State and Community Corrections Juvenile Detention Profile Survey. 

## Story Pitch
The Juvenile Justice system in California has changed dramatically in the past two years, following Governor Newsome's announcement that all Department of Juvenile Justice facilities will be closed by June 30, 2023. Counties who have incarcerated youth in these high-security, prison-like facilities now have to find suitable housing that abides by Title XV rules 


## Cleaning Data

Once I found my dataset, I began importing the data to my GoogleSheets document and cleaning it. I used Adobe Illustrator to copy the data into csv format and then uploaded it to google drive and pasted it sheet by sheet onto a cohesive document. 

I froze and bolded the headings on each sheet. I used the original titles for each, but made my own titles to label the bottom tabs for easy access. I also made duplicates of each sheet before I cleaned it and labeled those “Copy” and the table they were replicating.

To begin cleaning, I converted all of the percent columns into percentages and reduced the trailing zeroes so they were whole numbers. I also rounded all of the decimals of non-percentage numbers into whole numbers, because they were each representing averages of people. 


## Interviewing the Data

#### General inquiry: What is ADP and how is it calculated?
Answer found in notes section of report: “Average Daily Population (ADP) is calculated by taking a count of the number of juveniles in custody at 0600 hours each day of the month, adding these daily counts together, and dividing the sum by the number of days in each month. A one-day snapshot is the number of juveniles in custody at 0600 hours on the 15th day of the month. For the misdemeanor and felony populations the one-day snapshot each month provides an estimate of the monthly population and is used to estimate the average monthly population (AMP) for the year” (JDPS Data, March 2022).

Other information: “JuvenileCamps/Ranches only house Post-Disposition juveniles, therefore their Total ADP is only composed of Post-Disposition juveniles” (JDPS Data, March 2022). 
This is why in every table for Camps/Ranches, there are zeroes in the Pre-Disposition columns – they are not mistakes or missing data!


### Question 1: In 2021, which California counties had the highest population of juvenile inmates on an average day? Which had the lowest population?
#### Analysis Process:
1. Sorted column B (“Average Daily Population 2021”) in Table 4 (“2021CountiesJuvenileFacilities”) from Z to A. This revealed which counties had the highest and lowest population.
!['Name I give the image','Alt text desscribes the image'](/File path to the image OR an image URL)
[insert 2 images: J124 Q1.1 and 1.2]


### Question 2: Which counties are closest to Berkeley, California? Where do they fall in the 2021 data of incarcerated youth? Look at ADP and differences between Pre and Post Disposition.
!['Name I give the image','Alt text desscribes the image'](/File path to the image OR an image URL)
[census ss]
1. I used the Bay Area Census website for a map of Bay Area counties. 
2. I chose Alameda County, the county Berkeley resides in, as well as 4 neighboring Bay Area counties: Contra Costa, Marin, San Francisco, and San Mateo. 
3. I created a pivot table of Table 4 and added "Counties" to the Rows section. In the values section, I put "ADP (Average Daily Population) 2021," "Pre-Disposition as a Percent of ADP," and "Post-Disposition as a Percent of ADP" and selected "SUM" of each category. 
4. I sorted the Counties row by each of my three values in descending order, so the table showed the county with the highest numbers at the top. I highlighted to see where my 5 Bay Area counties fell in each category. 
[3 ss at 3:15pm]

My Bay Area counties were 




!['Name I give the image','Alt text desscribes the image'](/File path to the image OR an image URL)
