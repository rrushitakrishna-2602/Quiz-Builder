# 🎯 Quiz Builder – Create. Play. Analyze.

**Quiz Builder** is an interactive web-based quiz creation and assessment platform developed using React.js and Vite. It allows creators to create and manage quizzes while participants can join quizzes, answer questions and view their results.

## 🌐 Live Demo

https://quiz-builder-1egh.vercel.app

## 📌 Project Overview

Quiz Builder provides a simple and user-friendly platform for conducting online quizzes. It includes separate workflows for Creators and Participants, making quiz management and participation easy and interactive.

The application supports multiple question types, countdown timers, automatic evaluation and performance analysis.

## ✨ Features

### 🔐 1. User Authentication
- User Signup and Login.
- User information maintained using Local Storage.
- Role selection after authentication.

### 👩‍💻 2. Role-Based Access
- Separate Creator and Participant workflows.
- Different dashboards based on the selected role.

### 📝 3. Quiz Creation and Management
- Create and manage quizzes.
- Add multiple questions.
- Support different question types:
  - Multiple Choice Questions (MCQ)
  - True/False
  - Text-Based Questions
  - Image-Based Questions
- Add correct answers and explanations.
- Edit and manage questions.

### 🎮 4. Quiz Participation
- Join quizzes using a unique quiz code.
- View questions and answer options.
- Navigate between questions.
- Countdown timer.
- Automatic submission when the timer expires.

### 📊 5. Results and Performance Analysis
- Automatic answer evaluation.
- Calculate scores and percentages.
- Display correct and incorrect answers.
- Review submitted answers.
- View correct answers and explanations.

### 💾 6. Data Management
- Browser Local Storage for maintaining application data.
- Stores user information, quiz details, questions, attempts and results.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React.js | Building user interfaces |
| Vite | Development and build tool |
| JavaScript | Application functionality |
| HTML5 | Application structure |
| CSS3 | Styling and responsive layouts |
| Local Storage | Client-side data storage |
| Git | Version control |
| GitHub | Source code management |
| Vercel | Application deployment |
| VS Code | Development environment |

## 🏗️ Application Architecture

The application consists of three logical layers:

**1. User Interface Layer**
- Signup and Login
- Role Selection
- Admin Dashboard
- Participant Dashboard

**2. Application Logic Layer**
- Authentication Management
- Quiz Creation and Management
- Question Handling
- Quiz Participation
- Timer and Submission
- Answer Evaluation
- Results Generation

**3. Data Storage Layer**
- User Information
- Quiz Details
- Questions and Answers
- Quiz Attempts
- Results

**Storage:** Browser Local Storage.

## 🔄 Application Workflow

### Creator Workflow

1. Register or Login.
2. Select Creator role.
3. Access the Admin Dashboard.
4. Create a new quiz.
5. Add questions, answers and explanations.
6. Save and share the quiz code.
7. View participant results.

### Participant Workflow

1. Register or Login.
2. Select Participant role.
3. Access the Participant Dashboard.
4. Enter the quiz code.
5. Attempt the quiz within the given time.
6. Submit answers.
7. View results and review explanations.

## 💻 Installation and Setup

Follow these steps to run the project locally.

### Prerequisites

Install the following:
- Node.js
- NPM
- Visual Studio Code
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/Sochana90209/Quiz-Builder.git
```

### Step 2: Navigate to the Project Folder

```bash
cd Quiz-Builder
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Start the Development Server

```bash
npm run dev
```

### Step 5: Open in Browser

Open the local URL displayed in your terminal. Usually:

```text
http://localhost:5173/
```

## 📂 Project Modules

The application is organized into the following main modules:

- **Authentication:** Signup and Login functionality.
- **Admin:** Quiz creation and management.
- **User:** Quiz participation and results.
- **Shared:** Common components and reusable functionality.

## 🔮 Future Enhancements

- Backend integration.
- Database integration for centralized data storage.
- Enhanced authentication and authorization.
- Advanced performance analytics.
- Improved accessibility and scalability.
- Additional quiz customization options.

## 🎓 Learning Outcomes

Through this project, we gained practical experience in:

- React component-based development.
- JavaScript programming.
- State management and UI interactions.
- CSS styling and responsive layouts.
- Browser Local Storage.
- Git and GitHub collaboration.
- Application deployment using Vercel.

## 👥 Team Members

| S. No. | Name |
|---|---|
| 1 | Sochana |
| 2 | Deepika |
| 3 | Rushitha |

**Subject:** Frontend Development Frameworks

## 🙏 Acknowledgement

We sincerely thank our faculty and institution for their guidance and support throughout the development of this project.

---

**Quiz Builder – Create. Play. Analyze.** 🎯

*Making online quizzes simple, interactive and effective.*
