# Build interactive visualization using Tableau

## Data available from U.S. Census

- We can search and obtain data from [data.census.gov](https://data.census.gov/)

- Topics covered by the U.S. Census
  
![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/63-census-topics.png)

- Geographical units covered by the U.S. Census

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/64-census-geographies.png)

## Downloading and cleaning data from the U.S. Census

- The primary thing a user needs to clean after downloading data from the U.S. Census is the *double-headings* issue
  - Most table processing software, such as MS Excel and Google Sheet, can only handle a tabular file with one heading line before the first line of data
  - Even if the software allows users to specify which line to start with, it is easier to have a meaningful name

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/65-census-dbl-heading.png)

- **Goal of data preparation**
  - Keep only one line as the table header
  - Have a meaningful column/field name

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/66-census-data-cleaned.png)

### How to download and clean data from the U.S. Census

- A [StoryMap](https://arcg.is/4yiG1) showing how to download and prepare data from [data.census.gov](https://data.census.gov/)

## Obtain a cleaned version of data for this tutorial

- We have prepared a cleaned version of data
  - [county-commute-data.csv](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/data/county-commute-data.csv)
  - [county-employment-industries.csv](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/data/county-employment-industries.csv)
- Open `county-commute-data.csv` to inspect the content of data

| Type | Field Name |
| :--------: | :-------: |
| Geography | `GEO_ID` |
|  | `FULL NAME` |
|  | `STATE` |
|  | `NAME` |
| Metrics | `TOTAL WORKERS` |
|  | `NOT WORK FROM HOME` |
|  | `DRIVE` |
|  | `CARPOOL` |
|  | `PUBLIC TRANSIT` |

## A brief look at Tableau

- Create aggregation, prediction, and visualization of data in an intuitive way
  - No coding skill needed to create data aggregation, basic stats, and prediction
  - No background on geospatial technology needed to create a map

- Work flow in Tableau

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/71-tableau-workflow.png)

- An example of a sheet in Tableau

![Alt Text](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/70-sheet-anim.gif)

- An example of interactive feature in dashboard

![Alt Text](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/69-dashboard-anim.gif)


## Get prepared to work in Tableau Public

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/67-tableau-pub-logo-scr.png)

- A free version of Tableau
  - Has a web and desktop version
  - Desktop version can handle large datasets faster

- Create an account for Tableau Public to start using

- Start working
  - Login to your Tableau Public account
  - Click **Create** to select **Web Authoring**

![img](https://github.com/jiashenyue/data-viz-non-coders-boot-camp/blob/main/pictures/68-tableau-start.png)

## Create your first Sheet in Tableau Public
