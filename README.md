# 🚀 Student Placement Predictor (Flask + Docker + Machine Learning)

An end-to-end Machine Learning web application that predicts whether a student is likely to get placed based on academic and skill-based performance metrics. The application is powered by a trained Random Forest Classifier, containerized using Docker, and deployed on Render.

---

## 🌐 Live Deployment

**Live Application:**  
https://YOUR-RENDER-URL.onrender.com

**GitHub Repository:**  
https://github.com/satwiktelang1879/Student_Placement_Predictor

---

# 📌 Project Overview

This project demonstrates the complete Machine Learning deployment pipeline:

- Data Preprocessing
- Model Training
- Model Serialization
- Flask Backend
- Interactive HTML/CSS Frontend
- Docker Containerization
- Cloud Deployment using Render

The application accepts student details through a web interface, processes them using the trained model, and instantly predicts whether the student is likely to be placed.

---

# 👨‍💻 Student Profile

- **Name:** Satwik Telang
- **Reg no:** 23BAI11046
- **Institution:** VIT Bhopal University
- **Course:** B.Tech Computer Science Engineering

---

# 🛠️ Tech Stack

### Programming Language

- Python 3.10

### Machine Learning

- Scikit-learn
- Pandas
- NumPy

### Backend

- Flask

### Frontend

- HTML
- CSS

### Model

- Random Forest Classifier

### Deployment

- Docker
- Render

---

# 📂 Project Structure

```
Student_Placement_Predictor/
│
├── static/
│   └── style.css
│
├── templates/
│   └── index.html
│
├── app.py
├── train.py
├── placement_model.pkl
├── requirements.txt
├── Dockerfile
├── .gitignore
└── README.md
```

---

# 📊 Input Features

The prediction model considers the following student attributes:

| Feature | Description |
|----------|-------------|
| CGPA | Student's CGPA |
| Communication Skills | Rating out of 10 |
| Resume Score | Rating out of 10 |
| Coding Score | Rating out of 10 |
| Placement Attendance | Attendance Percentage |

---

# 🎯 Prediction Output

The trained Random Forest model predicts one of the following:

- ❌ Not Placed
- ✅ Placed

The prediction is generated instantly after the user submits the form.

---

# ⚙️ Local Setup

## 1. Clone Repository

```bash
git clone https://github.com/satwiktelang1879/Student_Placement_Predictor.git
```

```bash
cd Student_Placement_Predictor
```

---

## 2. Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Train the Model (Optional)

```bash
python train.py
```

---

## 5. Run Flask Application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

# 🐳 Docker Deployment

## Build Docker Image

```bash
docker build -t student-placement-predictor .
```

## Run Docker Container

```bash
docker run -p 5000:5000 student-placement-predictor
```

Visit

```
http://localhost:5000
```

---

# ☁️ Cloud Deployment

The application is deployed using **Render**.

Deployment workflow:

- Push code to GitHub
- Render automatically detects repository updates
- Docker image is built
- Flask application starts inside the container
- Public URL is generated

---

# ✨ Features

- Clean User Interface
- Instant Placement Prediction
- Machine Learning Powered
- Random Forest Classification
- Dockerized Application
- Responsive Design
- Cloud Hosted on Render

---

# 📸 Application Preview

> Add screenshots of your application here.

Example:

```
images/homepage.png
images/result.png
```

---

# 📈 Future Improvements

- User Authentication
- Database Integration
- Prediction History
- Model Comparison
- Admin Dashboard
- Advanced Analytics

---

# 🙌 Acknowledgements

Built as a Machine Learning Deployment project to demonstrate the complete lifecycle of developing, containerizing, and deploying an ML application using Flask, Docker, and Render.

---

# 📬 Contact

**Satwik Telang**

GitHub:  
https://github.com/satwiktelang1879

LinkedIn:  
https://www.linkedin.com/in/YOUR-LINKEDIN/

---
⭐ If you found this project useful, consider giving it a star!
