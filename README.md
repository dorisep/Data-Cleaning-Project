

# Marathon_Analysis_Project
This project is an analysis of marathon competition data, country demographic data and regional weather data  for KU Data Analytics Bootcamp

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project was to identify emergent phenomenon from data contained in Olympic Medal data in Marathon events and other other datasets or sources that provide context and justy. 

### Methods Used
* Data Collection
* Data Cleaning
* Data Analysis
* Data Interpretation
* Data Visualization

### Technologies
* Python libraries:
    * pandas
    * matplotlib
    * requests
    * numpy
    * stats
    * Json
    * os

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modelling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)
* Data sets:
    * Kaggle
        * Olympic Medal Data - csv
        * World Marathon Majors - csv
    * CIA World Book - JSON dump
    * World Weather Online - API call

The project started by exploring 100 years of Olympic marathon medal data and noticed the sudden rise and pronounced success of two African nations, Ethiopia and Kenya. Journalists and acedemics had looked into this however there was little to no data involved in there analysis. Consistent in the hyposthesis found in these sources were interests in the influence of demographics and benefit of climate and geography in training. 

Initially there were challenges in cleaning the Olympic data, isolating the Marathon results, merging this with the data from the World Marathon Majors and standardizing labels and metrics involved. In order to collect the pertinent demographic data of each of the countries explored a JSON dump from the CIA World Book was sourced. In order to collect climate data an API call was utlized to gather 5 years of weather data for cities that held either major races or the olympics. The weather data for the African countries was approximated by refrencing their respective capital cities.


## Needs of this project

- data exploration/descriptive statistics
- data processing/cleaning
- data visualization
- writeup/reporting


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing DSWG Members

**Team Leads (Contacts) : [Full Name](https://github.com/[github handle])(@slackHandle)**

#### Other Members:

|Name     |  Slack Handle   | 
|---------|-----------------|
|[Full Name](https://github.com/[github handle])| @johnDoe        |
|[Full Name](https://github.com/[github handle]) |     @janeDoe    |

## Contact
* If you haven't joined the SF Brigade Slack, [you can do that here](http://c4sf.me/slack).  
* Our slack channel is `#datasci-projectname`
* Feel free to contact team leads with any questions or if you are interested in contributing!
