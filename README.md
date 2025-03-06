# Resume Ranking Tool for HR & Recruiters

## 🔍 Overview
The **Resume Ranking Tool** is a web-based application that helps HR professionals and recruiters efficiently analyze and rank resumes based on a given job description. By leveraging **Natural Language Processing (NLP)** and **TF-IDF similarity scoring**, the tool ranks resumes based on their relevance to the job description.

## 🚀 Features
- Upload multiple PDF resumes
- Extracts text, names, and emails from resumes
- Uses **TF-IDF** and **cosine similarity** for ranking
- Displays ranked resumes with similarity scores
- Download results as a CSV file

## 🛠️ Tech Stack & Tools Used
### **Backend:**
- **Flask** - Web framework to build the application
- **spaCy** - NLP library for extracting entities
- **PyPDF2** - Extracts text from PDF resumes
- **Scikit-learn** - Used for **TF-IDF vectorization** and **cosine similarity**
- **Regular Expressions (re)** - Extracts emails and names from resumes
- **CSV Module** - Saves ranked resume results

### **Frontend:**
- **HTML & CSS** - For rendering the web UI
- **Jinja2 (Flask Template Engine)** - Dynamic content rendering

## 📂 Installation & Setup
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/resume-ranking-tool.git
cd resume-ranking-tool
