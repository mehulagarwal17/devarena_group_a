🧠 AlgoArena

Where coders battle, learn, and visualize algorithms.

📌 Problem Statement

Learning Data Structures and Algorithms (DSA) is one of the most essential skills for computer science students and developers, but most learners struggle with:

Understanding the logic flow behind algorithms.

Staying consistent and motivated while practicing.

Facing boring, exam-style platforms with no engagement or feedback loop.

To solve this, we built AlgoArena — a gamified coding platform where users practice DSA through interactive challenges, earn XP, compete with peers, and now even visualize their code execution using the new CodeVisualizer feature.

The CodeVisualizer allows users to paste DSA-based code (like sorting, recursion, or tree algorithms) and instantly see the step-by-step visual representation of how the algorithm executes — helping them understand logic intuitively rather than just reading static code.

AlgoArena combines education, competition, and visualization into one powerful learning ecosystem.

🚀 Project Overview

AlgoArena is a full-stack web application that:

Makes coding practice fun and competitive through gamification.

Provides instant code execution and feedback for DSA problems.

Helps users learn visually through the CodeVisualizer module.

Tracks progress with XP, badges, and leaderboards.

Encourages daily consistency with streaks and challenges.

⚙️ Key Features
Feature	Description
🧩 Code Editor	Users can write, compile, and run code directly in-browser for C, C++, Python, and Java.
🏅 Gamified Learning	Earn XP, coins, and badges for solving problems and maintaining streaks.
🧠 CodeVisualizer	Paste DSA-based code to see step-by-step execution flow with animations and variable tracking.
🧾 Leaderboard System	Global, weekly, and college leaderboards to encourage competition.
🎯 Daily Challenges	One problem per day to maintain coding streaks and consistency.
🥇 Tournaments	Real-time contests with countdown timers and instant scoring.
👥 Profile Dashboard	Displays XP, streaks, accuracy rate, and progress stats.
🧰 Admin Panel	Allows uploading new coding problems and managing users.
🔒 Secure Authentication	JWT-based login/signup system with password encryption.
🖼️ CodeVisualizer (New Feature)

The CodeVisualizer helps users see how algorithms run, instead of just reading them.

Example Use Case:
A user pastes their Python code for a Merge Sort algorithm.

The visualizer highlights each step: dividing the array, merging elements, comparing values, and returning the final result.

Arrows and color changes represent recursive calls and data flow.

The goal is to bridge the gap between code and mental visualization — making learning logic simpler and faster.

Supported Algorithms:
Sorting algorithms (Bubble, Selection, Merge, Quick), searching, recursion (factorial, Fibonacci), and tree/graph traversals (DFS, BFS).

🧩 System Architecture
Frontend (React.js / Next.js)
     |
     |--> Handles UI, code editor, leaderboard, and visualization
     |
Backend (Node.js + Express)
     |
     |--> Manages users, XP, challenges, leaderboard, and compiler requests
     |
Database (MongoDB)
     |
     |--> Stores user data, submissions, rankings, and problem sets
     |
Compiler API (Judge0 / Sphere Engine)
     |
     |--> Executes user-submitted code safely in sandbox

🛠️ Tech Stack
Layer	Technology
Frontend	React.js / Next.js / Tailwind CSS
Backend	Node.js with Express
Database	MongoDB
Compiler Execution	Judge0 or Sphere Engine API
Authentication	JWT with bcrypt encryption
Visualization Engine	Custom algorithm visualizer built using D3.js / Canvas API
Hosting	Vercel (frontend), Render / AWS (backend)
🔍 Workflow

User signs up or logs in.

Selects a DSA problem from available challenges.

Writes and submits code in the online editor.

Backend sends code to the compiler API for safe execution.

Results are validated and XP/coins are awarded.

User can switch to CodeVisualizer mode to visualize their logic step-by-step.

Leaderboard and badges update automatically based on performance.

📅 Future Enhancements

AI Mentor Mode: Gives intelligent hints when users get stuck.

Voice-Assisted Learning: Explains algorithm steps using speech.

Web3 Achievements: Mint NFT badges for major milestones.

Team Battles: Group-based tournaments between colleges.

Mobile App Version: For on-the-go DSA practice and streak tracking.

🧑‍💻 Impact

AlgoArena transforms the way students learn and practice algorithms.
By merging visual learning, gamification, and competition, it improves:

Retention rate

Logical understanding

Motivation and coding consistency

The platform aims to help learners think like programmers instead of just writing syntax.

📂 Repository Structure
algoarena/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   └── utils/
│   └── package.json
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   ├── server.js
│   └── package.json
├── README.md
└── LICENSE

⚡ Getting Started
1️⃣ Clone the repo
git clone https://github.com/yourusername/algoarena.git

2️⃣ Install dependencies

Frontend:

cd frontend
npm install


Backend:

cd backend
npm install

3️⃣ Run the project

Frontend:

npm start


Backend:

node server.js

4️⃣ Open in browser

Visit: http://localhost:3000

🏆 Summary

AlgoArena = LeetCode + Game + Visualizer
A platform built to make DSA learning interactive, rewarding, and intuitive.
