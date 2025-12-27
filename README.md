# Project Title : Student Reality Tracker

# Overview:
Student Reality Tracker is a rule-based academic analysis tool that evaluates a student’s subject-wise performance and CGPA to present a realistic academic snapshot.
Instead of focusing only on final CGPA, the project emphasizes structured calculation, edge-case handling, and explainable results.

# Features:
- Subject-wise CGPA calculation using credits and grades
- Rule-based evaluation logic (not hardcoded formulas)
- Separation of UI and business logic
- Edge-case handling for invalid or incomplete inputs
- Clean and minimal user interface

# TechStack:
- React
- JavaScript
- CSS

# Folder Structure:
src/
  * Components/
    - SubjectInput.jsx
    - Result.jsx
  * data/
    - rules.js
  * App.jsx
  * App.css

# Working:
The application collects subject details such as credits and grades, processes them through a rule-based evaluation system, and calculates CGPA along with contextual academic feedback.

# How to Run Locally:
npm install
npm run dev

# Future Improvements:
- Semester-wise performance tracking
- Trend analysis across semesters
- Data persistence for historial comparison


