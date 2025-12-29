# 🎒 Adaptive Math Tutor for Grade 5 Students

A simple **web-based adaptive math tutor** designed to help **5th grade elementary students** understand **addition of hundreds** through personalized practice and child-friendly feedback.

This project focuses on **real educational impact**, tested with actual students, and implements a lightweight adaptive learning logic.

---

## 🌟 Key Features
- Adaptive question difficulty based on student performance  
- Friendly and encouraging feedback for children  
- Focused learning on addition of hundreds  
- Simple and intuitive web interface  
- Designed for small group learning (10 students)  

---

## 🎯 Project Goal
The goal of this project is to support elementary students in mastering addition of hundreds by:
- Reducing common mistakes such as forgetting to carry numbers  
- Adjusting question difficulty based on understanding level  
- Improving learning confidence through positive feedback  
- Providing a simple AI-assisted learning companion  

---

## 👥 Target Users
- 10 Grade 5 elementary school students  
- Designed for use with real children (tested with siblings and peers)  

---

## 📘 Learning Scope
**Mathematics – Addition of Hundreds**
- Addition without carrying  
- Addition with carrying in ones  
- Addition with carrying in ones and tens  

---

## 🧠 How the Adaptive System Works
1. A student answers a math question  
2. The system checks correctness and identifies common mistakes  
3. The student’s understanding score is updated  
4. The next question difficulty is adjusted automatically  
5. Friendly feedback is shown to guide learning  

---

## 🧮 Adaptive Logic
| Understanding Score | Question Difficulty |
|--------------------|--------------------|
| < 0.4              | Easy               |
| 0.4 – 0.7          | Medium             |
| > 0.7              | Challenging        |

---

## 📊 Success Metrics
- Increased accuracy over time  
- Reduced repetition of the same mistakes  
- Students willing to continue practicing  
- Improved confidence when solving math problems  

---

## 🖥 Application Interface
The web application includes:
- Home / Start screen  
- Question screen  
- Feedback screen  
- Simple progress indicator  

*(Screenshots or demo GIF can be added here)*

---

## 🛠 Tech Stack
- **Python**
- **Streamlit**
- Rule-based adaptive learning logic
- In-memory / JSON data storage

---

## 🚀 How to Run the App
```bash
pip install -r requirements.txt
streamlit run app.py
