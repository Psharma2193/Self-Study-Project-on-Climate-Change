# Self-Study-Project-on-Climate-Change
Analysis of various Climate change visualizations
---
title: "Self Study Project - Prachi Sharma"
author: "Prachi Sharma"
date: "April 12, 2019"
output:
  html_document: default
  pdf_document: default
  word_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


# Evaluation Framework

Below is the rubric for Evaluating the Visualizations

* **Data Presentation** - Does the visualization present data correctly and effectively with less interpretation?  	 
*  **Chart choice** - How well does the graph choice complement the subject and the data?	   
*  **Comprehensibility** - How comprehendible is the visualization for general audience considering mass outreach of this subject?   
*  **Narration Impact** - Did the visualizations add depth to the deliberation about impacts of the subject among viewers?

Scored on below scale:

-  **4** - Outstanding 

-  **3** - Effective

-  **2** - Adequate 

-  **1** - Ineffective


Reference - 

1. <a href='https://cyber.rms.moe/books/03%20-%20General%20Science/The%20Visual%20Display%20of%20Quantitative%20Information%20-%20Edward%20Tufte.pdf' rel='nofollow'>The Visual Display of Quantitative Information - Edward Tufte</a> 


2. <a href='https://scholarworks.iu.edu/dspace/bitstream/handle/2022/16814/VisualizationAssessmentRubric.pdf?sequence=6' rel='nofollow'>Visualization Assessment Rubric</a> 





# Climate Change Visualizations


## Visualization 1

This dynamic visualization is a must watch for visualization wizards. It is a series of charts that demonstrates the effect of all known natural and human factors on climate change over the years. 

It gives an interesting twist to a chart as simple as line chart and stands out in beautifully narrating the story of how all the factors individually as well as together impact climate change. The color choices for representing factors is on point and description on top of chart is short, relevant and generates interest. It is successful in bringing out the point that it is in fact human factors that are more responsible for climate change compared to natural factors. It is very easy to understand with a little room for interpretation. 

The downside in the visualization is analyzing over the axes. Quantifying the exact temperature for each year is not possible as the temperature is wrt Average. Though on scrolling through the plot one can see the year but it would have been better to have the axis show the year number. 

**Reference -<a href='https://www.bloomberg.com/graphics/2015-whats-warming-the-world/' rel='nofollow'>What's warming the world</a> **


![](Visualization1_bloomberg.png)


```{r, echo=FALSE,out.width="49%", out.height="20%",fig.cap="Graph Series",fig.show='hold',fig.align='center'}
knitr::include_graphics(c("figs/ww1.png","figs/ww2.png"))
knitr::include_graphics(c("figs/ww3.png","figs/ww4.png"))
```

### Evaluation : 

Data Presentation | Chart choice | Comprehensibility | Narration Impact
--- | --- | --- | --- 
2 | 3 | 3 | 4 




## Visualization 2

This visualization convey to the public in a fresh way just how serious climate issue is. The standard way of visualizing such data is usually line charts but this viz catches attention by showing the changes dynamically. The visualization shows both the deviations from the average temperature over the recent years, and the sharp overall increases in average temperatures in the last 30 years. It can be noticed that as the years are passing average global temperatures keep peaking in a more than century-long pattern of  rapid warming. Spiral chart is an appropriate choice for showing this rapid change and the color transition from ice blue to bright yellow and closeness to red lines also complement the notion of alarming increase in temperature.  
Though visualization makes a subtle point of human activities causing temperature rise by appealing visuals, but it fails at showing year by year rise and fall of temperature which can't be tracked through this visualization. We can not see a year's exact temperature deviation through this chart which is more easy through a static chart.

*PS- Below the GIF are Before and After images of the visualization.Before image is what inspired this Viz and after image is what was campaiged throughout the world for climate change awareness* 

**Reference: <a href='https://www.vox.com/2019/3/4/18246245/climate-change-warming-stripes' rel='nofollow'>Climate change data representation</a>**


