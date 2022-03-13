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

After getting the Average Points per Minute for each team we can see that the most "stable" team so far this year has been the Phoenix Suns. On the other hand, the Sacramento Kings have the largest difference in terms of average ppm between the first 2 minutes of a quarter and the last 10

![alt text](https://github.com/MarlinMyrte/First-Minutes-Part-2/blob/main/Top%20Bottom%20diff.png "Top-Bottom 3")


Now, by adding up the "lost points" of each minute, we can recalculate the results of each game and the standings
*We have to mention that by doing this recalculation of the scores some ties might occur which makes it impossible to determine the eventual winner of a game. That being said we can only hypothesize on what could have happened in these tied games*

**Eastern Conference**
![alt text](https://github.com/MarlinMyrte/First-Minutes-Part-2/blob/main/East%20Standings.png "East")


**Western Conference**

![alt text](https://github.com/MarlinMyrte/First-Minutes-Part-2/blob/main/West%20Standings.png "West")

### In the Eastern Conference, we can see that the 76ers jumped from the 3rd place to the 2nd place which is something that could change a lot during the Playoffs and also the Wizards went up to the 10th place
### Ιn the Western Conference, the Lakers moved up a spot and are in the playoff picture and the Clippers are in the play in tournamet
