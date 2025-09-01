# 📄 Resume Parser & Skill Extractor

An interactive **Resume Parser** built with **Python 🐍** that extracts **technical skills, experience, and company details** from resumes.  
This project helps recruiters and HR teams analyze candidate profiles efficiently by identifying their **skills, roles, and companies worked at**, with structured outputs ready for automation or further analysis.

---

## ✨ Features
- ✅ Extracts **technical skills** like Python, Java, SQL, Flask, Git, Machine Learning, etc.
- ✅ Counts **frequency of skills** across multiple resumes
- ✅ Detects if a candidate has a **specific skill**
- ✅ Checks if a candidate has **worked at a specific company**
- ✅ Provides **JSON-like output** for easy integration with other tools or dashboards
- ✅ Interactive: Users can modify the script to search for any skill or company dynamically

---

## 🚀 Getting Started

# Clone the repository
git clone https://github.com/your-username/resume-parser.git
cd resume-parser

# Install required Python packages
pip install -r requirements.txt

# Run the parser
python main.py

---

## 🛠 How It Works

The parser reads resumes (PDF or DOCX), extracts text, and identifies **technical skills and experience**. The results are stored in a structured dictionary like this:

result = {
    "skills": {
        "technical": ["Python", "Java", "SQL", "Flask", "Git", "Machine Learning"]
    },
    "experience": [
        {"company": "Google", "role": "Software Intern"},
        {"company": "Infosys", "role": "Developer"}
    ]
}

This allows you to see **exactly what skills the candidate has** and their previous **job experience**, all in a structured format.

---

## 🎯 Customizing Searches

You can easily customize the parser to search for any skill or company:

# Search for a Skill
search_skill = 'Python'  # Change to any skill like 'AWS', 'Java', etc.

# Search for a Company
company_search = 'Google'  # Change to any company like 'Amazon', 'Infosys', etc.

The parser will output whether the candidate has the skill or company experience.

---

## 📊 Example Output

✅ Candidate has technical skill: Python  
❌ Candidate has not worked at Google  

Total resumes processed: 1  

📊 **Technical Skills Frequency:**  
Python: 1  
Java: 1  
SQL: 1  
Flask: 1  
Git: 1  
Machine Learning: 1  

---

## 📌 Future Enhancements

- 🔹 Add **NER (Named Entity Recognition)** for more accurate company and role detection  
- 🔹 Support multiple resume formats (PDF, DOCX, TXT, etc.)  
- 🔹 Build a **web interface** for uploading resumes and viewing results  
- 🔹 **Database integration** for storing parsed results and analytics  
- 🔹 Generate **visual dashboards** for skill distributions across multiple resumes  

---

## 🤝 Contributing

Contributions are welcome! 🚀  
If you’d like to improve the parser, add new features, or optimize performance:

1. Fork the repository  
2. Create a new branch (`git checkout -b feature-name`)  
3. Make your changes  
4. Commit (`git commit -m "Add feature"`)  
5. Push (`git push origin feature-name`)  
6. Open a Pull Request  

---

## 🧑‍💻 Author

**Prabhakar Rayal**  
📍 Rishikesh, Uttarakhand | 🎓 B.Tech CSE Graduate  

🔗 [LinkedIn](https://linkedin.com/in/your-link) | [GitHub](https://github.com/your-username)
