# Quiz App

This is a simple quiz application built using React. The app allows users to answer a series of questions and receive their score at the end.

## Features

- Displays multiple-choice questions.
- Tracks the user's score.
- Provides feedback with the final score at the end of the quiz.
- Responsive and visually appealing design.

## Technologies Used

- React.js
- CSS for styling

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tahaesii/quiz-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd quiz-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

5. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## File Structure

- `src/Quiz.js`: Contains the main Quiz component logic and state management.
- `src/Quiz.css`: Contains the styles for the Quiz component.

## How to Use

1. The app starts with the first question displayed.
2. Click on one of the answer options to proceed to the next question.
3. At the end of the quiz, the app will display your total score.

## Code Explanation

### Quiz Component

The `Quiz` component is a React class component that manages the following states:

- `questions`: An array of question objects, each containing the question text, answer options, and the correct answer.
- `currentQuestion`: Tracks the current question index.
- `showScore`: A boolean that determines whether to display the score.
- `score`: Keeps track of the user's score.

### Event Handlers

- `clickHandler(isCorrect)`: Handles user clicks on answer options. If the answer is correct, the score is incremented. The app proceeds to the next question or displays the score if it is the last question.

## Styling

The app uses custom CSS for styling, defined in `Quiz.css`. Key styling features include:

- A responsive layout with flexbox.
- Custom button styles for hover and focus states.
- A visually appealing color scheme.



##

