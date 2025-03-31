---
layout: post
title:  "How has drug-related crimes in San Fransisco changed over the years?"
date:   2025-03-29 16:18:24 +0100
categories: blog
author: Khaled Zamzam & Fadl Matar
---

## Introduction
Some crimes across San Francisco, particularly drug and narcotics-related offenses has undergone a
significant transformation in recent years. In this data story, we'll explore how drug-related crimes have changed over the years, how different neighbourhoods have been
impacted, and what factors may have driven these changes.

# About the data
This analysis is based on publicly available crime data from the San Francisco Police Department (SFPD). The dataset includes detailed records of all reported crimes across the city, such as theft, assault, vandalism, and more. For this story, we’ve focused specifically on incidents categorized as drug or narcotics-related offenses. The dataset spans from 2003-2024, and includes fields such as date, location, and incident category, allowing us to track and visualize how drug-related crime has changed over time.

## A Citywide Decline
Let's begin by taking a look at the overall number of arrests related to drug and narcotics
offenses. Over the past decade, San Francisco has experienced a clear and dramatic decline in
drug- and narcotics-related crimes. Figure 1 shows the total number of these offenses
recorded each year across the city. It highlights just how significant the drop has been,
with arrest numbers in recent years falling to nearly half or even less, compared to levels before 2010. 
Moreover, we see that the number of crimes were at it lowest in 2020 and 2021, most likely due to COVID-19.

![image tooltip here](/assets/barchat.png)
<p>Figure 1 - Number of repoted drug/narcotics crimes in San Fransisco per year from 2003 to 2024</p>

## District Analysis

# Where are the hotspots?
Further in our analysis, we investigated which neighborhoods are most affected by drug cases over the past two decades. Figure 2 illustrates that the top 3 most affected districts are Tenderloin, Southern and Mission, with Tenderloin having more than double the number of cases compared to each of the other two.

{% include map.html %}

<br>
<p style="margin-top:40px">Figure 2 - The distribution of reported drug crimes across the city from 2003 to 2024, with darker areas representing higher totals. 
By hovering over the map you can see the total number of drug crimes for each district. </p>

# Drug-Related Crime Trends by District
While the overall decline in drug-related arrests across San Francisco is clear, it doesn’t tell the whole story. When we look at the city district by district, some areas stand out more than others. The interactive map in Figure 3 shows how arrest patterns have shifted over time across the city’s districts, highlighting which areas have been most affected, and how that has changed in recent years.

<link rel="stylesheet" href="http://cdn.pydata.org/bokeh/release/bokeh-1.4.0.min.css" type="text/css" />
<script type="text/javascript" src="https://cdn.pydata.org/bokeh/release/bokeh-1.4.0.min.js"></script>
<script type="text/javascript">
    Bokeh.set_log_level("info");
</script>

{% include bokeh.html %}
<p style="padding:10px">Figure 3 - Drug-related arrests by district over time. The slider allows comparison of arrest trends across neighborhoods throughout the years.</p>

As Figure 3 illustrates, the Mission District has experienced a significant decrease in reported drug-related crime over the past two decades. One contributing factor might be the gentrification of the district, which increased during San Fransisico's tech booms and brought significant changes to the neighbourhood [[1]].

Tenderloin has remained the district with most visible drug activity in San Francisco. Like other districts, drug-related arrests in Tenderloin have also noticeably declined. However, in the recent years (2022-2024), there has been a noticeably increase in number of arrests, which can be due to the increased police activity in the area [[2]].


## Conclusion
In this data story, we have explored the trends in drug-related crime in San Francisco - how the number of reported cases has changed over time, and which districts have been most affected. We can conclude that drug-related crimes have dropped significantly over the past two decades. Tenderloin, Southern, and Mission are the most affected districts having the highest number of reported cases, with Tenderloin remaining the city's primary hotspot for drug-related activity. 

The numbers don't tell the whole story. While arrests may have gone down that doesn't always mean the problem is gone, in some cases it may have been relocated somewhere else.

## References
1. [Newsweek Magazine - Tech Boom Forces a Ruthless Gentrification in San Francisco](https://www.newsweek.com/2014/04/25/tech-boom-forces-ruthless-gentrification-sanfrancisco-248135.html)
2. [The San Francisco Standard - Drug markets persist downtown despite thousands of arrests, police crackdown](https://sfstandard.com/2024/08/28/san-francisco-drug-markets-post-crackdown)


[1]: https://www.newsweek.com/2014/04/25/tech-boom-forces-ruthless-gentrification-sanfrancisco-248135.html
[2]: https://sfstandard.com/2024/08/28/san-francisco-drug-markets-post-crackdown
