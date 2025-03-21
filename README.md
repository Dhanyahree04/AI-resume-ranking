# 📄 AI-Powered Resume Screening & Ranking System  

 Overview  
This project is an AI-powered system for automated resume screening and ranking. It uses **Natural Language Processing (NLP)** techniques to compare resumes with job descriptions and ranks candidates based on **TF-IDF** and **cosine similarity**.  

 Features  
 Extracts text from resumes (PDF/DOCX)  
 Preprocesses text using NLP (lemmatization, stopword removal)  
 Converts text into numerical representation using TF-IDF  
 Computes similarity scores with job descriptions  
 Ranks candidates based on AI-driven analysis   
 Provides a user-friendly **Streamlit UI**  

 Technologies Used  
- **Python**  
- **Streamlit** (for Web UI)  
- **spaCy** (for NLP)  
- **scikit-learn** (for machine learning)  
- **PyPDF2** & **python-docx** (for text extraction)  
- **GitHub & Ngrok** (for deployment)  

Project Structure  

 Installation & Setup  
1️ **Clone the repository**  
```bash
git clone https://github.com/YOUR_USERNAME/AI-Resume-Ranking.git
cd AI-Resume-Ranking

2 pip install -r requirements.txt
3 streamlit run app.py
4 http://localhost:8501/

**Working**
Upload resumes (PDF/DOCX)
Enter a job description
Click "Rank Candidates"
View ranked candidates based on AI analysis
📌 Example Output
Candidate Name	Similarity Score
John Doe	      0.85
Jane Smith	    0.78
Alice Brown	    0.72


