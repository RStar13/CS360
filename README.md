# CS360
CS360 Mobile Architecture and Programming
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
  The application i chose is a weight tracking app.  The objective allows for the user to set a target goal and daily update their weight.  By keeping record
  of their weight loss/gain, they can reflect on what led to the changes in their weight and hopefully be inspired to continue their progress.  The app itself
  must allow for a user to register a unique username and password, allow them to log into their account, set their target weight and date, and each day update 
  their current weight.  The username/password, weight records, and their progress are recorded in databases.  Each daily weight log is compared against the goal weight,
  and their current weight loss and lbs til reaching goal are calculated and show to the user through a simple table.  If a user forgets to enter their weight one day, they can
  add it at any time, and the app will sort the data chronologically and place it in the appropriate spot on the table.  
  
What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
  When the user opens the app, they are greeted by a login screen.  On this screen existing users can login via U/N and P/W, or new users can create an account.  SMS features can also be
  activated, allowing the app to push notifcation reminders daily.  After logging in, the user is brought to their dashboard.  Herein they can set their goal weight, log their current body weight,
  and view their progress.
  
How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
  When coding this app, It was done modularly.  Working from one screen to the next to make sure flow between screens is intuitive and functional.  Working bit by bit toward
  the completion of the goal and testing regularly was key in being able to make a cohesive program.  
  
How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
  Using the catlog for error display and testing the app and trying to break it were my primary methods for testing functionality.  Constant testing especially
  when trying to change features in the app would allow me to see when and where a bug in the code would manifest.  It also allowed me to back track, undo, and
  try something else.  
  
Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
  The entire process was a challenge for me.  I suppose one feature that i needed to innovate was the data table for the user to review.  I had use a table wigdget in project 2 to demonstrate a table
  with different data columns.  I found that trying to use that method caused the app to lag down as it was an inneficient way to demonstrate the data.  I ended up using a RecyclerViewer to generate the
  table and enable easier alterations to the data via retroactive recordings of weights, or deleting entries at will.  This greatly improved the speed at which the app ran.
  
In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
  At this point in time I still feel woefully inaddequate when it comes to coding in Java.  Being able to get through this course was a great source of my stress as work 1 FT job and 1 PT job while taking
  one course per term at SNHU.  Getting Covid during this time slowed me down some.  The fact that I made it until the end and hobbled through the course material was success enough for me.  Had I more time
  to really deep dive into more material and other resources (udemy and youtube) I may have been able to produce a more polished and impressive application.  I went into this class with excitement and hope
  but came out feeling ground down.  Oh well.  It was a learning experience in more ways than just Mobile Architecture and Coding.
