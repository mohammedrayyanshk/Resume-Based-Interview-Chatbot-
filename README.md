# Resume-Based-Interview-Chatbot-
An AI-powered HR Interview Chatbot that analyzes your resume (PDF), generates tailored interview questions, and gives instant feedback using sentiment analysis.
AI HR Interview Chatbot with Resume-Based Q&A

This project is an interactive AI-based HR Interview Chatbot built using **Gradio** and **Transformers**. It allows you to upload your resume in PDF format, automatically generates 5 personalized interview questions using **FLAN-T5**, and gives real-time feedback on your answers using **Sentiment Analysis**.

---

##  Features

-  Upload Resume (PDF)
-  Auto-generates 5 interview questions based on your resume
-  Submit answers and get feedback using sentiment analysis
-  Final score with encouragement tips
-  Chat-style interface using Gradio

---

##  Libraries Used

- [transformers](https://huggingface.co/transformers/)
- [gradio](https://gradio.app/)
- [pdfplumber](https://github.com/jsvine/pdfplumber)
- [sentencepiece](https://github.com/google/sentencepiece)
- torch (for model execution)

Install all required packages:

```bash
pip install transformers gradio pdfplumber sentencepiece
