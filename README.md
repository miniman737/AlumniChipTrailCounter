# AlumniChipTrailCounter
 A basic python data analytics project that pulls a users strava activity to count the number of times they have run around chip trail
#Problem
Team Captain of the University of Victoria Mens Track Team was tasked me with figuring out how to calculate/figure out the ammount of times 
he had run the alumni chip trail since he started his schooling at UVic

#Solution
By making a call to the Strava API v3, and calling all of a users activities/storing the JSON data I then converted the 
polyline data and began to graph their activies to using matplot.lib. Using the Users graphed data, it was just a simple implementation of checking on each
activity the number of times a user had crossed each of the 4 "virtual gates" on the alumni chip trail that counted it as a lap.
It is important to acknowledge that any loop around henderson rec center, or any short cut that is taken by the ECS building end of Chip will still be counted as 
a lap, as there are multiple/3 different ways in which you can run around Alumni Chip Trail.

