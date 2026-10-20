# Snap Class – AI Attendance System

An attendance system that marks a whole class from a single group photo, so teachers don't have to call roll.

> **Status: in development.** Features marked ✅ work now. Features marked 🔄 are still being built.

## What it does

- Detects and identifies multiple students from one group photograph
- Gives teachers and students their own portals
- Supports QR-code check-in
- Shows attendance analytics

## Features

- ✅ Face recognition from a group photo (dlib face embeddings + SVC classifier)
- ✅ Teacher and student portals
- ✅ Secure login with bcrypt-hashed passwords
- ✅ QR-code check-in
- ✅ Attendance data stored in Supabase (PostgreSQL)
- 🔄 More features in progress

## Tech stack

Python, Streamlit, OpenCV, face_recognition, dlib, scikit-learn (SVC), Supabase (PostgreSQL), bcrypt, QR code generation

## Project structure

```
AI-Attendance-System/
├── app.py              # Streamlit entry point
├── src/                # Application code
├── requirements.txt    # Python dependencies
└── .gitignore
```

<!-- Add your screenshots to a "screenshots" folder, then delete this line and the closing arrow line below to show them.

## Screenshots

![Teacher dashboard](screenshots/dashboard.png)
![Group photo result](screenshots/group-photo.png)

-->

## How to run

1. Clone the repository:

   ```bash
   git clone https://github.com/subhajitjana15112003/AI-Attendance-System.git
   cd AI-Attendance-System
   ```

2. Install the libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a Supabase project and add its URL and key to your Streamlit secrets file (`.streamlit/secrets.toml`). Do not upload this file to GitHub.

4. Start the app:

   ```bash
   streamlit run app.py
   ```

## Roadmap

- Test recognition accuracy on more students
- Improve the attendance analytics
- Deploy the app online

## Author

**Subhajit Jana** – B.Tech CSE (AI & ML), The Neotia University

[GitHub](https://github.com/subhajitjana15112003) | [LinkedIn](https://www.linkedin.com/in/subhajit-jana-b433b2309)
