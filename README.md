# 🌿 AyurWell – AI Powered Ayurvedic Healthcare Platform

AyurWell is an AI-driven healthcare and wellness platform that combines Ayurvedic principles with intelligent recommendation systems to provide personalized health insights, dietary guidance, and patient assessments.

Designed to bridge traditional Ayurveda with modern technology, AyurWell helps patients and practitioners make informed wellness decisions through structured assessments, ML-assisted recommendations, and health tracking.

🚀 Live Demo: https://ayurwell2-o.vercel.app/

---

## ✨ Features

### 👤 Smart Patient Assessment
Structured multi-step assessment system:

- Basic Profile
- Ayurvedic Assessment
- Lifestyle Analysis
- Medical History
- Symptom Tracking
- Dietary Habits
- Doctor Notes

Collects:

- Age
- Gender
- Height / Weight
- Prakriti
- Vikriti
- Activity level
- Sleep pattern
- Symptoms
- Medical conditions
- Allergies
- Dietary preferences

---

### 🧠 AI + ML Recommendation System

Hybrid recommendation pipeline:

Patient Profile

↓  

Hard Filters

↓  

Disease Mapping

↓  

Knowledge Retrieval

↓  

Ranking Model

↓  

LLM Explanation Layer

↓  

Safety Layer

↓  

Personalized Recommendation

Recommendations include:

✅ Recommended foods  
✅ Foods to avoid  
✅ Ayurvedic reasoning  
✅ Confidence scores  
✅ Risk level assessment  

---

## 🔬 Core AI Features

### Dosha Detection

Supports:

- Vata
- Pitta
- Kapha
- Mixed constitution analysis

Uses ML-assisted prediction with confidence scoring.

---

### Intelligent Food Recommendations

Considers:

- Symptoms
- Allergies
- Medical conditions
- Lifestyle
- Region
- Goals
- Diet preferences
- Ayurvedic body constitution

No random suggestions.

Uses:

- Rule Engine
- Retrieval
- Ranking
- AI explanation layer

---

### 📈 Progress Tracking

Track:

- Wellness progress
- Assessments
- Diet plans
- Health history
- Recommendations

---

### 🩺 Practitioner Dashboard

Doctors and practitioners can:

- Review assessments
- Create diet plans
- Add recommendations
- Add notes
- Monitor patient history

---

## 🏗 System Architecture

```text
Frontend (Next.js)

↓

Authentication Layer

↓

Flask API Backend

↓

MongoDB Database

↓

ML Recommendation Service

├── Dosha Prediction Model

├── Food Recommendation Model

├── Retrieval System

└── Safety Layer

↓

AI Explanation Layer
