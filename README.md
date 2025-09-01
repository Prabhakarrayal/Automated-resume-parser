# 📄 Resume Parser & Skill Extractor

An interactive **Resume Parser** built with Python 🐍 that extracts **technical skills, experience, and company details** from resumes.  
This project demonstrates how to analyze candidate profiles, identify technical skills, and check for specific experience (e.g., working at Google).

---

## ✨ Features

- ✅ Extracts **technical skills** (Python, Java, Flask, SQL, etc.)  
- ✅ Counts frequency of skills across resumes  
- ✅ Detects if a candidate has a **specific skill** (e.g., Python)  
- ✅ Checks if a candidate has **worked in a specific company** (e.g., Google)  
- ✅ Provides clean, structured JSON-like output for further processing  

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/resume-parser.git
cd resume-parser
2. Install Requirements
bash
Copy code
pip install -r requirements.txt
3. Run the Parser
bash
Copy code
python main.py
🛠 How It Works
The project parses resumes and stores data like this:

python
Copy code
result = {
    "skills": {
        "technical": ["Python", "Java", "SQL", "Flask", "Git", "Machine Learning"]
    },
    "experience": [
        {"company": "Google", "role": "Software Intern"},
        {"company": "Infosys", "role": "Developer"}
    ]
}
🎯 Customizing Searches
🔍 Search for a Skill
In Cell 7, you can edit this part:

python
Copy code
search_skill = 'Python'
➡️ Change 'Python' to any other skill (e.g., 'AWS', 'Java').

🏢 Search for a Company
In the same cell:

python
Copy code
company_search = 'Google'
➡️ Change 'Google' to any other company (e.g., 'Amazon', 'Infosys').

The script will then tell you whether the candidate has that skill or company experience.

📊 Example Output
yaml
Copy code
✅ Candidate has technical skill: Python
❌ Candidate has not worked at Google

Total resumes processed: 1
📊 Technical Skills Frequency:
Python: 1
Java: 1
SQL: 1
Flask: 1
...
📌 Future Enhancements
Add NER (Named Entity Recognition) for more accurate company/role detection

Support for multiple resume formats (PDF, DOCX, etc.)

Web interface for uploading resumes

Database integration for storing parsed results

🤝 Contributing
Pull requests are welcome! If you’d like to improve the parser, add new features, or optimize performance, feel free to open an issue.

🧑‍💻 Author
Prabhakar Rayal
📍 Rishikesh, Uttarakhand | 🎓 B.Tech CSE Graduate
🔗 LinkedIn | GitHub
