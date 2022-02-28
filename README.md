# First-Minutes-Part-2

You can find Part 1 [here](https://github.com/MarlinMyrte/First-Minutes-Part-1)

## Based on my previous analysis, we found out that there is an offensive slump in the first 2 minutes of each quarter.
## A fair question that can be raised here is whether this "2-minute slump" affects the outcome of the game and how different would the team standings be if all teams didn't have this slump.

To answer this question we need to:
- Obtain Average Points per Minute data for all the NBA teams
- Compare the offensive performance of each team in the first 2 minutes vs in the last 10 minutes of each quarter
- Predict how many more points a team would score if the played the same way during all the minutes of the quarter by adding the difference of the means to the total score of each game
- Recalculate the score of each game
- Recalculate the standings

After getting the Average Points per Minute for each team we can see that the most "stable" team so far this year has been the Phoenix Suns. On the other hand, the OKC Thunder have the largest difference in terms of average ppm between the first 2 minutes of a quarter and the last 10

![alt text](https://github.com/MarlinMyrte/First-Minutes/blob/main/Top%20Bottom%20diff.png "Top-Bottom 3")


Now, by adding up the "lost points" of each minute, we can recalculate the results of each game and the standings
*We have to mention that by doing this recalculation of the scores some ties might occur which makes it impossible to determine the eventual winner of a game. That being said we can only hypothesize on what could have happened in these tied games*

**Eastern Conference**
![alt text](https://github.com/MarlinMyrte/First-Minutes/blob/main/East%20Standings.png "East")


**Western Conference**

![alt text](https://github.com/MarlinMyrte/First-Minutes/blob/main/West%20Standings.png "West")

### In the Eastern Conference, we can see that the 76ers jumped a spot from the 3rd place to the 2nd place, the Bulls have 3 ties which could bring them down to the 2nd spot in the East and Charlotte dropped a spot to Toronto and is now 7th
### In the Western Conference, the Los Angeles Clippers might drop 2 wins because of ties and that could bring them to the 9th place and to the play-in tournament while 2 potential wins in ties from the Kings could bring them to the 12th spot


####################################################################
FOR PORTFOLIO
We discovered that there are teams which have a larger difference in their offensive performance in the first 2 minutes of each quarter compared to their offensive performance in the first 10 minutes of each quarter.

![](/Images/Top%20Bottom%20diff.png)

**So what if this "2-minute slump" didn't exist? How would the standings be different?**

**Eastern Conference**
![](/Images/East%20Standings.png)

**Western Conference**
![](/Images/West%20Standings.png)

In the Eastern Conference, we can see that the 76ers jumped a spot from the 3rd place to the 2nd place, the Bulls have 3 ties which could bring them down to the 2nd spot in the East and Charlotte dropped a spot to Toronto and is now 7th

In the Western Conference, the Los Angeles Clippers might drop 2 wins because of ties and that could bring them to the 9th place and to the play-in tournament while 2 potential wins in ties from the Kings could bring them to the 12th spot
