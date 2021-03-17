# P0rtfolio
Portfolio work for 94-870 [Telling Stories with Data] (https://api.heinz.cmu.edu/courses_api/course_detail/94-870/)


# About Me
Hello, my name is [Nolan (he/him)] (https://www.linkedin.com/in/nolanroosa/) and I am a first year MSPPM DA student. I have been living in Pittsburgh for a while now, having completed my BS at the University of Pittsburgh in Economics and Political Science. My background is primarily in university and think tank research and I am hoping to use this course to better present the data that I work with. After graduating I hope to continue with a think tank style organization or work with a federal agency on program evaluation and audit.

# I hope to learn..
I hope to learn how to more effectively communicate with the data I use on a daily basis! I am currently working with survey data and am hoping to impress my coworkers with some high quality visuals.

# Portfolio

## Final Project: 

## Other Assignments:

[Georgia]

[Japanese debt to GDP Ratio]

<iframe src="https://data.oecd.org/chart/6gQB" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6gQB" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2015</a></iframe>

## Debt to GDP Ratio
<div class="flourish-embed flourish-chart" data-src="visualisation/5298778"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

# Japanese Debt to GDP Ratio
<div class="flourish-embed flourish-scatter" data-src="visualisation/5298936"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

While the graph has alot of extra elements that could be removed with more time with the flourish tool, the graph shows that overtime Japan has significantly increased their debt to GDP ratio compared to other OECD countries. This comparison is also shown with the difference between Japan and the average ratio line that is overlayed in black on the scatterplot.

# Georgia
Working through the process of finding visualizations, critiquing them, and then recreating them was challenging. I spent a significant amount of time going through some different news sources and journals that I enjoy before deciding that COVID data is obviously timely and likely to be accessable. I found a dashboard on the Georgia Department of Public Health page that had multiple visualizations and data that paired with it. I chose this vizualisation because I believe it was created to intentionally play down the number of COVID deaths in the state. The scaling on the X axis does not allow for the user to see deaths occuring among younger people, and cases overshadow all of the death data.

My initial brainstorm was that I could represent each outcome (case, hospitalization, death) with a circle, and then fill those circles with the proportion of each age that experienced that outcome. I thought this would create a more balanced view of each of the outcomes, and convey to the viewer which age groups are most at risk. I pitched this inital idea to my roomates and we realized that by leaving out the case numbers I was losing a significant amount of data. We decided that it would be intuitive to simply fix the problem directly and rescale the count axis. I switched the axis to follow more conventional perceptions of bar graphs, and then drew a seperate graph for each outcome. With a new scale, it became much easier to understand the hospitalization and death outcomes that were not viewable on the original visual.

![Brainstorming](FullSizeRender.jpeg)

Another thought that I had was that I need to make sure that the changes in scale are noticed by the viewer. This is where I added color to the labels of the Y axis. The text color corresponds with each outcome, bringing the viewers attention to this difference in scale.

![Georgia Deaths by Age Group](georgia.png)

I then had to work with the data after realizing that it was incomplete. The zip file from the Georgia DOH only included data on deaths by age, not cumulative case of hospitalization data. I searched through other state health websites, and CDC data but could not find data to complete the rest of the visualization. I created one of the three graphs that would make up the visualization. The real outcome would resemble the bottom white board sketch shown above in brainstorming.

