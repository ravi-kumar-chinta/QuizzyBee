# QuizzyBee 🐝

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=white&labelColor=20232A)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=FFD62E)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Quiz App](https://img.shields.io/badge/Quiz-App-8A2BE2)

---

## 🚀 Overview
**QuizzyBee** is a fun and interactive quiz application built using **React** and **Vite**.  
It allows users to test their knowledge through multiple-choice questions with instant feedback.  

This project demonstrates **React component-based design, state management with hooks, and modern UI styling**.

---

## ✨ Key Features
✅ **Multiple-Choice Questions** – Dynamic quiz with options.  
✅ **Answer Validation** – Highlights correct and wrong answers.  
✅ **Score Tracking** – Keeps track of user’s performance.  
✅ **Reset & Retry** – Restart quiz anytime.  
✅ **Responsive UI** – Works smoothly on desktop and mobile.  
✅ **Animated Background** – Pleasant gradient with smoke-like effect.  

---

## 🛠️ Technologies Used
- **React** – Frontend library  
- **Vite** – Fast build tool  
- **CSS3** – Styling & animations  
- **JavaScript (ES6+)** – Logic and interactivity  

---

## ⚙️ Installation & Setup
1. **Clone the repository:**
```bash
git clone https://github.com/ravi-kumar-chinta/QuizzyBee.git
```
```bash
cd QuizzyBee
```
2. **Install dependencies:**
```bash
npm install
```

3. **Run the app in development mode:**
```bash
npm run dev
```
- The application should now be running locally, usually accessible at `http://localhost:5173/` (the exact port may vary).
---

## 📂 Folder Structure

This project follows a component-based architecture typical of React applications.


```bash
.
├── node_modules/         # Automatically generated folder for installed dependencies
├── public/               # Static assets that are copied directly to the build folder
├── src/                  # Main application source code
│   ├── assets/           # General assets (images, fonts, etc.)
│   │   └── data.js       # Holds the quiz question data
│   ├── Components/       # Reusable UI components
│   │   └── Quiz/         # Contains files for the main Quiz component
│   │       ├── Quiz.css
│   │       └── Quiz.jsx
│   ├── App.jsx           # Main application component
│   ├── index.css         # Global styles
│   └── main.jsx          # Entry point for the React application (where the App is mounted)
├── .gitignore            # Specifies files/folders to be ignored by Git
├── index.html            # The main HTML file where the React app is injected
├── package-lock.json     # Locks dependency versions
├── package.json          # Project dependencies and scripts
└── vite.config.js        # Configuration file for the Vite bundler
```
---

## 🎮 How to Play

- Read the question carefully.

- Click on the correct option.

- Your score updates automatically.

- Click Next to go to the next question.

- At the end, view your total score.

- Use Reset to restart the quiz.

---


## 📈 Quiz Mechanics

 - Each question has 4 options, only one is correct. 
 - Selected answer gets highlighted (`Green` for `correct`, `Red` for `wrong`)
 - Score increases for each correct answer.
 - Final score is displayed at the end of the quiz.

## 🖼️ QuizzyBee Preview

- - Here’s how the app looks:

![QuizzyBee Screenshot]("C:\Users\hp\OneDrive\Desktop\Projects\quiz-app\Preview.png")

## ✅ Conclusion

- Built a fully functional quiz app using React + Vite.

- Implemented state management, conditional rendering, and scoring system.

- Designed with a beautiful animated background to enhance UX.

## 🎉 Enjoy the Quiz!

Thank you for checking out QuizzyBee 🐝.
Test your knowledge, challenge your friends, and have fun learning! 🚀