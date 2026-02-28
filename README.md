🎮 DigitalSteps — Game-Based Java Learning Platform

An interactive desktop application designed to make learning Java Object-Oriented Programming (OOP) engaging, structured, and accessible through gamification and adaptive progression.

📖 About the Project

DigitalSteps is a Java-based desktop learning platform developed as part of the Object-Oriented Programming (2) course at Imam Abdulrahman Bin Faisal University.

The system integrates structured Java learning with gamification concepts, offering adaptive learning paths, level-based progression, quizzes, and a worldwide competition mode — all supported by a relational MySQL database.

The platform is designed to support learners at different skill levels, guiding them step by step from programming fundamentals to advanced OOP concepts.

🚀 Core Features
👤 User Management

Secure player registration and login with validation

Unique username, email, and phone enforcement

Player profile management and account deletion

Database-based level tracking per player

📚 Adaptive Learning System

50+ lessons across three tiers: Beginner, Intermediate, Advanced

Lesson completion tracking stored in the database

Programming Basics module for complete beginners

Level assessment quiz for automatic level assignment

🧠 Quizzes & Assessments

Level-based quizzes (10 questions per quiz)

Automatic level updates based on performance

Admin-managed question bank with full CRUD operations

🌍 Worldwide Competition Mode

Anonymous global competition mode

Nickname and avatar selection

Real-time leaderboard with rankings

Replay option after results

🔐 Admin Dashboard

Secure admin login (pre-seeded accounts)

System statistics overview (players, quizzes, top scores)

Player management (view, filter, delete)

Quiz management (Create, Read, Update, Delete)

Feedback viewer using File I/O

🛠 Technologies Used

Java (Swing / javax.swing) — GUI and application logic

MySQL — Relational database management

JDBC — Java–MySQL connectivity

NetBeans IDE — Development environment

File I/O — Player feedback handling

🗄 Database Overview

Database: DigitalStep1

Main tables include:

Player

Administrative

Lesson

Question

Quiz

player_Take_lesson

player_anwser_qustion

Administrative_Update_Quize

Administrative_Display_player

The system applies relational modeling with many-to-many relationships for lesson tracking, quiz attempts, and administrative actions.

📂 Project Structure
DigitalSteps/
├── src/
│   ├── Auth/
│   ├── Player/
│   ├── Lessons/
│   ├── Quiz/
│   ├── LevelAssessment/
│   ├── ProgrammingBasics/
│   ├── WorldwideComp/
│   └── Admin/
├── database/
│   └── DigitalStep1.sql
└── feedback.txt
⚙️ Setup Instructions
Requirements

Java JDK 8+

MySQL Server

NetBeans IDE (recommended)

MySQL Connector/J

Installation

Clone the repository

Run the SQL file to create the database

Configure JDBC connection details

Open in NetBeans and build the project

🎓 Academic Context

Developed as an academic project for the OOP (2) course — Second Semester 2023/2024.
