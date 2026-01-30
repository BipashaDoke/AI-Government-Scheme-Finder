# System Design Document

## Project Title
AI Government Scheme Finder

---

## 1. Overview
The AI Government Scheme Finder is a web-based application that helps users
identify government schemes they are eligible for based on personal and
economic details using AI-driven analysis.

---

## 2. System Architecture
The system follows a client–server architecture.

User → Frontend → Backend → AI Engine → Database

---

## 3. Components Description

### 3.1 Frontend
- User interface for data input
- Displays eligible schemes
- Built using React

### 3.2 Backend
- Handles API requests
- Processes user data
- Communicates with AI module
- Built using Python (Flask)

### 3.3 AI Module
- Analyzes user data
- Matches eligibility rules
- Uses Kiro AI / Gemini API

### 3.4 Database
- Stores user profiles
- Stores scheme details
- MongoDB is used

---

## 4. Data Flow
1. User enters personal details
2. Data is sent to backend
3. Backend sends data to AI module
4. AI processes eligibility
5. Eligible schemes are returned
6. Results displayed to user

---

## 5. Security Design
- Basic authentication
- Secure API communication
- No sensitive data exposed to frontend

---

## 6. Advantages of the Design
- Modular architecture
- Scalable system
- Easy to maintain
- AI-based automation

---

## 7. Future Enhancements
- Multilingual support
- Mobile application
- Voice-based input
- Real-time government database integration
