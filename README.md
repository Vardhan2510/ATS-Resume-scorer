# ATS-Resume-scorer
Created a web-based AI Resume Intelligence Suite for ATS optimization. Supports PDF resume upload, job description analysis, and automated ATS scoring. Generates detailed feedback to improve resume visibility and job matching.

# 🚀 ATS Resume Intelligence Suite

An AI-powered ATS (Applicant Tracking System) Resume Checker that analyzes resumes against job descriptions and provides an ATS compatibility score, missing keywords, and personalized improvement suggestions. This project helps job seekers optimize their resumes to improve their chances of passing ATS screening systems.

---

## 📌 Features

- 📄 Upload Resume in PDF format
- 📝 Paste Job Description
- 🤖 AI-powered Resume Analysis
- 📊 ATS Compatibility Score
- 🔍 Missing Keywords Detection
- 💡 Resume Improvement Suggestions
- 📈 Semantic Skill Matching
- ⚡ Real-time Analysis
- 🖥️ Responsive Modern UI

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- Tailwind CSS
- JavaScript (ES6)
- PDF.js (Resume Text Extraction)
- Lucide Icons

### Backend
- Python
- Flask
- Flask-CORS

### AI Model
- Google Gemini 3 Flash API

---

## ⚙️ How It Works

1. User uploads a PDF resume.
2. User pastes the target Job Description.
3. PDF.js extracts the resume text from the PDF.
4. The extracted text and job description are sent to the AI model.
5. Gemini analyzes both documents.
6. The application displays:
   - ATS Match Score
   - Resume Summary
   - Missing Keywords
   - ATS Formatting Feedback
   - Resume Improvement Suggestions

---

## 📂 Project Structure

```
ATS-Resume-Checker/
│
├── index.html
├── app.py
├── requirements.txt
├── static/
├── templates/
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/ATS-Resume-Checker.git
```

```bash
cd ATS-Resume-Checker
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Flask Server

```bash
python app.py
```

The application will start at

```
http://localhost:8080
```

---

## 📸 Screenshots

Add screenshots of:

- Home Page
- Resume Upload
- ATS Analysis Report
- Final Score Dashboard

---

## 📈 Future Improvements

- Multi Resume Comparison
- Support DOCX Files
- Authentication System
- Resume History
- Export Report as PDF
- Dark Mode
- AI Resume Builder
- Interview Question Generator

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Nanda Yaso Vardhan Molugu**

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

## ⭐ Support

If you found this project helpful, please give it a ⭐ on GitHub.
