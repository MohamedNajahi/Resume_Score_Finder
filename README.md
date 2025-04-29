# 🚀 AI-Powered ATS Resume Score Finder

An intelligent resume analysis tool that helps job seekers improve their resumes by comparing them with job descriptions. It uses AI and NLP to give a match score based on how well the resume fits the job.

---

## 🎯 What It Does

- Compares a resume (PDF) with a job description
- Uses semantic similarity to find how well the resume matches
- Shows a match score (%) to help users improve their resumes for ATS (Applicant Tracking Systems)

---

## 🔧 Tech Stack & Features

- ✅ **Flask** – Web framework to handle the user interface and uploads
- ✅ **PyMuPDF (fitz)** – Extracts text from PDF resumes 📄
- ✅ **SentenceTransformers** – Converts text into embeddings using `all-MiniLM-L6-v2` 🧠
- ✅ **Scikit-learn** – Calculates similarity using cosine similarity 📊
- ✅ **Werkzeug** – Handles secure file uploads 🔒
- ✅ **NumPy & OS** – For data processing and file handling ⚙

---

## 💡 How It Works

1. 📂 Upload your resume (PDF)
2. 📝 Enter the job description
3. 📊 Click "Check Score"
4. ✅ See how well your resume matches the job with a percentage score

---

## 🖥️ Installation

```bash
# Clone the repository
git clone https://github.com/MohamedNajahi/CVSnakeGameProject.git
cd CVSnakeGameProject

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
