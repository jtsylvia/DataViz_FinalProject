## March 21

Scraped data from liberty league baseball teams and stored them as objects in R. Started to tidy the SLU baseball data.

## March 23 Beginning of Class

Merge all of the individual team data frames into a single one. Also, created example visualizations to see what variables to explore.

## March 23 End of Class

Imported Game data for each team in Liberty League and stored all games into a single data set. Also, added grouping variables of "School" and "Division" to both the individual data and game data.

## March 28 Beginning of Class

Created a new data set of all Liberty League "Game" Data. Mutated new columns to show more contemporary baseball statistics including FIP and K/BB ratio. Lastly, began working on a shinyApp that plots two pitching statistics on the x-axis and y-axis to create a scatterplot.

## March 28 End of Class

Tidied dataset to make Player name look nicer by only including last name. Also did some more work on ShinyApp by adding a player input to indicate where a specific player is on the scatterplot by coloring point and having their name in text (work in progress).

## March 30 Beginning of Class

Made the finishing touches on the previous shinyApp that indicated a player's name. Began new shinyApp that displays a lollipop chart for the top 20 players for a specific statistic.

## March 30 End of Class

Changed several character strings to numeric strings in order to make lollipop chart function better. Created new color scale for member schools of Liberty League. Will work on implementing multiple tabs for shinyApp next time.

## April 4 Beginning of Class

Created two shinyApps for game data in which I used different game statistics and logistic regression to predict a team's probability of winning. Also utilized plotly to put labels on the two new shinyApps as well as the previous ones created.

## April 4 End of Class

Worked on using different tabs within Shiny instead of using conditional UI to visualize hitting vs. pitching data. Still a work in progress at this point.

## April 6 Beginning Class

Continued troubleshooting shinyApp from last time. Still need to figure out the exact error I am making to get it working.

## April 6 End of Class

Was able to get shinyApp working. Now have 3 tabs visualizing different tabs so the plan is to keep adding onto this shinyApp. Lastly, started experimenting with new ggplot package that included a baseball field geom.

## April 11 Beginning of Class

Incorporated images of each teams logo and implemented them into the Individual data shinyApp. Fixed some bugs in code in involving game data as well.

## April 18 Beginning of Class

Fixed further bugs in shinyApp for the GameData. Going to work on making the team logos clearer during class today.

## April 18 End of Class

Releveled my W/L variable and colored points based upon wins and losses. Researched on how to incorporate background images onto the plots within the shinyApp.

## April 18 Beginning of Class

...

## April 20 End of Class

Finally fixed geom_image problem as it had to do with `color = School` being in the global aesthetics. Also added a new wOBA statistic to give weights to different types of ways of getting on base. Going to bring all data into one ShinyApp next week.

## April 25 Beginning of Class

Working with the Game Data shinyApp I added two new tabs which show the distributions of each of the statistics--it also includes vertical lines indicating the team average as well as league average. I renamed the 'choices' to be more user friendly to somebody who does not know baseball abbreviations. Lastly, I classified the app into a "Hitting" tabset and a "Pitching" tabset for ease of use and clarity.

## April 27 Beginning of Class

Constructed a dataset where only conference games are considered for individual players. This will be utilized in creating normalized stats for the league. Also made appearance changes on GameData shinyApp.

## April 27 End of Class

Manually added new data frame which calculated park factors for all of the libety league fields. This will be utlized in creating normalized statistics as well. It will probably also be used in a separate visualization.

