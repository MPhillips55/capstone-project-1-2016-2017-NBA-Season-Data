### Statistics Explanations

In the exploratory data analysis portion of my project I used two statistical methods to help analyze the data. 

First, I calculated r-squared for the regression lines in my scatter plots. This helped to explain how much spread there was in the underlying data and how well the regression line summarized that data. The values that I found lined up with my intuition from just looking at the data - team possessions was kind of all over the place, it was possible to succeed playing very different styles of basketball. Team assists was a little more closely grouped, with the r-squared value being around 36% and again agreeing with my visual interpetation of the scatter plot that more assists would generally lead to more wins. 

Second, I used z-tests to analyze population mean assists for two groups of NBA teams - those that made the playoffs and those that did not. I chose this distinction because making the playoffs (for most teams anyway) is a good measurement of how the season went. I chose to utilize z-tests because the data being analyzed comprised the entire population of NBA teams, thus the population standard deviations could be calculated. 

The results were interesting. Team assists were found to correlate to success (making the playoffs) at an alpha level of .05. The calculated z-score was 1.697 and the z-critical value for alpha of .05 is 1.645. This confirmed one of my original hypotheses' when beginning this project: that passing effectively is an important measurement of playing winning basketball.

The second z-test I conducted was to analyze a team efficiency stat that I calculated from team box-score data, once again comparing playoff and non-playoff teams. This test was useful but in a different way. 

The z-score identified here did not exceed the z-critical value and any difference between the two populations was likely due to chance. I can now conclude that using the team efficiency in further analysis is not going to be very helpful as it does not correlate strongly with success. The stat did not generalize well to team-wide analysis in the same way that it identified efficient players earlier in my EDA report. I was hoping that the better teams in the league could be identified by using the efficiency stat, but as it turns out having a few good players carrying the team does not fully cancel out an otherwise lackluster roster. And on the flipside, a team could have a decent efficiency score, but fail in other areas not measured in the score such as defense and rebounding.  
