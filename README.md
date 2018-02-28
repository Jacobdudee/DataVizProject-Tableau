# Data Visualization Project: Create a Tableau Story

#### Jacob Dodd

The final visualization for this project is available at this link:

https://public.tableau.com/profile/jacob.dodd#!/vizhome/FlightDelayTrends2008-2017/FlightDelayBreakdownVsAverage

## Summary

Arriving flight delays are a major inconvenience for fliers in the United States, and being the curious sort, I wanted to explore why flights were delayed, and how that has changed on a year to year basis. To accomplish this, I downloaded and analyzed data from the Bureau of Transportation Statistics, which had information on total delays and the categories responsible.

This chart breaks down yearly total flight delays by the category marked responsible (security, late arrival, etc.) and compares it to the average time a flight was delayed. On the left y-axis, each the sum of each delay category (in minutes) is plotted, with the area under each line corresponding to how much of the total it is responsible for.

## Design 

I wanted to show which categories of flight delays were most responsible, so I had to plot each of the 5 categories in the same plot while also demonstrating their relationship with each other. To accomplish this, I used a line area plot, which plots the area below the line (in this case representing category) until it reaches the next line. The area demonstrates the share of the total delays each category is responsible for, so the viewer gets a quick idea of the categories with the largest share. 

There were two choices for me, I could show how percentage changed, or show the total. I presented both iterations to my girlfriend, and the one that made the most sense intuitively to her (and what she said looked better) was showing the total, and not the percentages. In the end, I went with the total. 

The total chart also kept the door open for a couple more dimensions, with the total yearly delay represented by the height of the left y-axis, and also the opportunity to add more information and plot the average delay by flight on the right y-axis. 

## Feedback
With a passion for charts and coming from a customer service and communications background, my girlfriend was a good resource as she represented a likely non-technical audience. 
I first showed her a line chart, with each line representing a delay category. She said that it made sense, but did not convey how they were related. I agreed, and stacked each line to make a line area chart. 

When making the line area chart, I realized I should make 2 versions: one showing total delay with each category, and the other showing the yearly percentage of each category as part of Total Delay minutes. With the percentages not changing much on a year to year basis, she stated that the percentage plot did not convey that much useful information. Due to this feedback, I went with the total chart.

## Resources:

1. Data from BTS: 
https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp

2. Udacity's Data Analyst Nanodegree:
https://www.udacity.com/course/data-analyst-nanodegree--nd002

3. How to make a dual-axis plot:
http://kb.tableau.com/articles/howto/dual-axis-bar-chart-multiple-measures

4. Tableau Public:
