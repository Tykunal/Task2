# Quiz App           

## Introduction
Welcome to the Ultimate Quiz Challenge! This repository contains the code for a simple Quiz App that allows users to test their knowledge by answering intriguing questions on various topics. The app is built using HTML, CSS, and JavaScript.

## How to Play
1. To get started, open the `index.html` file in your web browser.
2. Click on the "Start Quiz" button to begin the quiz.
3. Read each question and click on the corresponding answer option to select your choice.
4. You have a total of 30 seconds to answer each question.
5. After answering all the questions, the quiz will be completed, and your score will be displayed.

## Quiz Questions
The quiz questions and their options are defined in the `script.js` file. Here's a sample of the questions:

```javascript
const quizQuestions = [
  {
    question: "What is the capital of France?",
    options: ["Paris", "London", "Berlin", "Rome"],
    correctAnswer: "Paris"
  },
  {
    question: "Which planet is known as the Red Planet?",
    options: ["Venus", "Mars", "Jupiter", "Saturn"],
    correctAnswer: "Mars"
  },
  // More questions...
];
```
## Score
The app keeps track of your score based on the number of correct answers you provide.
At the end of the quiz, you will see your total score and the percentage of correct answers.

## Timer
You have 30 seconds to answer each question.
If you don't answer within the given time, the quiz will end automatically, and your score will be displayed.