![](https://media.giphy.com/media/crqhvcJRxDjlC/giphy.gif)



```{r, echo=FALSE,out.width="49%", out.height="20%",fig.cap="Before and After Images for the above Visualization",fig.show='hold',fig.align='center'}
knitr::include_graphics(c("figs/Gif_inspiration.png","figs/Gif_goal.png"))
```


### Evaluation : 

Data Presentation | Chart choice | Comprehensibility | Narration Impact
--- | --- | --- | --- 
2 | 3 | 4 | 4 




## Visualization 3

This visual art shows the amount of annual Co2 emissions in 39 countries. This visualization captures a lot of information including +ve,-ve emission changes and for each country the annual carbon dioxide emissions between 1992 and 2012 (kt) and renewable energy consumption (% of total final energy consumption). The countries are ordered according to instruments used for environmental policy (tax revenue in % of GDP). 

The visualization is very informative and captures all the facts at one place. The climate trend of all the countries clearly shows how climate has changed worldwide and country is immune to those changes. We can perform various analysis like how much CO2 emissions are from developing in comparison to developed nations which can highlight the underlying activities being done in these countries which are causing emissions(as developing countries are believed to have more industrial and manufacturing activities). 

The choice of chart is very unique, but in doing so it gives away the essence of simplicity. Some viewers might find it hard to understand this visualization right away as we are used to viewing data through lines and bars. The use of specific language other than English makes it hard to be widely used and understood. The axis for year and scale for length of petals are not clearly described for each country's plot requiring efforts to identify the year. 


**Reference: <a href='https://www.behance.net/gallery/31279439/Carbon-Dioxide-Emissions' rel='nofollow'>CO2 Emissions</a>**


![](figs/CO2_emissions.png)


```{r, echo=FALSE,out.width="49%", out.height="20%",fig.cap="Closer look at Visualization elements",fig.show='hold',fig.align='center'}
knitr::include_graphics(c("figs/COE1.png","figs/COE2.png"))
```


### Evaluation : 

Data Presentation | Chart choice | Comprehensibility | Narration Impact
--- | --- | --- | --- 
3 | 2 | 2 | 2 




## Visualization 4

The visualization shows climate model simulations of the effects of human and natural factors. The visualization's simplicity, chart choice, axes data, color representation makes it very easy to understand while giving sufficient facts for analysis. 
The black line shows observed global average temperatures. From the green line it is evident , without human influences temperature rise over the years wouldn't actually have been this worse. The chart is compelling in illustrating that inclusion of human factors increased the recent warming drastically through match up of the blue band and the black line. 

One thing that is not very clear from graph is what influence does human factors have exclusive of natural factors quantitavely.

**Reference: <a href='https://www.globalchange.gov/browse/multimedia/%EF%BF%BCseparating-human-and-natural-influences-climate' rel='nofollow'>Human Vs Natural Influences On climate</a>**


![](figs/HumanVsNatural_Influence_on_Climate.png)


### Evaluation : 

Data Presentation | Chart choice | Comprehensibility | Narration Impact
--- | --- | --- | --- 
3 | 3 | 3 | 3 




## Visualization 5 

This visualization is based on data from 2011 study that summarizes the opinions from climate / earth scientists regarding climate change. The visualization clearly shows that majority of the scientist community believe that humans are biggest culprit behind Global warming. To our surprise, there is less yet considerable no of scientist who believe Human have little or no role in Global warming. It can be believed for general public to not acknowledge the seriousness of climate change and their own culpability in causing it. But coming from knowledgeable, aware people in the community this erupts a debate on Human role in Global Warming 

The chart is based on survey data and there is possibilty that the essence of responses is not being captured by this chart.The chart is simple and conveys the message but data may have dimensions that can't be represented through basic bar chart that raises ambiguity concerns. Also, the categories are not properly evident unless one notices that there is no space between the bars. The survey questions could have been categorised well and then the chart would have provided more reasoning. 

**Reference:<a href='https://en.wikipedia.org/wiki/File:Climate_science_opinion2.png' rel='nofollow'> Human role in Global Warming</a>**

![](figs/AgainstHumanRole.png)


### Evaluation : 

Data Presentation | Chart choice | Comprehensibility | Narration Impact
--- | --- | --- | --- 
2 | 1 | 2 | 3 



# Conclusion

This project has helped in developing cognition on how we can present data worth of centuries through simplistic visualizations keeping the essence intact. We can make to the point argument in a single chart with all components speaking one story. There has to be balance of data on the chart, showing important data metrics for analysis is essential but putting too many data jargons on the chart can fail to leave an impression. And in the end it does come down to the audience it is being shown. For raising awareness about climate issues Visualization 1, 2 and warming strip plot leave a long lasting impression on masses while Visualization 3 is ideal for analysis by experts.
It was a great learning experience to see some amazing and creative visualizations during the research and inspiring to look at how differently the data can be interpreted visually.
