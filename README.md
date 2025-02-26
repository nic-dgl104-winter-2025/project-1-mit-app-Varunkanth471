[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/so8F8uYz)
# MIT App Inventor Project

# Varunkanth-Word_wiz-app

<!-- PROJECT LOGO -->

<div align="center">
    <img src="assets/logo2.png" alt="Logo" width="200">
  </a>
  <h3 align="center">Word_Wiz App</h3>
  <p align="center">
    A Word_Wiz MIT App
  </p>
</div>

<!-- ABOUT THE PROJECT -->

## About The Project

Word_Wiz MIT App is a user-friendly app designed to help beginner and intermediate language learners expand their vocabulary through engaging daily challenges. Built using MIT App Inventor, this app offers an interactive and effective way to learn new words, test knowledge, and track progress over time.

### Main Screens of the app

1. Login Page - (Screen1)
2. Welcome page - (MainMenu)
3. Dail_Quiz 
4. Flashcard
5. Progress Tracker

### Main components using in the app

1. Storage/Tiny DB - Local storage.
2. TextTOSpeech - component allows your app to convert text into spoken words.

## Login Screen

1. Given Username and Password:

* Username: "Admin"
* Password: "1234"

<img src="assets/login_page.jpeg" alt="screen" width="250">


## Welcome Screen (MainMenu)

1. A back button labeled "Home" and a "Main Menu" title, indicating this is a submenu.
2. Three main buttons for core app features.
3. A message guiding the user to the login page, which could be clearer and more user-friendly.
4. A modern and clean aesthetic with a dark blue gradient and white buttons.

<img src="assets/Welcome_page.jpeg" alt="screen" width="250">

## Quiz Screen

* Click on the any option button to display to start the Quiz.
* Select the given option for the MCQ question and it will display if the chosen answer is "correct" or "Try Again".

<img src="assets/Quiz.jpeg" alt="screen" width="250">

## Flashcard screen

1. Click the "Next word" button for the "Text-to-speech" component to activate.
2. You can hear the pronounce in Country "IND".
3. The Language option is in default, had tried to change the language to "Tamil" option was unable to select and choose.
    * The language has a default option like : "de"
                                               "en"
                                               "es"
                                               "fr"
                                               "it"   
4. The pitch rate and Speech rate is same which is "1.0".                                               

<img src="assets/Flashcard.jpeg" alt="screen" width="250">

## ProgressTracker

1. The progress tracker screen has the score achieved by the user.
    (not as excepted)
2. the progress tracker screen has the tinyDB function to store the value of score achieved by the user.

<img src="assets/ProgressTracker.jpeg" alt="screen" width="250">

### Code Block Component ScreenShots

<img src="assets/quizblockcomponent.png" alt="screen" width="250">
<img src="assets/Flashcardsblockcomponent.png" alt="screen" width="250">
<img src="assets/Progresstrackerblockcomponent.png" alt="screen" width="250">
<img src="assets/loginblockcomponent.png" alt="screen" width="250">
<img src="assets/mainmenublockcomponent.png" alt="screen" width="250">

### Referevnce

1. https://drive.google.com/file/d/1RhhC9aQsWEYS0Q3RJObJPcstx8lLsf7E/view - For quiz screen
2. https://obsidiansofteducation.com/index.php/sign-up-and-login-in-screen-in-mit-app-inventor/ - For login screen
3. https://www.youtube.com/watch?v=rhkw08U6bsg  For TinyDB



## Summary Details & Development Process

* The app was built using MIT App Inventor’s block-based programming environment. The process involved designing the UI with components like Labels, Buttons, and Arrangements, then wiring these components together using blocks.
* Data for quizzes and flashcards (Tamil letters/words and their translations) was stored in global lists. Procedures like LoadQuizQuestion and LoadFlashcard.
* Unlike traditional web coding, MIT App Inventor’s block system makes handling complex data structures tricky.
* Instead of using CSS padding or margins, MIT App Inventor requires the use of Horizontal/Vertical Arrangements to achieve a readable layout.

## Code review

* Have to initialize related code into procedures (like LoadQuizQuestion, CheckAnswer, and LoadFlashcard). This makes your project easier to manage because you don’t repeat the same blocks over and over. 
* Data Organization quiz data (questions, answers, and options) are stored in global lists.


## Resources Used

1. Youtube.
2. MIt App Inventor tutorial.
4. Mit App Inventore.



