### Overview
​
In this assignment, you'll indeed create another Quiz game. The catch? You're going to make this an online multiplayer game, all with the help of Firebase (and the rest of your web development repertoire)! In this application, two users should be able to access the URL to participate. When the users first enter the landing page, ask each for their preferred username. Store these values in a Firebase database. Once both users are logged in, create an API call to retrieve a trivia question for each to answer. Each user can select an answer option and once both have answered the question, the application will inform the users which was correct and move on to the next question. At the end of the quiz, display a summary of the winner and number correct under each player's name.
​
### Some Notes Before you begin
​
* Whether you finish the game or not, you must hand in your code by the due date to avoid having your work marked incomplete. 
* We acknowledge you are assigned this task as a solo dev. Still, we do want to see you program this game as best you can.
​
### Setup
​
1. Create a GitHub repo called `Quiz_Your_Friends` and clone it to your computer.
​
2. Create a file inside of your `Quiz_Your_Friends` folder called `index.html`. This is where your page's HTML will go.
3. Don't forget to include [jQuery](https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js) and [Firebase](https://www.gstatic.com/firebasejs/live/3.0/firebase.js).
​
4. Inside `Quiz_Your_Friends`, create your `assets` directory.
5. Create the folders and files you typically place in `assets` -- (JavaScript, CSS) just like you had for the prior unit's homework assignments.
​
### Submission on BCS
​
* Please submit both the deployed Github.io link to your solo project AND the link to the Github Repository!
​
### Instructions
​
* Create a game that suits this user story:
​
  * Only two users can play at the same time.
​
  * When the usernames have been assigned, dispatch and API query to the questions API of your choice to retrieve the question to display.
​
  * Both players will respond with their selected answers.
​
  * The game will track each player's selection and determine if they selected the correct answer.
​
  * Throw some chat functionality in there! (Optional: call this a stretch goal)
​
  * Styling and theme are completely up to you. Get Creative! Remember to follow the project requirements found in the PDF Project_1 in the class repository.
  (You will be provided a singular exemption from the requirement which states you must use a different CSS Framework. You may use Bootstrap as a solo developer.)
​
  * Deploy your project to Github Pages.
​
### Reminder: Submission on BCS
​
* Please submit both the deployed Github.io link to your homework AND the link to the Github Repository!
​
- - -
​
### Minimum Requirements
​
Attempt to complete project assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed. Adding a README.md as well as adding this homework to your portfolio are required as well and more information can be found below.
​
If your application cannot be live-demoed on presentation day, please create a slideshow to present from as a supplement.
​
- - -
​
### Create a README.md
​
Add a `README.md` to your repository describing the project. Here are some resources for creating your `README.md`. Here are some resources to help you along the way:
​
* [About READMEs](https://help.github.com/articles/about-readmes/)
​
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- - -
​
### Add To Your Portfolio
​
After completing the project please add the piece to your portfolio. 
​
- - -
​
### Additional Practice and Support
​
* If you find your skills lacking in any of the subjects we taught you, look at your instructor's in class repository. 
​
  * Recognize that we are asking every member of the class to learn something we have never taught in class before.
​
  * Find the exercises that you did in class and redo them from scratch. It might seem redundant at first, but this will help edify the material.
​
  * You can also watch videos of this all of our past lectures--we've saved these to the repo.
​
* If you have any questions about this project or the material we have covered, please post them in the community channels in slack so that your fellow developers can help you! If you're still having trouble, you can come to office hours for assistance from your instructor and TAs.
​
* Start by working through the 3 activities in Unit 7 in the class repository.
​
  **Good Luck!**