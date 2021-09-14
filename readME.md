# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [X] (2pt) User can view the app on various device sizes and orientations.
- [X] (1pt) Run your app on a real device.

### App Walkthrough GIF

- Walkthrough 
<p align="left">
<img src="iphone8.gif">
</p>
- View on various device sizes, ex: iPad Pro
<p align="left">
<img src="ipro.gif">
</p>
- Run the app on a real device 
<p align="left">
<img src="phone.gif">
</p>

### Notes
1. How to view the app on various device sizes and orientations? 
<p>
Adding different constraints to let each object know the relative distances respecting to other objects so that they know where to locate on various device sizes.   
</p>

2. How to display the app on a real device? 
<p>
a. Connect the Iphone with the MAC <br>
b. Go to account to add your account that is the same as the one on your phone <br>
c. Click the project, find a section called "Signing & Capabilities." Then look at the name in "Bundle Identifier," the end of the name should be ".app." That is to say the whole name should look like: company.project.app <br>
d. Replace the simulator with your phone device, and run it. <br>
e. Look at your iPhone and the app will be installed automatically in few seconds. <br>
f. There may be a error message telling you that the app is not authorized. Don't get panic, follow the steps. <br>
g. On your iPhone. Go to Settings --> General --> Device Management --> click your app and make your phone trust it. <br>  
</p>

