# Code-Quiz

This is a quiz application using HTML and CSS. This application focuses on semantic HTML elements. 
This project has been deployed to GitHub Pages. To get this project up and running, you can follow the deployment link. Or, download the sources files to use this as a template.

* [GitHub Repository](https://github.com/Fgrodasmendez1/Challenge-4)
* [Deployed GitHub IO](https://fgrodasmendez1.github.io/Challenge-4/)
* [Full Demo Video](https://drive.google.com/file/d/1NE5iRfU3dMwpYCBGjd_9cdutiWeNcE--/view)

![Horiseon.demo](![Horiseon (3)](https://user-images.githubusercontent.com/104540728/187055186-1fa9c33e-f788-48aa-aa23-233ea7bd3ffa.gif))

### Prerequisites

To install this application, you will need a text editor. I recommend Visual Studio Code. 

### Installing

To install this code, download the zip file, or use GitHub's guidelines to clone the repository. 


### Summary
* HTML and CSS documents and edit the starter code. 
* This project emphasizes the use of HTML to edit the sementic elements. 
* This project utilizes agile project management as a practice excercise for future work flow.

### This project has the following features: 
* The project provides starter code that must be edited. 
* The web page as functioning links.
* Each link directs the user to specific information based on the descr. 

![Screenshot-1](Asset/Screenshot-1.png)

* An appended HTML page that features questions, and multiple choice answers.
    * If questions are answered incorrectly, 10 seconds are deducted off remaining time.
    * Answers are recording using an event listener, "click" and tracks correct answers.

![Screenshot-2](Asset/Screenshot-2.png)
![Screenshot-3](Asset/Screenshot-3.png)

* An appended HTML page that features: 
    * Final score which is calculated using time remaining.
    * A Summary of how many questions answered correctly. 
    * Input area to record initials.
    * A Submit button.
    * Submit buttom saves initials and score to local storage.

![Screenshot-4](Asset/Screenshot-4.png)

* A Highscores HTML
    * This a list summary of intials and final scores.
    * Clear button resets the page and local storage.
    * "Home" button travels to the start of the quiz.

![Screenshot-5](Asset/Screenshot-5.png)

### Psuedo code:  
* Create a timer attached to a button with a starting value of 0.
* When timer is pressed start a reverse countdown.
* Create a 0 for countdown.
* When the countdown starts then the quiz start.
* Start Quiz will be on appended page.
* Append the question: choices.
* When user selects the right answer, textcontent "Correct!"
* When user selects the right answer, textcontent "Wrong!"
* Final score will keep track of how many the user got right. 
* Final Score Appended page. 
* Captures local storage.
* Travels to another HTML.
* Retrieved highscores.

### This project has script features of:
* Questions contained in an array variable with objects.
* Variable declaration area. 
* An event listener (onclick) that generates time interval.
* A function to render the questions and choices on the page using a for loop.
* An event listener on all list choices. 
* A comparison statement to compare correct answers to choices.
* An appended page showing the final stats of the individual user with input area for initials, captures local storage.
* Highscores retreived local storage.

### This project has media Queries for:
* max-width: 980px 
    * Adjusts body and container width
* max-width: 786px
    * Adjusts body and container width
    * Adjusts buttons
* max-width: 640px
    * Adjusts body and container width
    * Adjusts buttons to be centered and stacked

### To Execute File:
> Open in browser

### Features: 
* Two HTML Pages
    * Index.html 
        * Contains landing page to start timer
        * Appends two new pages 
* Highscores 
        * Retreives local data from previous page
* One CSS Page
    * Styles.css
        * Contains centering and styling for HTML list features
        * Contains media queries
* Two Javascript Page
        * Contains: 
        * Variables, including arrays with object
        * Event listeners
        * if/else if statements
        * For Loops
        * Functions 
        * Local Storage set and get 
