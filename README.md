# smart-study

## Qualcomm & Microsoft On-Device AI Builders Hackathon

Smart Study is a learning management system designed to help users follow structured study plans efficiently. It provides daily tasks, progress tracking, and interactive quizzes to enhance the learning experience.

Over 24 hours, we built a comprehensive study platform that leverages on-device AI. 


### 🚀 Features
#### 📆 Study Plans – Organize learning materials into daily tasks.
#### ✅ Progress Tracking – Mark tasks as completed and track study progress.
#### ❓ Interactive Quizzes – Answer multiple-choice questions to reinforce learning.
#### 🔍 Search & Filter – Easily find topics and navigate study plans.
#### 🌐 User-Friendly UI – Responsive and intuitive interface for a smooth experience.


### 🛠️ Tech Stack
#### ✅ React/TypeScript frontend with Material UI
#### ✅ Flask backend with SQLite database
#### ✅ Local LLM integration for on-device content analysis
#### ✅ Edge AI for question generation and study plan creation
#### ✅ Performance visualization with Recharts

It was incredible to see what we could build in just 24 hours with the Snapdragon X Elite Copilot+ PC. The power of on-device AI is truly game-changing!

### Start Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate  # For WSL
pip install -r requirements.txt

# Set Qualcomm hardware flags
export QNN_GPU_OPERATIONS=1
export HEXAGON_NPU=1

python app.py
```

### Start Frontend
```bash
cd frontend
npm install
npm run start
```

### Contributors:
- xukunzh Blaire_xukun
- learnerInTheFirstStage Allen Guo
- Crystal0GMY Meiyi Guang
- DucianX Yitian
- cristiipan Yuzheng Pan
