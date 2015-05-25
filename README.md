Goal
Create a Sinatra Application that allows anyone to add music (songs) to a public wall to share with the world. This app will be so open and chaotic that visitors don't even need to register a user account in order to post songs.

About the App
The Model
The track model can include the following fields/attributes:

Song Title (required)
Author (required)
URL (optional)
Timestamps (created_at and updated_at, as you should have with all tables)
The Actions
Any visitor will be able to create and view the list of music (songs). Similar to the previous app, don't worry about implementing the ability to update or delete songs. Once they're up, they're up. Crazy, I know!

Getting Started
Use the Sinatra Skeleton Code to get started, much like you did for your First Sinatra App Tutorial.

Estimated Time
This app should take you between 3 to 4 hours to build.

Tips
This application is very similar to the one built earlier via the tutorial. Feel free to use its Commits and Tutorial as a reference.
Write incremental code, much like you (hopefully) have been previously. When developing web apps, much like how you were doing with your ruby apps, write a little bit of code that should yield some result and then ensure that it does yield that result (ie: refresh the page to see the change).
Be sure to initialize a git repo for it and commit to it regularly. Make a new Github repo and push to it regularly as well. You can just work on the master branch for now.
Enhancement - Front-end Improvements using Twitter Bootstrap
There exist some pretty cool CSS UI frameworks which allow us to create decent looking web apps fairly quickly. They do this by providing us with some better boilerplate CSS classes to apply to our elements.

Twitter Bootstrap is likely the most popular, but there are others like Foundation. There's even Framework7 for making mobile apps appear/behave like iOS7 apps.

Apply the Bootstrap CSS framework to your project in order to style elements like the nav, buttons, etc. Consider how some of the tools within Bootstrap help to make your site more usable.

NOTE: When you add in the Bootstrap CSS, take out the existing normalize.css, as that is already included in Bootstrap.