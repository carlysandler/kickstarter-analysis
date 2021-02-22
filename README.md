# **Kickstarting with Excel**

## Overview of Project
*A Detailed Analysis of Arithmatic & Statistical Findings: Key Performance Trends, Visualizations, and Recommendations*
---
### Purpose
The purpose of the following project was to complete a thourough analysis on a Kickstart Crowdfunding data set, a sample population of 4000+ campaigns of varying categories and subgategories--performance is measured by the correlation between launch date and funding goals. 

The data set and brief were rovded by Louise, whom required the help of an analyst to understand the relativity of her personal fundraising success as her play, _Fever_, quickly received a large enough percentage of pledges to accomplish her fundraiding goal. 

---
## Analysis and Challenges
The following delinates the process of completing the analysis brief and providing insights to Louise:

  - 1) data wrathing of raw population sample through:
     * dynamic formulas using both arithmatic and statistical functions
     * custom sorting, filtering, and conditional formatting for optimal analytical capabilities
     
  - 2) analysis of the modified Kickstarter data set with:
     * pivot tables summarizing the campaign outcomes based on launch date and campaign goal ($$)
     * pivot charts formatted as line graphs to visualize the relationship

  - 3) explanation of findings based on analysis featuring:
     * concluding results
     * duligence of data set limitations
     * recommendations for supplemental tables and graphs

__Analysis Resources and Deliverables:__

- 1. Kickstarter Campaign Key Performance Trends: Excel File Reference
  - [Kickstarter_Challenge.xlsm](C:\Users\carly\OneDrive\Desktop\data_bootcamp\analysis_projects\crowdfunding_analysis\challenge deliverables\Kickstarter_Challenge.xlsm)
- 2. Data Visualation Resources
  - [visualization_images.zip](C:\Users\carly\OneDrive\Desktop\data_bootcamp\analysis_projects\crowdfunding_analysis\visualization_data\visualization_images.zip)
 ---
### Analysis of Outcomes Based on Launch Date

The line graph below shows the relationship between the Kickstarter campaign Launch Date, defined by the specific month the campaign launched in a 12 month calendar year. There are no subfilters on year, we are specifically looking at the correlation between the month of the launch date and the count of potential campaign outcomes, defined by: sucessful, failed, or canceled  categorized by month of launch date.  Louise specifically interested in the "theater" parent category because her play belongs to this parent category. 

- ![Theater_Outcomes_vs_Launch](C:\Users\carly\OneDrive\Desktop\data_bootcamp\analysis_projects\crowdfunding_analysis\challenge deliverables\Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The next line graph, shown below, visualizes the relationship between the sub Category, plays, and the outcomes of the initial goal amounts (in dollars) of the respective campaigns that are defined as "plays" as well. Here we can get a more drilled down, bottoms up, analysis that bears a greater external validity than the "Outcomes Based on Launch Date" graph.

- ![Outcomes_vs_Goals](C:\Users\carly\OneDrive\Desktop\data_bootcamp\analysis_projects\crowdfunding_analysis\challenge deliverables\Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Because I have 3+ years of professional experience working in excel as a data analyst in the fashion industry, I did not experience any challenges when completing the analysis; however, if I were a novel data analyst, I could predict a few challenges that one would encounter. 

  For example, custom sorting and formatting pivot tables and subsequent pivot charts can be frustrating if the following due-delligence is not completed prior to conducting the analysis through these tools:
  - Formatting the "kickstarter" worksheet without proper variable headings, number format values, and formulas without dynamic array movement can make the pivot table either always unexacutable, or incorrect--if you expect to find a count and the excel defauls the function as an average or percentage, depending on how you inputed the data and formatted it in the first place, you will find youtself with wrongly calcuated data. This puts you at major risk of providing false insights, or conflated statistics, making your recommendations null and void.
  - From a pivot chart perspective, if the data variables in question are incorrectly populated in tghe first place (i.e. rows vs coulumns or x axis vs y axis), the visualization of the data and the implied relational conclusion can be misguided, especially if you are implying causation.

## Results
- Looking at Outcomes Based on Lanch Date, I can conclude that peak sucess of theater campaigns occurs in Q2, starting in April, with the max number of successful campaigns occuring in May, and constantly decreasing until September. I can also conclude that there are at least 26% more successful theater Kickstarter campaigns in totality compared to the number of failed theather campaigns, leading me to question the caustion of this relationship.

- Looking at Outcomes Based on Goals, the maxium number of failed campaigns for plays occured when the campaign goal was between $1000 and $4999, but this can be interpreted miscorrectly as a causation, when this data does not tell us enough about the statistical signficance of this data point, rather it is the median, which can only justly be infered to occur because the 1000 to 4999 goal is the most popular kickstarter goal in the plays subcategory--we can see that we can also say the same about the max number of successful campaigns. Another findiging is that although there is the greatest number of data points within the 1000 to 4999 goal range, play campaigns are least likely to fail if they have goals at 4999 or less. 

-Besides the limitation of unknown causation described above, another limitation of the dataset is that we define launch date in the analysis as month, and we do not adjust our analysis to weigh the importance of quarterly or annual performance comp trends. We cannot give Louise a confident caustation of camaign outcomes based on launch date when within the definition of launch date, extraneous variables such as cyclical ecoonomic impacts and social media's marketing influence and influx of exposure in the later half of the 2010s. This could definitely skew the dataset and clutter the analysis to not probably compare at a net net level, the KPIs in subject.

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we can create?



#### Recommendations for Louise
1.
 -
2. 
 -
