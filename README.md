# resume-classification-system
An AI-powered Resume Classification System built with Python, Streamlit, TF-IDF, and Machine Learning that automatically categorizes PDF resumes into job domains.

# 📄 Automatic CV Scanner & Resume Classifier

An AI-powered Resume Classification System developed using **Python**, **Machine Learning**, and **Streamlit**.

The application automatically analyzes uploaded PDF resumes, predicts their job category using a trained Machine Learning model, organizes resumes into categorized folders, and generates a downloadable CSV report.

---

## 🚀 Features

- Upload multiple PDF resumes
- Automatic text extraction from PDF files
- Resume text preprocessing
- TF-IDF feature extraction
- Machine Learning-based resume classification
- Automatically creates folders based on predicted job category
- Saves resumes into their respective folders
- Download prediction results as CSV
- Simple and interactive Streamlit interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- Pickle
- PyPDF
- Regular Expressions (Regex)

---

## 📂 Project Structure

```
Automatic-CV-Scanner/
│
├── app.py
├── model.pkl
├── tfidf.pkl
├── requirements.txt
├── README.md
└── categorized_resumes/
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/automatic-cv-scanner-ml.git
```

Move into the project directory

```bash
cd automatic-cv-scanner-ml
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📥 How It Works

1. Launch the Streamlit application.
2. Upload one or more PDF resumes.
3. Specify the output folder.
4. Click **Categorize Resumes**.
5. The system:
   - Extracts resume text
   - Cleans the text
   - Converts text into TF-IDF vectors
   - Predicts the resume category
   - Creates folders automatically
   - Stores resumes in their predicted folders
6. Download the generated CSV report.

---

## 📊 Supported Categories

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

*(Add screenshots here)*

---

## 🎯 Future Improvements

- Resume ranking
- Skill extraction
- ATS score prediction
- Experience detection
- Education extraction
- Contact information extraction
- Named Entity Recognition (NER)
- Multi-language resume support
- Deep Learning models (BERT, RoBERTa)
- Resume recommendation system
- Deploy on Streamlit Cloud

---

## 👩‍💻 Author

**Noor Mustafa Chohan**

BS Artificial Intelligence

Pakistan

---

## ⭐ If you like this project

Please consider giving it a ⭐ on GitHub.
