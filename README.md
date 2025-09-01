# 📄 Resume Parser using Python & NLP  

This project is a **smart Resume Parser** built using Python and Natural Language Processing (NLP).  
It extracts key details such as **Name, Contact Info, Skills, Education, and Work Experience** from resumes in PDF/DOCX formats, making it easier for recruiters and companies to screen candidates automatically.  

---

## 🔧 Technologies Used  

- **Python**  
- **NLTK / Spacy** (for text processing & NLP)  
- **PyPDF2** / **pdfplumber** (for parsing PDF resumes)  
- **python-docx** (for DOCX parsing)  
- **Regular Expressions (Regex)**  
- **Jupyter Notebook / Colab / VS Code**  

---

## 📌 Features  

✔️ Extracts candidate’s **Name, Email, Phone Number, LinkedIn, GitHub**  
✔️ Detects and categorizes **Technical Skills & Soft Skills**  
✔️ Identifies **Education details** (Degrees, Universities, Graduation Year)  
✔️ Extracts **Work Experience & Projects**  
✔️ Saves parsed data in a **structured format (JSON/CSV)**  
✔️ Easy to customize for **company-specific requirements**  

---

## 📁 What You Need to Run  

- Python 3.8 or higher  
- A folder of resumes in **PDF or DOCX** format  
- Install the dependencies from `requirements.txt`  

---

## 🚀 How to Run  

1. Clone this repository:  


   git clone https://github.com/Prabhakarrayal/resume-parser
   cd resume-parser
Install required libraries:


pip install -r requirements.txt
Add your resumes (PDF/DOCX) in the /resumes folder.

Run the parser script or Jupyter Notebook:

python resume_parser.py
Extracted results will be saved in output.csv or printed on screen.

## 🛠️ Customization
To change keywords for skills, edit the skills.json file.

To add company-specific fields (like certifications or achievements), update the parser.py logic.

To save data in a database instead of CSV, connect with MongoDB/MySQL in the script.

## 🌟 Use Case for Companies
HR Teams → Automatically filter resumes based on job requirements.

Recruitment Platforms → Integrate this parser as a backend module.

Startups & Enterprises → Save screening time by structuring unorganized resume data.

## 🚀 Future Improvements
Add Machine Learning models for smarter skill & role classification

Support for multi-language resumes

Build a Flask/Streamlit Web UI for uploading resumes

Integration with ATS systems for real-time processing

## ✍️ Author
Prabhakar Rayal
B.Tech CSE | Graphic Era Hill University
📍 Rishikesh, Uttarakhand, India

GitHub Profile | LinkedIn Profile
