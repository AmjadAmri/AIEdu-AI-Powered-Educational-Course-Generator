# AIEdu – AI-Powered Educational Course Generator
A Flask-based web application that leverages OpenAI models to automatically generate complete educational courses from a simple user prompt. The system creates a structured curriculum, detailed lesson content, learning objectives, multiple-choice assessments, stores generated courses in a SQLite database, and exports the final course as a PowerPoint presentation.


## Features
- AI-generated educational courses from user-defined requirements.
- Two-stage AI generation for improved curriculum coherence.
- Automatic chapter and lesson planning.
- Learning objectives generation for every lesson.
- AI-generated multiple-choice quizzes with answer keys.
- Bilingual support (Arabic and English).
- Course persistence using SQLite.
- Interactive web interface built with Flask.
- PowerPoint (.pptx) export.
- Input validation and structured JSON generation.


## Workflow
User Input
      │
      ▼
Course Requirements
      │
      ▼
Stage 1
Generate Course Outline
      │
      ▼
Stage 2
Generate Lessons
Learning Objectives
Quizzes
      │
      ▼
Store Course in SQLite
      │
      ▼
Display Course
      │
      ▼
Export PowerPoint

هذه أفضل من كتابة فقرة طويلة.

## Technology Stack
Backend
• Flask

Database
• SQLite

AI
• OpenAI API

Frontend
• HTML
• CSS
• Jinja2

Libraries
• python-pptx
• python-dotenv

Language
• Python

## Project Structure
.
├── app.py
├── requirements.txt
├── templates
│   ├── base.html
│   ├── index.html
│   ├── new_course.html
│   ├── course.html
│   └── quiz.html
├── static
│   └── style.css
└── instance
    └── courses.sqlite3

    
## Example Input
Parameter	Example
Topic	Artificial Intelligence
Academic Level	Undergraduate
Language	English
Duration	90 Minutes
Chapters	4


## Example Output

The generated course includes:

Course title
Course description
Chapter structure
Lesson content
Learning objectives
Multiple-choice quizzes
PowerPoint presentation
