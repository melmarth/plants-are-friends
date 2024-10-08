# Plants are Friends
Capstone project for NSS Aug 2024 <br>
Link to the published dashboard: [Open Plant Finder](https://app.powerbi.com/view?r=eyJrIjoiYjAzOTc4ZjEtYjAwNi00ODhjLTgyOTUtYTE3NThmMGM1MmRhIiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9)

## Executive Summary
Few people don’t know the disappointment of adopting a houseplant only to have it die. Water, light, soil acidity, it can be tricky. Maybe you just need to choose the right plant, but how? 

## Motivation
Plants can make us happier and even more productive! We spend on average 34.4 hours per week in the office, more if our office happens to be our home. Plants can make such important locations better. They also make great gifts! Even if you only know the recipient slightly, a well-chosen plant can bring them joy. Especially if they have a record of killing plants; then they need a steady supply!

 - Article for improves mental health:
	de Seixas M, Williamson D, Barker G, Vickerstaff R. Horticultural therapy in a psychiatric in-patient setting. BJPsych Int. 2017 Nov 1;14(4):87-89. doi: 10.1192/s2056474000002087. PMID: 29093958; PMCID: PMC5663021.
 - Article for improves productivity:
	Ostner, S. W. (2021). Biophilia hypothesis: The benefits of nature in the workplace. In R. Appel-Meulenbroek & V. Danivska (Eds.), A handbook of theories on designing alignment between people and the office environment (pp. 169–180). Routledge/Taylor & Francis Group. https://doi.org/10.1201/9781003128830-15

## Data Questions
Violet is opening a plant shop staged as a house with different levels of light so that customers can choose a plant based on the "room" in the store it is in. She has a list of 235 popular houseplants she would like to sell. Before she can choose her location and start sourcing supplies, she needs to know the following:
 - How many plants will be in each room?
 - How much space will she need for each lighting condition
 - Which plants require high maintenance? Can they all be in the same room?
 - What types of soil will she need to purchase and how much of each mix will be needed? 
 - How many "toxicity", "high maintenance", and "tolerates neglect" signs would she have to order?
 - How will customers find the right plant for them (dashboard)?

## Minimum Viable Product (MVP)
Must Have:
 - Tool to find a plant based on light, water, and care required
 - Answer to supplies and space questions

## Data Sources
Data sources – Web scraping from two sites and manual fill of a few missing data points.
1. https://houseplantsexpert.com
2. https://www.gardenia.net
3. https://brainygardener.com/

## Technology
 - Python for webscraping and data cleaning
 - Excel for some spot cleaning and filling in a few missing data points
 - PowerBI for visualizations used in slide deck and interactive dashboard (see Plant Friends Presentation.pdf for link)
 - Google Slides for presentation (includes speaker notes)

## Known Issues and Challenges
Possible challenges:
 - The API doesn’t work (it didn't, it stopped being supported around 2 years ago)
 - Web scraping provides widely varying data or insufficient data (also happened!)
 - Not all data questions can be included due to time
 - Allergies
