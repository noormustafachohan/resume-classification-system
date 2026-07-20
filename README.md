# 📄 AI Resume Classification System

An AI-powered Resume Classification System built with **Python**, **Machine Learning**, and **Streamlit**. This application automatically analyzes uploaded PDF resumes, predicts their job category using a trained Machine Learning model, organizes resumes into categorized folders, and generates a downloadable CSV report.

---

## 🚀 Features

- 📂 Upload multiple PDF resumes simultaneously
- 📄 Extract text from PDF resumes automatically
- 🧹 Clean and preprocess resume text
- 🤖 Predict resume category using a trained Machine Learning model
- 📁 Automatically organize resumes into category-specific folders
- 📊 Generate a downloadable CSV report of predictions
- 🖥️ Simple and interactive Streamlit web interface

---

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Framework | Streamlit |
| Machine Learning | Scikit-learn |
| Feature Extraction | TF-IDF Vectorizer |
| Data Processing | Pandas |
| PDF Processing | PyPDF |
| Model Storage | Pickle |
| Text Processing | Regular Expressions (Regex) |

---

## 📂 Project Structure

```
resume-classification-system/
│
├── app.py                     # Main Streamlit application
├── model.pkl                  # Trained Machine Learning model
├── tfidf.pkl                  # TF-IDF vectorizer
├── Resume.csv                 # Dataset used for training
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
├── LICENSE                    # MIT License
├── .gitignore                 # Git ignore rules
└── screenshots/
    ├── home.png
    └── results.png
```

---

## 📷 Application Preview

### 🏠 Home Screen

The Streamlit interface allows users to upload multiple PDF resumes, specify an output directory, and automatically classify resumes into job categories using a trained Machine Learning model.

<p align="center">
  <img src="screenshots/home.jpeg" width="900">
</p>

---

### ✨ Features Demonstrated

- Upload multiple PDF resumes
- Automatic PDF text extraction
- Resume category prediction
- Organized output folders
- CSV report generation
- User-friendly Streamlit interface

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/noormustafachohan/resume-classification-system.git
```

### 2. Navigate to the project folder

```bash
cd resume-classification-system
```

### 3. Install required libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

---

## 💻 How It Works

1. Launch the application.
2. Upload one or more PDF resumes.
3. Enter the output folder name (optional).
4. Click **Categorize Resumes**.
5. The application:
   - Extracts resume text
   - Cleans and preprocesses the text
   - Converts text into TF-IDF feature vectors
   - Predicts the resume category
   - Creates category folders automatically
   - Saves each resume into its predicted folder
6. Download the generated CSV report.

---

## 📊 Supported Resume Categories

The model can classify resumes into the following categories:

- Advocate
- Arts
- Automation Testing
- Blockchain
- Business Analyst
- Civil Engineer
- Data Science
- Database
- DevOps Engineer
- DotNet Developer
- Electrical Engineering
- ETL Developer
- Hadoop
- Health & Fitness
- HR
- Java Developer
- Mechanical Engineer
- Network Security Engineer
- Operations Manager
- PMO
- Python Developer
- SAP Developer
- Sales
- Testing
- Web Designing

---

## 📷 Application Preview

### Home Screen

> *(Add a screenshot here after uploading to GitHub.)*

```
screenshots/home.png
```

### Prediction Results

> *(Add a screenshot here after uploading to GitHub.)*

```
screenshots/results.png
```

---

## 📈 Future Improvements

- Resume ranking based on job requirements
- ATS (Applicant Tracking System) compatibility score
- Skill extraction from resumes
- Education and experience extraction
- Contact information extraction
- Named Entity Recognition (NER)
- Multi-language resume support
- Deep Learning models (BERT/RoBERTa)
- Resume recommendation system
- Cloud deployment

---

## 📋 Requirements

```
streamlit
pandas
numpy
scikit-learn
pypdf
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

### Noor Mustafa Chohan

**BS Artificial Intelligence**  
Pak-Austria Fachhochschule Institute of Applied Sciences and Technology (PAF-IAST), Pakistan

### Connect with me

- GitHub: https://github.com/noormustafachohan
- LinkedIn: https://www.linkedin.com/in/noormustafachohan/

---

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates future improvements.

---

### Project Highlights

✔ Machine Learning Project

✔ Streamlit Web Application

✔ Resume Classification

✔ Natural Language Processing (NLP)

✔ PDF Text Extraction

✔ Automated Resume Organization

✔ CSV Report Generation
