# 🎮 TechAid Gamification Module

## Overview
The Gamification Module is a key part of **TechAid**, a system designed to teach elderly users how to use modern technologies. Through positive and accessible game elements, we aim to motivate, engage, and support seniors in their learning journey.

## Key Features
- **Progress Badges:** Earn badges by completing lessons and mastering new skills.
- **Leveling System:** Unlock new levels as users advance through different technology topics.
- **Friendly Challenges:** Participate in simple, non-competitive challenges to reinforce learning.
- **Daily Goals:** Gentle reminders and small tasks encourage daily practice without pressure.
- **Customizable Avatars:** Personalize user profiles with friendly, easy-to-use avatars.
- **Supportive Feedback:** Positive, encouraging feedback designed to build confidence and celebrate small victories.

## Design Principles
- **Accessibility First:** Large fonts, high-contrast colors, simple language, and intuitive navigation.
- **Positive Reinforcement:** Focused on encouragement rather than competition.
- **Low Complexity:** Simplified interactions to ensure usability for users unfamiliar with technology.
- **Meaningful Rewards:** Rewards directly tied to learning achievements, promoting intrinsic motivation.

## Folder Structure
```plaintext
TechAid-Gamification/
├── public/                 # Static assets (images, icons, etc.)
├── src/
│   ├── assets/              # Avatars, badges, and media files
│   ├── components/          # Reusable UI components (cards, buttons, etc.)
│   ├── pages/               # Main pages/screens (dashboard, challenges, etc.)
│   ├── services/            # API services (user progress, achievements)
│   ├── hooks/               # Custom React hooks
│   ├── contexts/            # Context providers (e.g., UserContext)
│   ├── styles/              # CSS/SCSS files or styled-components
│   ├── utils/               # Utility functions
│   └── App.jsx              # Main app component
├── package.json             # Project dependencies and scripts
├── README.md                # Project documentation
└── .gitignore               # Git ignore rules

## 🛠 Prerequisites
```
- [Python 3.7+](https://www.python.org/downloads/)
- Git
```

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Tech-Aid-Project/gamification-repository.git
cd gamification-repository
```
### 2. Create a Virtual Environment (optional, but recommended)
```bash
python -m venv venv
```

Activate the virtual environment:

- Windows:
```bash
venv\Scripts\activate
```
- macOS/Linux:
```bash
source venv/bin/activate
```

### 3. Install the Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Project
```bash
python main.py
```
