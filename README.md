# 🧠 Resume Parser & QA Bot

An OCR-powered Resume Parser with AI-based Question Answering — built using **Python, Gradio, spaCy, Transformers, and Tesseract OCR**.

This tool can:
- Extract **Phone Number, Email, Name, Address, and Skills** from resumes
- Automatically **score resumes** based on LinkedIn ATS-style section checks
- Support **multiple PDF resumes**
- Let you **ask questions** about resume content via a **Gradio chat interface**

---

## ✨ Features
✅ Extracts clean contact details (phone, email, name, address)  
✅ NLP-based **skill extraction** (custom skill list for better accuracy)  
✅ ATS-style **section scoring** (Education, Skills, Experience, Projects)  
✅ Supports scanned PDFs with **OCR**  
✅ **AI Question-Answering** from resume text  
✅ **User-friendly Gradio interface**  

---

## 📂 Project Structure
resume-parser-bot/
│── app.py # Main application code
│── requirements.txt # Python dependencies
│── README.md # Project documentation
│── sample_resumes/ # Example resumes for testing


---

## 🚀 Installation & Usage

### **1. Clone the Repository**
```bash
git clone https://github.com/<your-username>/resume-parser-bot.git
cd resume-parser-bot

pip install -r requirements.txt


sudo apt-get install poppler-utils tesseract-ocr
python -m spacy download en_core_web_sm
python -m nltk.downloader punkt

python app.py

