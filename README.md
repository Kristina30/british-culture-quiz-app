# British Culture Quiz App

This is a quiz game in regards of the British Culture. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for the user. The main goal of this project is to provide a positive emotional experience for the users.

![British Culture Quiz App](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/quiz-responsivedesign.png)

## This project has the following features:
### Home Page
* Navigation bar at the top of the page.
* Heading - giving a clear introduction to the user.
* Hero image - that makes the quiz home page look more vibrant.
* Instructions Section - tells the user how to play the game.
* Play Now button - that takes the user to the quiz page.
* Footer - that holds the social media links.

![British Culture Quiz App](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/home-page-screenshot.png)

### Quiz Page
* Progress bar - inserted on the left side on the top of the page. It tells the user how many questions needs to be answered.
* Scores - the score updates with every answer selected. Correct answer award 200 points, Inscorrect answer give 0 with a maximum of 2000 avaibale at the end.
* Question section - inserted above the answers containers.
* Answers Containers - give the user a choice of different answers. The selected answers will respond with relevant color changes to reflect the response. Correct answers will be colored in Green / Incorrect answers will be colored in Red.

![British Culture Quiz App](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/quiz-page-screenshot.png)

### End Quiz Page
* Final Score - the score updates with every answer selected. Correct answer award 200 points.
* Input Field - requires the user to type their name in order to save their score.
* Save Button - saves initials and score to local storage also there is a message displaing that the user's score has been saved on a pop up window at the top of the page.
* Play Again Button - takes the user back to the quiz game.
* Go Home Button - takes the user back to the Home Page.

![British Culture Quiz App](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/end-page-screenshot.png)

## Wireframes

* Those aren't my original wireframes as I had issues with git pod and I have decided to remove the High Score Page and the timer on the Actual Quiz Page. I have also re-typed the whole Quiz game on different repository due to the issues with GITPOD. 

![British Culture Quiz App Home Page](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/home-page.png)

![British Culture Quiz App Page](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/game-page.png)

![British Culture End Quiz App Page](https://github.com/Kristina30/british-culture-quiz-app/blob/main/assets/images/your-score-page.png)




## User Stories

### As a user I want:
* the quiz app to be very appealing to me in terms of design and feeling.
* the introduction to help me understand the purpose of the project.
* to be able to see some instructions on how to play, before starting the game.
* to know whether I have selected the correct or incorrect answer with a visual response.

### As owner of the site, I want to:
* promote my quiz app in a way that will keep existing users and attract new ones.
* the typography in the project to look fun and engaging.
* the project to be responsive across different resolutions.
* the users to be navigated easily using the navigation bar and other types of links that leads to other pages inside the quiz app.

## Structure of the site

* The Home Page has a Navbar, that links the link to the relevant sections on the Home Page. 
* The Play Quiz link and Play now! button starts the game.
* The navbar is responsive across different resolutions, at 720px width, it changes to a hamburger menu.
* The iconic Hero image is placed to draw the users attention, which hopefully encourages them to have a go at playing the game.
* The dark background throughout the project gives the effect of a Dark Mode Theme.
* The selected answers will respond with relevant color changes to reflect the response. Correct answers will be colored in Green / Incorrect answers will be colored in Red.
* The user can save their scores by typing their name and pressing the Save button. Score and Name will be saved in browser local storage.
* The score updates with every answer selected. Correct answer award 200 points, Inscorrect answer give 0 with a maximum of 2000 avaibale at the end.

## Design

### Colour Scheme
The two main colours used are CMYK Colours: #fafafa and #f9ae22.
The Background color is #333

### Typography
The Playfair Display font is used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. 

### Imagery
Imagery is very important. The large, background hero image is designed to be striking and catching the user's attention.

### Features
   * Responsive on all device sizes
   * Interactive elements

### Technologies Used
* HTML - is the basic building block for the project and to structure the content.
* CSS - is used to style all the web content across the project.
* JavaScript - is the main programming language used to manipulate HTML dom, and make the project interactive.
* Google Fonts - Playfair Display font was used for this project and linked from Google Fonts.
* Font Awesome - Font Awesome icons were used in the Footer of the Home page for Social media links.
* Github - storing code for the project after being pushed.
* Gitpod - development enviroment for the project.
* Balsamiq - creating the wireframes for the project.
* W3 School - JavaScript used to make the nav bar responsive.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate the code of my project to ensure there were no syntax errors.
   * W3C Markup Validator - [Results](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fkristina30.github.io%2Fbritish-culture-quiz-app%2F)
   * W3C CSS Validator - [Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkristina30.github.io%2Fbritish-culture-quiz-app%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
   * JavaScript Validator - Passed without any errors. JSHint marks some of my functions uncalled. Please see explanation below.
   1. MakeNaveResponsive function is called on nav icon when used in responsive mode. This function has been called in my index.html to make my nav bar responsive.
   2. ReDirect function is called in end-quiz.html. This function redirectsthe window location to a specified page name.
   3. SaveHighScore function is called in end-quiz.html in order to save the score of the user. This functionality makes the webpage future proof and gives me an opportunity to expand the functionality and to create a new page in order to display the High Scores in a separate page.

### Further Testing

When the project was deployed, I used Chrome Dev Tools to help test responsiveness. Chrome Dev Tools used to emulate the following devices,

* Apple Ipad
* Apple Ipad Pro
* Apple iPhone 5/SE
* Apple iPhone 6/7/8
* Apple iPhone 6/7/8 Plus
* Apple iPhone X
* Motorola G4
* Samsung Galaxy Fold

The project was manually tested on the Iphone 11 Pro, Iphone 7, Iphone X and Samsung Galaxi S21 Ultra.

The project was tested on the following browsers,
* Google Chrome
* Microsoft Edge
* Mozilla Firefox

I used the W3C Markup Validator and W3C CSS Validator to validate my HTML and CSS. 

I used JSHint to check my JavaScript code.

## Deployment procedure

Once the webpage been fully created, I staged it to be pushed to github by using the Git version control system.
The final step used was pushing the finished product to github.

### Deploying a GitHub Repository via GitHub Pages
* In your Repository section, I selected the Repository to I wish to deploy.
* In the top horizontal menu, I located and clicked the Settings link.
* Inside the Setting page, around halfway down I located the GitHub Pages Section.
* Under the Source, I selected the None tab and change it to Main and clicked Save.
* Finally once the page resets I scrolled back down to the GitHub Pages Section to see the following message "Your site is ready to be published at (Link to the GitHub Page Web Address)". There is the link to the published site, that I will use to submit my project and also able to access it from different devices and browsers.

### Making a Local Clone
* Find the GitHub Repository.
* Click the Code button
* Copy the link shown.
* In Gitpod, change the directory to the location you would like the cloned directory to be located.
* Type git clone, and paste the link you copied in step 3.
* Press Enter to have the local clone created.

### Issues
* I had a lot of dificulties creating this project as my gitpod had a lot of issues and most of my code disapiared. To ensure any further issues I have created a new repository and re-typed all the code. The old repository (british-culture-quiz) is still in my github account so that the assessor can view it if needed.

## Acknowledgements
I received great advice and feedback from my mentor Medale Oluwafemi.

I have also watched some walk through tutorials to helps me understand the logic of what types of functions would need to be used to make make quiz app functional.
* Brian Design
* Dev Ed
