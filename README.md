"# QuizGameApp" 
📌 Overview

QuizApp is a simple React Native application that allows users to select quizzes and answer multiple-choice questions. It tracks the user's score and provides an interactive quiz experience.

🛠 Features

Select from multiple quizzes

Answer multiple-choice questions

Track correct and incorrect answers

Interactive UI with touchable buttons

🏗 Tech Stack

React Native (Expo)

TypeScript

React Hooks

🚀 Installation & Setup

Prerequisites

Make sure you have the following installed:

Node.js (Recommended: Latest LTS version)

Expo CLI

Steps to Run the App

Clone the repository:

git clone https://github.com/Ni31/QuizGameApp git
cd QuizGameApp

Install dependencies:

npm install

Start the development server:

npx expo start

Scan the QR code using the Expo Go app on your mobile device or run the app on an emulator.

⚠ Fixing Common Errors

Error: TypeError: os.availableParallelism is not a function

🔧 Solution:

If you encounter this error, modify your metro.config.js file or add the following workaround in your project:
