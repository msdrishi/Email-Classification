# 🚀 Project : Email Routing and Classification using GenAI

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction

This project aims to automate the routing and classification of customer emails in the commercial banking sector using GenAI. 
By leveraging the power of a Retrieval-Augmented Generation (RAG) framework integrated with a Large Language Model (LLM), 
we can provide relevant information as input and receive accurate, context-aware results in response. 
the system efficiently extracts email content, identifies request types and sub-types, detects duplicates, and assigns priorities.
The solution reduces manual intervention, minimizes response time, and enhances accuracy, leading to a streamlined email management process.

## 🎥 Demo
🔗 [Live Demo](https://drive.google.com/file/d/1uZjvo7_Ocdlt9sNDrSBdeHbxw9-tfJi2/view)
📹 [Video Demo](https://drive.google.com/file/d/1uZjvo7_Ocdlt9sNDrSBdeHbxw9-tfJi2/view) 

## 🖼️ Screenshots:

![Screenshot2](https://github.com/ewfx/gaied-dragons/blob/main/code/src/data/outputs/screenshot2.png)
![Screenshot3](https://github.com/ewfx/gaied-dragons/blob/main/code/src/data/outputs/screenshot1.png)

## 💡 Inspiration
Processing high volumes of customer emails manually is time-consuming and prone to errors. This solution uses GenAI to streamline email management by classifying requests, detecting duplicates, and extracting key information.

## ⚙️ What It Does
Email Extraction: Extracts email content from .eml files and attachments (.pdf, .docx, .doc, .jpg).

Classification: Uses GenAI to classify emails into predefined request types and sub-types.

Duplicate Detection: Leverages FAISS for vector similarity search to identify duplicate emails.

## 🛠️ How We Built It
GenAI Model: Integrated with Groqcloud using LLaMA 3.3 70B for accurate classification.

Duplicate Detection: Implemented using FAISS (Facebook AI Similarity Search).

Data Extraction: Used PyPDF2, python-docx, win32com, and Tesseract OCR for processing attachments.

Embedding Generation: Utilized HuggingFace models for generating text embeddings.

Document Management: Managed request types and sub-types using DOCX documents.

Vector Storage: Stored embeddings in a FAISS vector database.

Backend: Developed using Python with Flask.

Additional Libraries: Included Sentence Transformers, NumPy, and Scikit-Learn.

## 🚧 Challenges We Faced
Integrating the RAG framework with the LLM to accurately classify specific request types and sub-types was one of the most challenging aspects. 
Additionally, processing and cleaning the extracted text from .eml files posed significant difficulties. 
We worked extensively to minimize token usage while retaining essential information. Our efforts have paid off, resulting in an efficient and accurate solution.

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/your-repo.git
   ```
2. Install dependencies  
   ```sh
   pip install -r requirements.txt (for Python)
   ```
3. Run the project  
   ```sh
   python app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: HTML, CSS, JavaScript
- 🔹 Backend: Python (Flask / FastAPI)
- 🔹 Database: FAISS for vector storage
- 🔹 LLM: Groqcloud (LLaMA 3.3 70B)
- 🔹 Data Extraction: PyPDF2, python-docx, Tesseract OCR
- 🔹 Embedding Generation: HuggingFace Models

## 👥 Team
- **Rishi Prasad** - [GitHub](https://github.com/msdrishi) | [LinkedIn](https://www.linkedin.com/in/rishi-prasad-6526a7213/)
- **Dhakshayani** - [GitHub](https://github.com/gsvdhakshayani) | [LinkedIn](https://www.linkedin.com/in/dhakshayani-garapati/)
- **Abhinisha** - [GitHub](https://github.com/abhinishakumari) | [LinkedIn](https://www.linkedin.com/in/abhinishakumari/)
- **Anurag** - [GitHub](https://github.com/binuboi79) | [LinkedIn](https://in.linkedin.com/in/anurag-baral-2261a7191)
