---
sidebar_position: 1
---

# System Overview
Project Abstract
This document proposes a web-based application called Auto Suggestion Quiz, designed to improve the learning and assessment experience through automatically generated and adaptive quiz content.
The application allows users to practice academic or technical topics by receiving suggested quiz questions based on:
selected subjects
difficulty levels
user performance
Instead of relying only on static question banks, the system dynamically generates quizzes, creating a more personalized and efficient study experience.
Users can take quizzes, receive immediate feedback and scores, and review their performance history over time. The system aims to support active learning, improve knowledge retention, and reduce the effort required to create or search for practice materials.
By using Auto Suggestion Quiz, users will have an engaging and effective way to strengthen their understanding of course content and track improvement over time.

#Conceptual Design
The frontend of the application will be built using JavaScript, React, HTML, and CSS. React will be used to create reusable UI components and manage the state of the application. JavaScript, HTML, and CSS will be used to build the interface and handle user interactions.
The backend will be developed using Python and Django. The backend will manage user authentication, quiz generation logic, scoring, and storage of user data. A relational database such as SQLite will be used to store user accounts, quiz attempts, performance results, and question history.
The system will be accessible through a standard web browser and designed to support multiple users. The application will provide a simple interface for selecting quiz settings, answering questions, and reviewing results.

#Background
Similar products include Quizlet and other online quiz platforms that allow users to study through flashcards and practice tests. Quizlet is widely used and provides effective tools for reviewing content, but it often relies on manually created study sets and static question collections.
Auto Suggestion Quiz is similar to these tools in that it supports learning through quizzes and repetition. However, it differs by focusing on automatic suggestion and adaptive quiz generation. Instead of requiring users or instructors to create all quiz questions manually, the system helps generate and recommend questions based on user selections and performance.
By combining automated quiz creation, instant feedback, and performance tracking, Auto Suggestion Quiz provides a more personalized and efficient alternative to traditional quiz-based study tools.
