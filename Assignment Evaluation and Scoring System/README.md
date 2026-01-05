<div align='center'>
  <img style="width:30%" src='https://github.com/user-attachments/assets/ef8d7bd6-72b1-4d7b-8f74-b6f2860e1a49'/>
</div>

<div align='center'> 
  <h1> Assignment Evaluation and Scoring System</h1> 
</div>


 
---

## 🚀 Overview

In academic environments like **Innomatics**, faculty receive multiple **ZIP files** daily containing student assignment PDFs.  
Manual evaluation is **time-consuming, repetitive, and inconsistent**.

This project automates the **entire assignment evaluation pipeline** — from ZIP upload to **LLM-based scoring and feedback generation**, with **zero manual intervention**.

---

## 🎯 Objective

To build an **end-to-end AI-powered evaluation system** that can:

- 📦 Handle ZIP-based assignment submissions  
- 📄 Extract and clean PDF content  
- 🧠 Evaluate answers using LLMs  
- 📊 Generate structured scores & feedback automatically  

---

## ✨ Features

### 🔍 1. ZIP File Handling

- Accepts ZIP files uploaded by faculty/students  
- Automatically extracts all PDFs  
- Supports **nested folder structures**

---

### 📄 2. PDF → Text Conversion

- Converts PDFs into clean, readable text  
- Removes:
  - Headers & footers  
  - Watermarks & noise  
- Works for **typed & handwritten** submissions  

---

### 🧩 3. Intelligent Q&A Extraction

- Automatically separates:
  - ❓ Question  
  - ✍️ Student Answer  
- Handles inconsistent formatting across PDFs  

---

### 🤖 4. LLM-Based Answer Evaluation

Each Question–Answer pair is evaluated by an **LLM**, which returns:

| Output | Description |
|-----|------------|
| 📊 Score | Marks (0–10) |
| 📝 Feedback | Detailed explanation |
| ❌ Errors | Mistakes & gaps |
| 💡 Suggestions | Improvement tips |

---

### 📈 5. Automated Score Aggregation

- Combines question-wise marks  
- Calculates **total score**  
- Outputs clean **JSON-based structured results**

---

## 🛠️ Tech Stack

| Tool / Technology | Usage |
|-----------------|------|
| **Python** | Core processing logic |
| **PyPDF2 / PDFPlumber** | PDF text extraction |
| **Regex** | Question & answer segmentation |
| **LLMs (Gemini / OpenAI / Claude)** | Answer evaluation |
| **LangChain** | LLM orchestration |
| **JSON** | Structured scoring output |
| **FastAPI / Flask (Optional)** | API deployment |

---

## 📸 Screenshot

<img width="1472" height="585" alt="Workflow" src="https://github.com/user-attachments/assets/efe72bcc-9567-4f98-ba49-452eb4037a1d" />


---

## 🚀 Impact of the Project

This system:

- ⏱️ Saves **hours of manual evaluation time**
- ✅ Ensures **consistent & unbiased grading**
- 🤖 Demonstrates real-world **LLM automation**
- 📊 Produces structured, auditable results
- 🔁 Scales easily for large batches of assignments

---

## 📌 Conclusion

This project showcases how **AI + automation** can fully replace repetitive academic evaluation workflows.  
It highlights practical use of **LLMs, document processing, and structured scoring**, making it highly relevant for **AI, Automation, and Data roles**.

---

⭐ *If you found this project useful, feel free to star the repository!*  

👤 **Author:** Ashish Mishra  
AI / ML | Automation | LLM Systems 🚀
