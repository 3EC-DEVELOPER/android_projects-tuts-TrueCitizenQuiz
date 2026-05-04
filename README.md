# TrueCitizenQuiz — True/False Quiz App

> **Course project** — built while following [The Comprehensive Android App Development Masterclass](https://www.udemy.com/course/android-development-java-android-studio-masterclass/) by [Paulo Dichone](https://www.udemy.com/user/paulodichone/) on Udemy.
>
> This project is not original work. It was created for learning purposes only. Full credit to Paulo Dichone for the course content and instruction.

<p align="center">
  <img src="https://img.shields.io/badge/Android-Tutorial-3DDC84?logo=android&logoColor=white" alt="Android Tutorial"/>
  <img src="https://img.shields.io/badge/Java-Course%20Project-ED8B00?logo=openjdk&logoColor=white" alt="Java Course Project"/>
  <img src="https://img.shields.io/badge/Quiz-True%2FFalse-111827" alt="True False Quiz"/>
  <img src="https://img.shields.io/badge/Trainer-Paulo%20Dichone-2563EB" alt="Trainer Paulo Dichone"/>
</p>

---

## About

A true/false quiz app using questions about US citizenship. The user navigates through a bank of questions with next and previous arrow buttons, answers true or false, and receives instant feedback via a `Toast`. This project is an earlier, simpler version of the quiz concept that was later expanded in the Trivia project.

## Concepts Covered

- Creating a `Question` model class with a resource ID and boolean answer
- Storing a fixed question bank as an array of model objects
- Implementing `View.OnClickListener` on an Activity with a `switch` statement
- `ImageButton` for navigation arrows alongside standard `Button`
- `Toast` for immediate answer feedback
- Question index management and wrapping (next/previous with boundary handling)
- String resources (`R.string`) for question text to support localisation
- `Log.d()` for debug output

## Tech

- Language: Java
- Min SDK: Android 5.0+
