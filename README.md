# 📄 TutorAI - Exam Question Digitizer

**TutorAI** is a fully local, AI-powered tool that automatically detects, crops, and converts exam questions from PDFs or images into editable **Word** and **PowerPoint** formats.

## 🎥 Demo

https://github.com/user-attachments/assets/d76f823b-c5e5-4e76-a314-b1f3b2ffe6ab

*(Watch the AI in action)*

## ✨ Key Features
- 🔒 **100% Privacy:** No internet required, runs entirely on your machine.
- 🧠 **AI-Powered:** Uses a custom **YOLOv8** model (`best.pt`) for precise detection.
- 🛠️ **Interactive Editor:** Manually adjust, swap, or delete questions via a visual canvas.
- 📂 **Multi-Format Export:** Supports **.docx**, **.pptx**, **.pdf**, and **.zip**.

## 🤖 Model Performance

The local **YOLOv8** model has been trained on a custom dataset to ensure high accuracy in detecting question blocks.

| Metric | Value | Description |
| :--- | :--- | :--- |
| **mAP@50** | **87.4%** | Overall detection accuracy |
| **Precision** | **90.2%** | Accuracy of positive detections |
| **Recall** | **84.4%** | Ability to find all questions |
| **Speed** | **~30ms** | Inference time per page (GPU) |

## 🚀 Quick Start

**1. Clone the repository:**
```bash
git clone [https://github.com/iqbalmirzayev/tutor-ai-exam.git](https://github.com/iqbalmirzayev/tutor-ai-exam.git)
cd tutor-ai-exam
```
**2. Install dependencies:**
```bash
pip install -r requirements.txt
```
**3. Run the app.**
```bash
streamlit run app.py
```
