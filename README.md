# Power BI Project
# Financial Data Analysis 

Financial Data Analysis PowerBI Dashboard
A project that utilizes Microsoft PowerBI to analyze financial data and visualize sales, cost price and profits through an interactive dashboard.

"Data analysis is not just about presenting data, but to build a story and create a meaningful narrative from the raw data. At the end of the day, that's what analytics is all about - not about writing code, not about crunching numbers, not about memorizing formula syntax - it's about deriving meaning and context from the data and, more importantly, using it to make real change." - Chris Dutton, Maven Analytics

## Problem Description
This project deals with fictional financial data taken from Microsoft sample data and uncovering potential areas for sales,profit improvement using Power BI. By conducting a thorough Exploratory Data Analysis (EDA), we aim to identify trends, patterns, and relationships within the dataset that could inform data-driven business decisions.


## Project Goals
Here are the questions I would like the PowerBI dashboards to answer:

How many sales are made over a period of time and in total.
How many sales are made based on country, segment, product individually and combined.
How many units are sold based on country, segment, product individually and combined.
How much profit is made based on country, segment, product individually and combined.
Total discounts given on the product.
Gross profit and Net Profit over time period.
Number of units sold and profit made by each product.
Quarterly and weekly spending information.
What is manufacturing price and sale price.
How is discount is made as per dicount band.
Key factors influencing profit to increase or decrease.
In order to answer these questions, I invested time in planning the PowerBI measures I would need to create and also planned a rough outline of the dashboard visuals I wanted.

## Data Analysis Summary
Here are the dashboards that I created. If you would like to actually play around with these dashboards see the end of this readme for instructions:

<img width="688" alt="image" src="https://github.com/Roja-Reddy/Power-BI-Projects/assets/170682854/534620b3-909a-40be-947b-91ed8982b1a0">

<img width="673" alt="image" src="https://github.com/Roja-Reddy/Power-BI-Projects/assets/170682854/72de8d39-8eb4-4fbe-9140-5530aa3ca126">

## Software Used
  - Windows 10 Machine
  - Microsoft PowerBI Desktop (v2.129.905.0)
  - Microsoft Excel

## Explanation of Project Files
Here is a brief description of each file/folder found in this GitHub repository.

Financial Sample.xlsx
This is the folder that contains Excel File of Financial Data. The dates range from Sep 1 2013 - Dec 1 2014.

Finance Data Analysis.pbix
This is the main Power BI file containing the finance dashboards.

## Data Collection Methodology
I collected the data by from Microsoft https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download. It was a sample financial data given in microsoft sample data.

## Data Cleaning
Checked for values and any anomalies like null values, unique and distinct values using column profiling, column distribution, column quality.
Based on analysis made removed a few columns from data which were redundant. 

## Measure Creation & Visualizations
In order to help answer the questions listed above created a measures for net profit percentage and gross profit percentage.

For easy understanding of measures created and for user to find it friendly as a best practice placed all measures in a separate query that I created using powery query editor and named it as Measure.

Once these data was ready, I followed my planned layout above and created each visual one at a time. 

I created hierarchy for overall date, year, quarter, month, and day of week. With these one has a lot of options as to what granularity they wish to visualize their data with respect to dates.

Create few clustered Column and line chart, pie chart, donut chart, few card visuals to show overall data and most importantly slicers to filter all the data.

As the report i created was two pages I syncronized slicers on both pages.

## Conclusion
Using PowerBI I was able to visualize Financial data in an interactive way. This allowed me to drill deeper into sales and profits made and factors affecting profits.

## How You Can View My Power BI Dashboards
For those interested in actually playing around with the dashboard, here are some detailed steps to help you do so:

 ### 1. Download PowerBI

Go to this site: https://powerbi.microsoft.com/en-us/desktop/ and click the "Download Free" button in the center of the screen (this may change in the future!). There may be a prompt that asks you to download from the Microsoft Store instead, in which case simply click the button that opens the Microsoft Store and install the application from there.

Note: You DO NOT have to sign-in to use this 'Desktop' version, although if you choose to then you'll need to use a work/school email adddress.

 ### 2. Configure Some Settings

Open Power BI Desktop and simply close the large dialog window that starts. Then, go: File -> Options and settings -> Options. On the left side you'll see two general categories of options: GLOBAL and CURRENT FILE.

Under the GLOBAL options, go to 'Preview features' and de-select all options.

Under the CURRENT FILE options, go to 'Data load' and de-select the two options: (i) Update or delete relationships when refreshing data, and (ii) Autodetect new relationships after data is loaded.

Finally, again under the CURRENT FILE options, go to 'Regional Settings' and make the appropriate selection for your region.

### 3. Download My Project Files

Now that everything is set up, you simply have to download all my project files as they are into a folder on your machine, open the Power BI file (the one with .pbix extension) and have fun!

## Acknowledgements
- Creators of Microsoft PowerBI - It's a pretty amazing tool!
- Viewers of my GitHub page...Thanks for visiting!
