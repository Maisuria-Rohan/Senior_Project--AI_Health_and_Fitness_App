# AI Health and Fitness Application

Senior Capstone Project

An AI-powered mobile fitness application designed to help students and busy individuals maintain a healthy lifestyle through personalized workout planning, activity tracking, and intelligent fitness assistance.

---

## Project Overview

Many students struggle to stay consistent with fitness because of demanding academic schedules, work commitments, and limited time.

Traditional fitness applications often provide generic workout plans that do not adapt to a user's schedule, availability, or fitness level.

The AI Health and Fitness Application was developed to solve this problem by generating personalized workout plans based on user information, available workout days, and fitness experience. The application also includes activity tracking, workout streak monitoring, and an AI-powered fitness chatbot for workout-related assistance. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

## Team Project

This project was developed as a group senior capstone project at the University of Houston-Clear Lake.

### Team Members

- Salim Aldakheel
- Ken Kurian
- Rohan Maisuria
- Charan Saragadam
- Trinity Varela
- Edsson Zapata

---

## My Contributions

As one of the primary backend developers, I worked on:

### Backend Development

- User authentication system
- User account creation and login
- Profile management
- Workout generation logic
- Workout scheduling system
- Workout completion tracking
- Workout streak calculations
- Statistics tracking
- API development using FastAPI
- Database integration

### AI Features

- OpenAI API integration
- AI chatbot backend implementation
- Fitness-focused prompt engineering
- Vector store integration
- Chatbot safety and restriction logic

### Frontend Integration

- Connected Android frontend to backend APIs
- Login and signup integration
- Workout plan retrieval
- User profile integration
- Session management and authentication tokens

### Deployment

- Backend deployment on Render
- Environment configuration
- API testing and debugging
- Production deployment support

---

## Problem Statement

Students and working individuals often find it difficult to maintain fitness routines because of busy schedules and lack of personalized guidance.

The goal of this project was to create a mobile application that generates customized workout plans that fit a user's schedule, fitness level, and available workout time while providing intelligent assistance through AI. :contentReference[oaicite:2]{index=2}

---

## Features

### User Authentication

- Account creation
- Secure login
- User profile management
- Persistent user sessions

### Personalized Workout Generation

Users provide:

- Age
- Gender
- Height
- Weight
- Fitness level
- Available workout days
- Available workout times

The system generates a customized workout schedule based on the user's availability and fitness profile. :contentReference[oaicite:3]{index=3}

### Workout Plans

- Weekly workout schedule
- Day-by-day workout breakdown
- Exercise lists
- Sets and duration information

### Workout Tracking

- Mark workouts as completed
- Store workout history
- Track completed sessions
- View recent workouts

### Workout Streaks

- Consecutive workout tracking
- Current streak monitoring
- Progress statistics

### Statistics Dashboard

- Total workouts completed
- Current workout streak
- Recent workout history

### AI Fitness Chatbot

Users can:

- Ask fitness questions
- Request workout guidance
- Get exercise recommendations
- Receive workout-related assistance

The chatbot uses OpenAI GPT integration and a fitness knowledge base to provide relevant responses. :contentReference[oaicite:4]{index=4}

### User Preferences

- Update personal information
- Modify fitness preferences
- Manage account settings

---

## System Architecture

The application follows a multi-layer architecture:

### Frontend

- Android Studio
- Java
- Retrofit

### Backend

- FastAPI
- Python

### Database

- SQLite
- SQLAlchemy ORM

### AI Layer

- OpenAI GPT
- Vector Store Knowledge Base

The frontend communicates with the backend through REST APIs. The backend processes user requests, stores data in the database, and communicates with the AI engine when chatbot functionality is used. :contentReference[oaicite:5]{index=5}

---

## Technology Stack

### Frontend

- Java
- Android Studio
- XML Layouts
- Retrofit

### Backend

- Python
- FastAPI
- SQLAlchemy
- JWT Authentication

### Database

- SQLite

### AI Services

- OpenAI API
- GPT-4o Mini

### Version Control

- Git
- GitHub

---

## Application Screens

### Login Screen

[Insert Screenshot]

### Account Creation

[Insert Screenshot]

### Home Screen

[Insert Screenshot]

### Workout Schedule

[Insert Screenshot]

### Workout Details

[Insert Screenshot]

### Statistics Dashboard

[Insert Screenshot]

### Profile Screen

[Insert Screenshot]

### AI Chatbot

[Insert Screenshot]

---

## Testing

The project was tested using Android Studio emulators and backend API testing.

### Test Areas

- User Signup
- User Login
- Workout Generation
- Activity Tracking
- Workout Recommendations
- AI Chatbot Responses
- Schedule Management
- Account Deletion

Test cases were created to verify all major functional requirements before deployment. :contentReference[oaicite:6]{index=6}

---

## Demo Workflow

1. Create account
2. Enter personal fitness information
3. Configure weekly availability
4. Generate workout plan
5. View daily exercises
6. Complete workout
7. Track progress in Stats page
8. Interact with AI Coach chatbot

---

## Repository Contents

### Documentation

- Vision, Scope, and Project Plan
- Requirements Specification
- Design Document
- Test Plan
- Team Charter

### Source Code

- Android Frontend
- FastAPI Backend
- Database Models
- AI Chatbot Services

---

## Future Improvements

Potential future enhancements include:

- Water intake tracking
- Calorie tracking
- Social features
- Friend system
- Cloud synchronization
- Social media sharing
- Expanded wellness recommendations

These features were identified during project planning for future releases. :contentReference[oaicite:7]{index=7}

---

## Final Outcome

The project successfully delivered a functional AI-powered fitness application capable of:

- Generating personalized workout schedules
- Tracking workout completion
- Monitoring workout streaks
- Providing AI-assisted fitness guidance
- Managing user profiles and preferences

The application was presented as part of the Senior Project course and demonstrated the complete software development lifecycle including planning, requirements gathering, design, implementation, testing, deployment, and final presentation. :contentReference[oaicite:8]{index=8}

---

## License

This project was developed for educational purposes as part of the University of Houston-Clear Lake Senior Project course.
