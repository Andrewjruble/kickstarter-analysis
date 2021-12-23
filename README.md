# Kickstarting with Excel

## Overview of Project

An up and coming playwright, is attempting a fundraiser for her play *Fever*. Since Louise is new to Kickstarters, she is looking gather insight on past fundraisers in order to determine what a realistic goal shoud be when doing hers.

### Purpose

Using Excel, crowdfunding data will organized, sorted and analyzed to figure out any metrics that made past fundraisers successful. Louise can apply these ideas to her own Kickstarter, setting her up for success.

## Analysis and Challenges

### An analysis was performed on two catergories:

#### Analysis of Outcomes Based on Launch Date

The goal was to visualize campaign outcomes ("successful, "failed," and "canceled") versus launch date (month). This was accomplished using a pivot table. By adding filters for the parent category and year, the data could be quickly organized in ways that allowed Louise to be as specific or as general as neccessary. A line chart was derived from the pivot table, using months as the X-axis and outcomes as the Y-axis. The line chart summarized the pivot table and made it easier to quickly to compare the variables, as well as see trends:

![Theater_Outcomes_vs_Launch](/resources/Theater_Outcomes_vs_Launch.png)

Having this infomation summarized what month performed the most successful campaigns 

### Analysis of Outcomes Based on Goals

For this analysis, eight different columns were made:
  - Goals (Ranging from <1,000 to >50,000 in increments of 5,000) defined the parameters for the other columns
  - Number Successful
  - Number Failed
  - Number Canceled
  - Total Projects
  - Percentage Successful
  - Percentage Failed
  - Percentage Canceled
  
With data filtered for "plays" as the subcatergory, the three "numbers" were filtered from the "Outcomes" column using the "Countif" function. This provided numerator with the "Total projects" column being the denominator when calculating the percentages in the next three columns. With the data organized in such a way, a line chart was again made to help visualization. The three percentage columns were graphed vs goal amounts:

![Outcomes_Based On Goal](/resources/Outcomes_vs_Goals.png)

This provided data on the success of the outcome based on the dollar value of the initial goal.  


### Challenges and Difficulties Encountered

While trying to become more familar with Excel, one of the major struggles involved pulling functions from different worksheets. It was a struggle at first to tab back and forth between while making sure to select the right information. This was essentially worked out with practice/trial and error. For the "Outcomes Based on Goal" deliverable, entering the "Countif" formula manually was difficult. Looking back, it may have been possible to format the "Goal" column differently, making it "selectable" instead of having to handtype the values in.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1) May (late Spring, early Summer), had both the most launched Kickstarters and most successful Kickstarters. 
  2) December was the month with least amount of launches and the number of failures in that month were nearest to it's successes. 

- What can you conclude about the Outcomes based on Goals?
  Assuming there was not enough data to conclusions about the upper range of the goals, 25,000 to 29,000 was the goal range with the highest success rate. 

- What are some limitations of this dataset?
  There were no specifications on other variables that may have been worth looking into. It would have been nice to see if all the kickstarters had the same pledge   time. It it unknown how popular some of the titles were prior to starting the fundraiser as well. Also, more samples at the higher ranges would have provided more  solid, reliable data. 

- What are some other possible tables and/or graphs that we could create?
  1) Theater outcomes based on launch date using years could give an idea of what direction Kickstarters are heading into the future. Using this method, it could be    helpful to make a trend line and see what average pledge would be going into the future. A line chart would be most helpful in this situation. 
  2) A bar graph showing average donation vs total pledged amount of successful campaigns could give insight on marketing strategies. Several small donations         reaching a goal, vs a few large ones could give an idea on how to much to ask for from each individual 



https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
