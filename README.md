# vibe_coding_hackathon
# 🧾 Smart Finance Tracker

> Helping small traders track income and expenses effortlessly using voice and photo input — with style and smart UX.

---

## 🚨 PROBLEM STATEMENT

Many small traders don’t track their income or expenses and have no idea if they’re making a profit.  

🛠️ **Challenge:** Build a mobile/web app that uses voice or photo input to help business owners track income and expenses in real-time.

---

## 🚀 OBJECTIVE

Build a visually stunning, fully functional web application using:

- `HTML`, `CSS`, `JavaScript` (frontend)
- `Python` (Flask backend logic)
- `MySQL` (database)

✅ Special emphasis on **creative animations**, **transitions**, and **interactive UI/UX**

---

## 🔥 KEY REQUIREMENTS

### ✅ Functional Features

Users can:
- 🎙️ Record voice to log income/expenses
- 📸 Upload photos of receipts
- 📊 View, filter, and analyze transactions

Backend should:
- Process voice-to-text 🎤
- Perform OCR on images 🧾
- Store & retrieve data from MySQL 📂

---

## 🎨 Creative/Animated UI (Page-by-Page Plan)

### 1. 🏠 Landing Page
- Background: canvas animation (particles/stars)
- Title: typewriter effect
- CTA buttons: glow + pulse
- Smooth scroll: slide/fade/bounce in sections

### 2. 🎙️ Voice & 📸 Photo Input Page
- Page transition: 3D card flip or slide with blur
- Voice input: pulsing mic + sound wave animation
- Photo input: drag/drop + gooey hover + “fly into ledger”
- Response: animated receipt card

### 3. 💰 Transactions Dashboard
- Rows animate in one-by-one
- Animated icons (bounce/float)
- Cards (Profit, Expenses): scale + count-up
- Filters slide in from side
- Add Transaction: glowing button expands on click

### 4. 📈 Analytics & Reports
- Line/bar charts draw from 0
- Pie charts slice in
- Hover tooltips glow/grow
- Filter/date range animated expansion

### 5. ⚙️ Settings & Profile
- Animated avatar ring
- Sun/moon toggle
- Ripple/shadow pop buttons
- Animated confirmations (checkmark confetti)

### 6. ❌ 404 & Offline Experience
- 404: floating sad shopping bag, bobbing text
- Offline: animated starry sky + searching satellite

---

## 📐 RESPONSIVENESS & MOBILE INTERACTIONS

- Mobile menu: radial slide or morph
- Touch reactions: ripple, bounce, light pop
- Swiping: elastic slide transitions

---

## 🧰 TECH STACK

| Layer      | Tools |
|------------|-------|
| Frontend   | HTML5, CSS3, JavaScript (ES6+) |
| Animations | GSAP, Anime.js, ScrollReveal, Lottie |
| Backend    | Python (Flask) |
| Voice API  | Web Speech API / Python + SpeechRecognition |
| OCR        | Python + Tesseract |
| Database   | MySQL |

---

## 📁 FILE STRUCTURE

voice_photo_finance_app/
├── frontend/
│ ├── index.html
│ ├── styles.css
│ ├── app.js
│ ├── components/
│ └── animations/
│ ├── loader.js
│ └── particleBackground.js
├── backend/
│ ├── app.py
│ ├── routes/
│ │ ├── transactions.py
│ │ ├── voice.py
│ │ └── photo.py
│ ├── services/
│ │ ├── speech_to_text.py
│ │ └── photo_ocr.py
│ └── db/
│ ├── models.py
│ └── connection.py
├── database/
│ └── schema.sql
└── README.md


---

## 🧪 DESIGN INTERACTIONS MATRIX

| Element         | Interaction Details |
|-----------------|---------------------|
| Buttons         | Glow, scale, ripple on click |
| Cards           | Bounce/scale in, hover lift |
| Form Fields     | Smooth float label, expanding underline |
| Scroll Sections | Staggered transitions |
| Modals          | Zoom fade with overlay |
| Toasts/Alerts   | Slide in/out with swipe or fade |

---

📌 Credits & Notes

This project is designed for creative coding and real-world utility with a delightful user experience. Animations are not just decoration—they communicate feedback and intent.

---

##AI used
Claude AI
Chatgpt
Lovable + superbase AI
Val town

---

## 🚀 Getting Started

### 🧱 Prerequisites
- Python 3.8+
- Node.js (if using JS-based animation libraries like Lottie)
- MySQL

### ⚙️ Backend Setup
```bash
cd backend
pip install flask flask-cors pytesseract SpeechRecognition
python app.py

