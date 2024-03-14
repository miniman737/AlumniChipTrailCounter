# AlumniChipTrailCounter
 A basic python data analytics project that pulls a users strava activity to count the number of times they have run around a popular running trail in Victoria BC
# Problem
Team Captain of the University of Victoria Mens Track Team was tasked me with figuring out how to calculate/figure out the ammount of times 
he had run the alumni chip trail since he started his schooling at UVic

# Solution
By making a call to the Strava API v3, and calling all of a users activities/storing the JSON data I then converted the 
polyline data and began to graph their activies to using matplot.lib. Using the Users graphed data, it was just a simple implementation of checking on each
activity the number of times a user had crossed each of the 4 "virtual gates" on the alumni chip trail that counted it as a lap.
It is important to acknowledge that any loop around henderson rec center, or any short cut that is taken by the ECS building end of Chip will still be counted as 
a lap, as there are multiple/3 different ways in which you can run around Alumni Chip Trail.

<img width="675" alt="PolyLineAnalysis" src="https://github.com/miniman737/AlumniChipTrailCounter/assets/51000189/22fa4650-0321-4221-b130-b0ae6d8493c4">
Here is an example of how a lap around Chip Trail is counted

# OUTPUT
Any Activity that contains more than one lap of chip trail has its activity name, distance and lap count outputted for the user in a very friendly fashion

<img width="700" alt="image" src="https://github.com/miniman737/AlumniChipTrailCounter/assets/51000189/0ff95d46-92ba-4b51-90b5-83ba01ded4df">
