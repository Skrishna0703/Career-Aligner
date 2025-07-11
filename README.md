# 🤖 Career Aligner: LinkedIn Job Application Assistant

Career Aligner is a **Streamlit-based AI web application** that helps job seekers optimize their resumes and job applications using the **Google Gemini API**. It provides detailed ATS (Applicant Tracking System) analysis, highlights skill gaps, and generates personalized cover letters and updated resumes to improve job matching success.

---

## 📌 Features

### ✅ Resume Analysis
- Upload resumes in PDF or DOCX format
- Compare resume against a pasted job description
- Get an overall match percentage
- Visual breakdown of matching and missing skills
- Analyze experience and education alignment

### ⚙️ Gemini-Powered Intelligence
- Uses Google's Gemini 1.5 Flash model
- Extracts structured insights from resume and JD
- Generates human-like cover letters and ATS suggestions

### 💼 Cover Letter Generator
- Creates tailored, ATS-optimized cover letters
- Downloadable in plain text format

### 📄 Updated Resume Generator
- Suggests ATS-based improvements
- Downloadable in both PDF and DOCX formats

### 🎨 Modern UI/UX
- Particle background animation
- Responsive layout with hover effects
- Footer with GitHub, LinkedIn, and email links

---

## 🛠️ Technologies Used

| Tool                              | Purpose                                  |
| --------------------------------- | ---------------------------------------- |
| **Streamlit**                     | Web app framework                        |
| **Google Gemini API**             | Resume & cover letter intelligence       |
| **PyPDF2**                        | Resume PDF reading                       |
| **python-docx**                   | DOCX parsing and generation              |
| **reportlab**                     | Resume PDF export                        |
| **streamlit-lottie**              | Lottie animation integration             |
| **dotenv**                        | API key management                       |

---

## 🔐 Environment Variables

Create a `.env` file at the root with the following:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

> You can get your key from [Google AI Studio](https://makersuite.google.com/).

---

## 🚀 Run Locally

```bash
# Step 1: Clone the repository
git clone https://github.com/Skrishna0703/career-aligner.git
cd career-aligner

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Add your .env with Gemini API Key
# Step 4: Run the app
streamlit run app.py
```

---

## 📤 Deployment

You can deploy this app on:

- [Streamlit Cloud](https://streamlit.io/cloud)
- [Render](https://render.com)
- [Heroku](https://heroku.com)

---

## ✨ Future Enhancements

- 🧠 Auto-detect job title and summary from JD
- 📚 Recommend skill-building courses
- 🔐 Add user authentication and history tracking
- 📦 Export ZIP bundle of all generated files

---

## 👨‍💻 Developer

**Shrikrishna Sutar**  
📂 GitHub: [@Skrishna0703](https://github.com/Skrishna0703)  
🔗 LinkedIn: [Shrikrishna Sutar](https://linkedin.com/in/shrikrishna-sutar-3b601524b)  
📧 Email: [shrikrishna0703@gmail.com](mailto:shrikrishna0703@gmail.com)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> 💡 “Empower your applications with smart insights. Let Career Aligner align your career path with AI.”