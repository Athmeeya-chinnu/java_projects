# java_projects

ExamForge CLI - Project Description

ExamForge CLI is a Command Line Interface (CLI) based Online Examination System developed in Java. It allows users to register, log in, take a multiple-choice examination, and instantly receive their scores. The system stores user details during program execution and prevents users from attempting the exam more than once.

Modules:

1. User Module
Registers new users.
Stores:
Name
Email
Password
Prevents duplicate user registration.

2. Authentication Module

Allows users to

Login using Email
Password verification
Rejects invalid credentials

3. Question Module

Stores all exam questions.

Each question contains

Question
Four Options
Correct Answer Index

4. Exam Module

Starts the examination after successful login.

Features

Randomizes questions using
Displays one question at a time
Accepts user answer
Calculates score

5. Result Module

After completing exam

Displays score
Marks exam as completed

WORK FLOW


Start
      │
      ▼
Main Menu
      │
 ┌────┴────┐
 │         │
Register   Login
 │          │
 │     Verify Credentials
 │          │
 │     Successful?
 │          │
 └────No────┘
      │
     Yes
      │
      ▼
Start Exam
      │
Display Questions
      │
Accept Answers
      │
Calculate Score
      │
Show Result
      │
Exit

















