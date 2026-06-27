# 🚀 AI Resume Screening System using NLP & Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-BERT%20%7C%20spaCy-success?style=for-the-badge)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-MLP-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📌 Project Overview

The **AI Resume Screening System** is an end-to-end application that automates resume analysis using **Natural Language Processing (NLP)** and **Machine Learning**. It extracts candidate information from PDF resumes, identifies technical and soft skills, calculates professional experience, predicts the most suitable job category, and presents the results through an interactive dashboard.

The primary objective of this project is to simplify the recruitment process by reducing manual resume screening and providing recruiters with structured candidate insights.

---

## ✨ Key Features

- 📄 Resume Parsing from PDF
- 🤖 BERT-based Named Entity Recognition (NER)
- 🧠 Job Role Prediction using Machine Learning (MLP)
- 💼 Automatic Experience Calculation
- 🛠 Technical & Soft Skill Extraction
- 🏢 Company & Education Detection
- 📊 Interactive Candidate Dashboard
- ⚡ Fast Resume Processing
- 📈 Resume Analytics and Visualization

---

## 🏗️ Project Workflow

```text
                Resume PDF
                    │
                    ▼
        Text Extraction (PyMuPDF)
                    │
                    ▼
       NLP Processing Layer
    (BERT + spaCy + Regex)
                    │
                    ▼
     Structured Candidate Data
                    │
                    ▼
      Machine Learning Model
      (Job Role Prediction)
                    │
                    ▼
      Interactive Dashboard
```

---

## 🛠 Tech Stack

### Programming Language

- Python

### Machine Learning & NLP

- BERT (bert-base-NER)
- spaCy
- Scikit-learn
- PyTorch

### Backend

- FastAPI

### Data Processing

- Pandas
- NumPy
- PyMuPDF
- Regex

### Frontend

- HTML
- CSS
- JavaScript

---

## 📊 Model Performance

| Metric | Value |
|---------|------:|
| Classification Accuracy | **70.37%** |
| Supported Job Categories | **24** |
| Dataset Size | **2,400+ Resumes** |

The Multi-Layer Perceptron (MLP) model predicts the most suitable job category using TF-IDF features combined with engineered resume features.

---

## 🤖 NLP Pipeline

The NLP pipeline automatically extracts:

- Candidate Name
- Email Address
- Phone Number
- Technical Skills
- Soft Skills
- Companies Worked At
- Educational Institutions
- Professional Experience

The system combines **BERT**, **spaCy**, and **rule-based NLP techniques** to generate structured candidate information.

---

## 📂 Project Structure

```text
AI-Resume-Screening-System/
│
├── app.py
├── train_dl.py
├── requirements.txt
├── resume_mlp_model.pth
├── models/
├── datasets/
├── static/
├── templates/
├── README.md
└── ...
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ai-resume-screening-system.git
```

### Navigate to Project

```bash
cd ai-resume-screening-system
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Download spaCy Model

```bash
python -m spacy download en_core_web_sm
```

### Run the Application

```bash
python app.py
```

---

## 🚀 How It Works

1. Upload a PDF resume.
2. The system extracts text using **PyMuPDF**.
3. BERT and spaCy identify important entities such as skills, companies, education, and experience.
4. Resume features are processed and passed to the Machine Learning model.
5. The model predicts the most suitable job category.
6. Results are displayed through an interactive dashboard.

---

## 🎯 Future Improvements

- ATS Compatibility Score
- Resume Ranking System
- Multi-Resume Comparison
- AI-generated Candidate Summary
- Cloud Deployment
- Recruiter Dashboard
- Authentication & User Management
- LLM-based Resume Feedback

---

## 📚 Dataset

- Kaggle Resume Dataset (2,400+ resumes)

---

## 📖 References

- Devlin et al. - BERT: Pre-training of Deep Bidirectional Transformers
- Hugging Face Transformers
- spaCy NLP Documentation
- Scikit-learn Documentation
- Kaggle Resume Dataset

---

## 👨‍💻 Author

**Vansh Arora**

B.Tech Computer Science Engineering (AI & Data Engineering)

### Skills

- Python
- Machine Learning
- Natural Language Processing
- FastAPI
- SQL
- React
- Data Structures & Algorithms
