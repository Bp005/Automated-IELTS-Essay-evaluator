# 📘 Automated IELTS Essay Evaluator

This project is an **Automated IELTS Essay Evaluation System** developed as a **Major Project for the Bachelor of Computer Engineering** degree at **Kantipur Engineering College (Tribhuvan University)**.

The system uses **fine-tuned Large Language Models (LLMs)** to automatically evaluate **IELTS Writing Task 2 essays** based on official IELTS evaluation criteria and provide detailed feedback.


---

## 🎓 Project Information

- **Project Type:** Academic Major Project  
- **Degree:** Bachelor in Computer Engineering  
- **Institution:** Kantipur Engineering College  
- **Year:** 2025  

### 👨‍💻 Team Members
- Agrim Khatry  
- **Bijay Poudel**  
- Bijay Kingring  
- Manish Karki  

### 👨‍🏫 Supervisor
- Dr. Manoj Shakya  
- Assistant Professor, Kathmandu University  

---

## 🧠 Problem Statement

IELTS Writing evaluation is:
- Time-consuming  
- Expensive  
- Dependent on limited human evaluators  

Many students lack **instant and structured feedback** for improving their writing skills. This project aims to solve that problem using **AI-based automated essay evaluation**.

---

## 🎯 Objectives

- Automatically evaluate IELTS essays based on:
  - Task Achievement  
  - Coherence & Cohesion  
  - Lexical Resource  
  - Grammatical Range & Accuracy  
- Generate band scores and feedback instantly  
- Reduce dependency on manual evaluation  
- Help students improve writing skills using AI feedback  

---

## 🛠️ Technologies Used

### 🔹 AI / Machine Learning
- Mistral-7B (Fine-tuned)
- Decoder-Only Transformer Model
- LoRA & QLoRA (Parameter-Efficient Fine-Tuning)
- Hugging Face Datasets
- PyTorch

### 🔹 Backend
- FastAPI
- WebSockets (for real-time feedback)
- ngrok (for local testing)

### 🔹 Frontend
- Next.js

---

## 🧪 Models Implemented

### 1️⃣ Fine-Tuned Mistral-7B
- High accuracy and detailed feedback
- ~89.2% agreement with human examiners
- Higher computational cost

### 2️⃣ Decoder-Only Model
- Faster inference
- Lower resource usage
- Used for real-time feedback

---

## 📊 Dataset

- **Source:** Hugging Face  
- **Dataset:** `chillies/IELTS-writing-task-2-evaluation`  
- **Training Samples:** ~9,800  
- **Testing Samples:** ~400  

---

## ⚙️ System Workflow

1. User submits an IELTS essay
2. Essay is sent to the FastAPI backend
3. Fine-tuned model evaluates the essay
4. Band scores and feedback are generated
5. Results are displayed on the frontend

---

## 🖥️ System Requirements

### Development Requirements
- Python 3.9+
- GPU with CUDA support (recommended)
- Minimum 16GB RAM
- Hugging Face account


git clone <your-repository-url>
cd automated-ielts-essay-evaluator
