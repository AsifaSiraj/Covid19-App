# COVID-19 Screening Tool

A responsive, browser-based COVID-19 self-assessment tool built using HTML, CSS, Bootstrap 4, and JavaScript.  

This application allows users to perform a guided symptom screening through an interactive modal questionnaire and receive a basic risk-level assessment.

---

## 📌 Project Overview

The COVID-19 Screening Tool is a lightweight front-end web application that:

- Provides COVID-19 awareness information
- Displays symptoms and prevention guidelines
- Conducts a 10-question screening assessment
- Generates a basic risk classification result

The application uses Bootstrap modals for structured UI flow and jQuery for dynamic question transitions and result handling.

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS + jQuery)
- Bootstrap 4.0.0
- Popper.js

CDN Dependencies:
- Bootstrap CSS & JS
- jQuery (Slim build)
- Popper.js

---


---

## 🚀 Features

### 1️⃣ Information Section
- What is COVID-19
- Symptoms overview
- Prevention guidelines
- WHO reference link

### 2️⃣ Interactive Screening Flow
- 10 symptom and exposure-based questions
- Sequential navigation logic
- Real-time answer recording
- Dynamic result display

### 3️⃣ Risk Classification Results

The tool provides one of three outcomes:

- **Result 1:** High Probability
- **Result 2:** Suspected Case
- **Result 3:** Low Risk / No Immediate Concern

---

## 🧠 Screening Logic

The screening decision is based on predefined symptom combinations.

Example logic (simplified):

- High probability if key symptoms (fever, dry cough, breathlessness, travel/contact history, etc.) are present.
- Suspected case if primary respiratory symptoms are present.
- Otherwise classified as low risk.

> ⚠️ Note: The logic is basic conditional logic and is not a medical diagnostic system.

---

## 💻 How to Run the Project

1. Clone or download the repository:
git clone https://github.com/AsifaSiraj/Covid19-App/


2. Ensure folder structure (especially `/img` directory) is intact.

3. Open `index.html` in your browser.

No server setup required.

---

## ⚠️ Important Disclaimer

This tool is for educational and demonstration purposes only.

It is:
- NOT a medical diagnostic tool
- NOT a substitute for professional healthcare advice
- NOT officially affiliated with any health authority

For accurate medical guidance, consult certified healthcare professionals or official public health organizations.

---

## 🔧 Potential Improvements

- Fix logical condition errors in result calculation
- Convert inline JavaScript to modular JS file
- Replace jQuery with modern ES6
- Add accessibility enhancements (ARIA improvements)
- Add form validation and score-based calculation
- Integrate backend API for real medical screening systems
- Improve mobile-first UI responsiveness
- Add analytics tracking

---

## 📈 Future Enhancements

- React or Vue version
- Backend integration (Node.js / Django)
- Database logging
- Admin dashboard
- Multilingual support
- Deployment on Vercel / Netlify
- Progressive Web App (PWA) support

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

## 👨‍💻 Author

Developed as a front-end web screening demo project.

---

## 🌍 Reference

World Health Organization (WHO)  
https://www.who.int/

---

