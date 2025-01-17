# Practice Test

This is a simple Practice Test built using ChatGPT haha. It allows users to upload an Excel file containing questions and start a quiz in different modes. The app supports multiple modes like Practice, Test, and Custom with settings for time limits, passing scores, and the number of questions.

## Features

- Upload an Excel file containing test questions.
- Three quiz modes:
  - **Practice Mode**: Displays the correct answers as you go through the questions.
  - **Test Mode**: Standard quiz mode with no feedback during the quiz.
  - **Custom Mode**: Customize the number of questions, time limit, and passing score.
- Dashboard to track answered and unanswered questions.
- Review incorrect answers after the test.

## Requirements

- A modern browser (Google Chrome, Firefox, etc.).
- An Excel (.xlsx) file formatted with questions, choices, and the correct answer.

## How to Use/Setup

### 1. Clone the repository (if applicable)

```bash
git clone https://github.com/salmonbara/Practice-Test
```
### 2. Open the project
Open practiceTest.html in a web browser.

### 3. Upload Your Excel File
- Click on the "Choose File" button to upload an Excel file containing questions.
- The Excel file must have the following structure:
    - Column 1: Number of question
    - Column 2: Question Text
    - Column 3: Option A
    - Column 4: Option B
    - Column 5: Option C
    - Column 6: Option D
    - Column 7: Correct Answer (A, B, C, or D)

### 4. Select Quiz Mode
After uploading the file, choose one of the following modes:

#### **Practice Mode**
In this mode, you can practice the questions and get feedback on whether your answers are correct or incorrect.

#### **Test Mode**
In this mode, you can take a test without immediate feedback. After completing the quiz, you'll get the results at the end.

#### **Custom Mode**
In this mode, you can customize the quiz by specifying the number of questions, time limit, and passing score.
- Set the number of questions.
- Set the time limit for the quiz in minutes.
- Set the passing score percentage.

### 5. Start the Quiz
- Once you choose a mode (and, in the case of Custom Mode, set the parameters), click "Start!" to begin the quiz.
- The quiz will load, and you can navigate through the questions using "Next" and "Previous" buttons.
- If you choose the Practice Mode, the correct answers will be highlighted.

### 6. Submit and Review
- After completing the quiz, click "Submit" to get your score.
- If you didn't pass, you can review the incorrect answers.

### 7. Reset
- You can reset the quiz anytime using the "Reset" button.

## Files
This project consists of the following files:

- `practiceTest.html`: The main HTML file containing the structure of the quiz.
- `practiceTest.css`: This project uses basic CSS for styling and layout. You can modify to change the visual appearance of the app..

## License
This project is open-source and available under the MIT License.
```
