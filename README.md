# Nudge – AI-Powered Fitness & Nutrition App

Nudge is a mobile application designed to help users build healthier habits through AI-driven workout planning and nutrition tracking.

The app focuses on simplicity, personalization, and actionable guidance instead of static plans.

---

## 🚀 Features

### 🏋️ Workout System
- AI-generated workout plans
- Structured workout flow:
  - Pre-workout (preparation)
  - Warm-up
  - Active workout (set-based)
  - Rest timer
  - Cooldown
  - Post-workout summary
- Step-by-step execution (not just static lists)

---

### 🍽 Nutrition Tracking
- Food logging with search
- Macro tracking (calories, protein, carbs, fat)
- AI fallback for unknown foods
- Daily nutrition insights

---

### 🧠 AI Coach
- Generates workout plans based on user context
- Provides explanations and insights
- Adapts to user behavior over time

---

### 📊 Smart Insights
- Daily analysis
- Habit tracking foundation
- Performance-based feedback (planned)

---

## 🏗 Tech Stack

### Frontend
- Flutter (Dart)
- Provider (state management)

### Backend
- Firebase
  - Authentication
  - Firestore
  - Cloud Functions

### AI
- LLM-based workout & nutrition logic
- Structured JSON responses for deterministic UI flow

---

## 🔄 Workout Flow Architecture

The workout system is built as a state machine:


Ready → PreWorkout → WarmUp → Workout → Rest → Cooldown → PostWorkout


- AI generates the full workout plan once
- The app executes the plan locally
- No per-step AI calls (performance + cost optimized)

---

## 📦 Project Structure (Simplified)


lib/
├── core/
├── features/
│ ├── workout/
│ ├── nutrition/
│ ├── coach/
├── providers/
├── services/
└── ui/

---

## 🔐 Privacy & Terms

- [Privacy Policy](https://m0nareks.github.io/Nudge-legal/privacy.html)
- [Terms of Service](https://m0nareks.github.io/Nudge-legal/terms.html)

---

## ⚙️ Setup

1. Clone the repo:
```bash
git clone https://github.com/your-username/nudge.git
Install dependencies:
flutter pub get
Run the app:
flutter run
🧪 Status

This project is under active development.

Planned improvements:

Adaptive workout system
Wearable integrations
Advanced analytics
Premium features
📬 Contact

For questions or feedback:
oguzhanbodur23@gmail.com
