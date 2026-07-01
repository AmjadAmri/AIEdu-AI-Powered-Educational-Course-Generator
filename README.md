<p align="center">
  <img src="https://github.com/user-attachments/assets/3077653c-7035-4c26-b857-a197ac485385" width="170" alt="AIEdu Logo">
</p>

<h1 align="center">
AIEdu – AI-Powered Educational Course Generator
</h1>

<p align="center">

<img src="https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white">
<img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white">

</p>

<p align="center">
Generate complete educational courses with AI in just a few clicks.
</p>

---

# Overview

AIEdu is a Flask-based web application that transforms a brief user request into a comprehensive educational course. Users specify the subject, academic level, language (Arabic or English), course duration, and number of chapters. The system then generates a structured curriculum, detailed lesson content, learning objectives, and AI-generated multiple-choice assessments, stores the generated course in a SQLite database, and exports the final course as a downloadable PowerPoint (PPTX) presentation.

---

# User Interfaces

<table align="center">
  <tr>
    <td align="center">
      <b>Home Page</b><br><br>
      <img src="https://github.com/user-attachments/assets/57c7bf9b-1061-4293-a60a-24eace33b917" width="450">
    </td>
    <td align="center">
      <b>Course Generation</b><br><br>
      <img src="https://github.com/user-attachments/assets/8bcee6eb-87eb-43b5-ba7c-1ce5c85bb8c9" width="450">
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Generated Course</b><br><br>
      <img src="https://github.com/user-attachments/assets/e2ff88cf-ad26-4625-8f1f-e90ac6c08947" width="450">
    </td>
    <td align="center">
      <b>Quiz Page</b><br><br>
      <img src="https://github.com/user-attachments/assets/94d18889-cc82-409c-b295-0e15763fdcf1" width="450">
    </td>
  </tr>
</table>

---

# Demo Video

https://drive.google.com/file/d/1MDHZQtQKaMBqIohZPD2usctRu5s2dEcj/view?usp=sharing

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

- Fine-tune an open-source language model for educational content generation tailored to different academic disciplines.
- Integrate Retrieval-Augmented Generation (RAG) to incorporate trusted educational references into the generation process.
- Support AI-generated educational diagrams, flowcharts, and visual learning materials.
- Expand multilingual support to additional languages.
- Export courses in additional formats such as PDF and Word.
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
