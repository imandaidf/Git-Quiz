# Git Quiz for Beginners

This is a simple web-based quiz application designed to help beginners learn the basics of Git. The quiz features multiple-choice questions and provides immediate feedback on answers.

## Features

- **Interactive Quiz**: Users can answer multiple-choice questions about Git.
- **Real-Time Feedback**: Displays whether the selected answer is correct or incorrect.
- **Score Tracking**: Keeps track of the user's score throughout the quiz.
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Tailwind CSS**: Styled using Tailwind CSS for a modern and clean UI.

## Access the Quiz

To access the web quiz, visit this link:  
[Git Quiz for Beginners](https://imandaidf.github.io/Git-Quiz/)

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Custom styles and Tailwind CSS for design.
- **JavaScript**: Logic for quiz functionality.

## How to Use

1. Open the `index.html` file in any modern web browser or visit the link above.
2. The quiz will start with the first question.
3. Select an answer and click the "Next Question" button to proceed.
4. At the end of the quiz, your score will be displayed along with feedback.

## Project Structure

```
index.html
```

- `index.html`: Contains the HTML, CSS, and JavaScript for the quiz.

## Customization

You can customize the quiz by editing the `quizQuestions` array in the `<script>` section of `index.html`. Each question object includes:

- `id`: Unique identifier for the question.
- `text`: The question text.
- `options`: An array of possible answers.
- `correctAnswer`: The correct answer for the question.

Example:
```javascript
const quizQuestions = [
    {
        id: 1,
        text: 'What is Git?',
        options: [
            'A type of coffee',
            'A version control system',
            'A graphic design tool',
            'A database management system',
        ],
        correctAnswer: 'A version control system',
    },
];
```

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com) for styling.
- [Google Fonts](https://fonts.google.com) for the "Inter" font.

Enjoy learning Git with this quiz!