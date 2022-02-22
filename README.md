# SNHU-CS-360

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This project was developed to fulfill the needs of a client with requirements associated with a weight tracking application. There needed to be a login page with the ability to
reguster new users. The users should be able to enter a goal weight and daily weight measurements. Those items were to be stored in a database and should have CRUD tools for data
management. The user needed to be prompted for SMS text notifications. SMS notifications would be sent based on requirements such as reaching a goal weight. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? 
Why were your designs successful?

A login screen was greated with features for logging on to the app as well as registering a new user. A second screen was built to allow for a goal weight to be entered and 
daily weight measurements and the date taken. That same page allowed for data entry into the database as well as a button to view the data in a list view. There was also a 
SMS notifications button. The view data button leads to another page with all data entries by the user listed. The user could then click on any line item to go to the edit page. 
This page has an update data and delete data feature. The user can change entries or delete them all together. There is a back button to return the user to the enter data page. The
SMS button leads to a notifications permissions pager where the user can grant or denty permissions to ereceive SMS notifications. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I used an object oriented approach. I took each page and requirement a deveolped them iteratively. I was able to find tutorials and exampls of similar requirements to base my
app design on. Any code used from those selections was cited in my Java code. I was careful to test every change made in the emulator before moving on to other challenges. I 
did have issues with the database after refactoring some file names. This took quite a bit of time to overcome. 

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

Each section of code was tested in the AVD emulator with a phone that was capable of running the API29. Any issues identified by Android Studio were addressed and tested again. 
This process made it much easier to troubleshoot issues as they arose rather than trying to find code errors after writing hundreds of lines. 

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I really had to be innovative with the overall app design. I had three different aesthetic designs before settling on what I completed. Knowing exactly what text views and
buttons, etc, would be required took several tries and a lot of thought. I believe the login page works best and is closest to the requiremenst in the assignment documentation. The
login page has its own database seperate from the daily weight entries and works quite well. 
