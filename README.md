<p align="center">
    <img src="images/home.png" width="900">
</p>

# AIEdu – AI-Powered Educational Course Generator

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web_App-black?logo=flask)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?logo=openai)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite)
![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3)

## Overview

AI-Powered Educational Course Generator is a Flask-based web application that transforms a brief user request into a comprehensive educational course. Users specify the subject, academic level, language (Arabic or English), course duration, and number of chapters. The system then generates a structured curriculum, detailed lesson content, learning objectives, and multiple-choice assessments, stores the generated course in a SQLite database, and exports the final course as a downloadable PowerPoint (PPTX) presentation.

---
## User Interface

### Home Page

<p align="center">
  <img src="images/home.png" width="800">
</p>

### Course Generation

<p align="center">
  <img src="images/generation.png" width="800">
</p>

### Generated Course

<p align="center">
  <img src="images/course.png" width="800">
</p>

### Quiz Page

<p align="center">
  <img src="images/quiz.png" width="800">
</p>

### Demo Video

> Add your project demo here:

https://github.com/user-attachments/assets/your-video-link

---

## Features

- 🤖 AI-generated educational courses from user-defined requirements.
- 📚 Two-stage AI generation for improved curriculum coherence.
- 📝 Automatic chapter and lesson planning.
- 🎯 Learning objectives generation for every lesson.
- ❓ AI-generated multiple-choice quizzes with answer keys.
- 🌍 Bilingual support (Arabic & English).
- 💾 Course persistence using SQLite.
- 🌐 Interactive web interface built with Flask.
- 📊 PowerPoint (.pptx) export.
- ✅ Input validation with structured JSON generation.

---

## Workflow

```text
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
```

---

## Technology Stack

| Category | Technologies |
|----------|--------------|
| **Backend** | Flask |
| **Frontend** | HTML, CSS, Jinja2 |
| **Database** | SQLite |
| **AI** | OpenAI API |
| **Programming Language** | Python |
| **Libraries** | python-pptx, python-dotenv |

---

## Project Structure

```text
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
```

---

## Example Input

| Parameter | Example |
|-----------|---------|
| Topic | Artificial Intelligence |
| Academic Level | Undergraduate |
| Language | English |
| Duration | 90 Minutes |
| Chapters | 4 |

---

## Example Output

The generated course includes:

- Course title
- Course description
- Structured curriculum
- Chapters and lessons
- Learning objectives
- Multiple-choice quizzes with answer keys
- Exportable PowerPoint presentation

---

## Future Improvements

- Support for additional export formats (PDF, Word).
- Integration with Learning Management Systems (LMS).
- AI-generated illustrations and diagrams.
- Personalized learning paths.
- Interactive assessments and grading.

---

## Author

**Amjad**  
Bachelor's in Artificial Intelligence  
Umm Al-Qura University
