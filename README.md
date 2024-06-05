# quizapp
Description

A simple Android quiz application where users can test their knowledge by answering multiple-choice questions.
Features

Multiple-choice questions with various topics we can customize this section based on our question data.
Keep track of user score.
Show pass/fail status at the end of the quiz.
Option to restart the quiz.

Java (MainActivity.java):

Manages the quiz flow and user interaction.
Keeps track of the score, current question, and selected answer.
Loads questions and answer choices from the QuestionAnswer class.
Checks if the user's answer is correct and updates the score accordingly.
Handles user clicks on answer buttons and the submit button.
Displays an alert dialog with the final score and pass/fail status at the end of the quiz.
Provides the option to restart the quiz.

Java (QuestionAnswer.java):

Stores the quiz questions, answer choices, and correct answers in separate arrays.
Provides a static way to access the quiz data from the MainActivity class.

XML (activity_main.xml):

Defines the user interface layout for the quiz.
Displays the total number of questions, the current question, and the answer choices (A, B, C, D).
Provides buttons for users to select an answer and submit it.
