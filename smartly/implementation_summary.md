# VolunteerIQ Implementation Details

VolunteerIQ is a modern web prototype designed to streamline NGO operations using Google Gemini AI.

## 🚀 Core Features

### 1. Data Input Module
- **Community Needs**: Coordinators can log urgent needs with details like category, location, and urgency levels (1-5).
- **Volunteer Registry**: A simple interface to manage available volunteers and their skill sets.

### 2. AI Intelligence (Powered by Gemini)
- **Need Prioritization**: Uses the Gemini API to analyze the list of community needs and rank them (Critical, High, Medium) with automated reasoning.
- **Smart Matching**: Automatically pairs the best volunteers to the most urgent needs based on skills, location, and situational context.

### 3. Dashboard Analytics
- Real-time tracking of:
    - Total Needs submitted.
    - Available Volunteers.
    - Successful Matches.
    - Critical Tasks identified by AI.

## 🛠️ Technology Stack
- **Frontend**: Pure HTML5, Vanilla JavaScript, CSS3.
- **Styling**: Modern dark theme with Inter typography, Font Awesome icons, and glassmorphism effects.
- **AI Engine**: Google Gemini 2.5 Flash (via `v1` REST API).
- **State Management**: Browser-based session state (no backend required for this prototype).

## 🔑 Setup Instructions
1. Open `index.html` in a code editor.
2. Search for the constant `GEMINI_API_KEY` in the `<script>` section.
3. Replace `'MY_API_KEY'` with your actual **Google Gemini API Key**.
4. Open `index.html` in any modern web browser.
5. Start adding Needs and Volunteers to see the AI in action!

---
*Created by Antigravity AI for VolunteerIQ Prototype.*
