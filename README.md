# 🎙️ Smart Podcast Generation from Academic Research Papers

A Generative AI-powered application that converts academic research papers into engaging podcast-style content. The system analyzes research papers, identifies research gaps, simplifies technical concepts, and generates conversational podcast scripts along with supporting resources such as show notes, timestamps, key terms, and downloadable documents.

---

## 📖 Overview

Academic research papers are often lengthy and difficult for non-specialists to understand. This project leverages Large Language Models (LLMs) and Natural Language Processing (NLP) techniques to transform complex research papers into easy-to-understand podcast-style content.

The application improves accessibility to scientific research by enabling users to consume research through engaging audio-based content.

---

## 🚀 Features

- 📄 Upload Research Papers in PDF format
- 🔍 Extract text from PDF documents
- 🧠 Analyze research papers using Llama 3.3 70B
- 📊 Identify research gaps
- 📚 Simplify technical content using a Scientific Lay Summarisation dataset
- 🎙️ Generate podcast-style conversational scripts
- 📝 Generate show notes
- 🏷️ Extract important key terms
- ⏱️ Automatically generate timestamps
- 📄 Export podcast content as DOCX
- 🔊 Generate audio using Google Text-to-Speech (gTTS)
- 🎧 Support for multiple podcast presentation styles

---

## 🎯 Problem Statement

The rapid growth of scientific publications has made it increasingly difficult for researchers, students, and the general public to consume and understand academic literature.

Research papers are often:
- Highly technical
- Time-consuming to read
- Difficult for non-domain experts

This project addresses these challenges by automatically converting research papers into podcast-style content, making scientific knowledge more accessible and engaging.

---

## ⚙️ System Workflow

```text
Research Paper (PDF)
        │
        ▼
PDF Text Extraction
        │
        ▼
Research Paper Analysis
        │
        ▼
Research Gap Detection
        │
        ▼
Scientific Lay Summarisation
        │
        ▼
Podcast Script Generation
        │
        ▼
Show Notes + Key Terms + Timestamps
        │
        ▼
DOCX Export
        │
        ▼
Audio Generation
```

---

## 📂 Dataset Used

### Scientific Lay Summarisation Dataset

**Source**

https://huggingface.co/datasets/pszemraj/scientific_lay_summarisation-plos-norm

### Dataset Highlights

- 24,000+ scientific research articles
- Human-written layman summaries
- Designed for scientific content simplification

### Purpose

The dataset provides examples of transforming complex scientific language into simpler explanations. These examples guide the AI model in generating podcast content that is easier for a wider audience to understand.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core Programming Language |
| Streamlit | User Interface |
| PyPDF | PDF Text Extraction |
| Llama 3.3 70B | Research Analysis & Podcast Generation |
| Groq API | Model Inference |
| Hugging Face Datasets | Scientific Dataset Integration |
| python-docx | DOCX Export |
| gTTS | Audio Generation |

---

## 🤖 AI Model

### Llama 3.3 70B

**Provider:** Meta AI

**Accessed via:** Groq API

### Used For

- Research paper analysis
- Research gap detection
- Scientific content simplification
- Podcast script generation
- Show notes generation
- Timestamp generation
- Key term extraction

---

## 📁 Project Structure

```text
Podcast-Generator/
│
├── app.py
├── requirements.txt
├── README.md
├── generated_docs/
├── generated_audio/
├── sample_papers/
├── dataset/
└── images/
```

---

## 💻 Installation

### Clone the Repository

```bash
git clone https://github.com/01fe23bcs182/Podcast-Generator.git
cd Podcast-Generator
```

---

### Create a Virtual Environment

```bash
python -m venv venv
```

---

### Activate the Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root and add your Groq API key:

```env
GROQ_API_KEY=your_groq_api_key
```

> **Note:** Never upload your `.env` file or API keys to GitHub.

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will start locally at:

```
http://localhost:8501
```

---

## 🌟 Future Enhancements

- Multi-language podcast generation
- Voice customization
- MP3 download support
- Advanced dataset retrieval
- Cloud deployment
- User authentication
- Interactive podcast player

---

## 🎯 Expected Impact

This project aims to:

- Improve accessibility to scientific research
- Simplify complex academic literature
- Promote science communication
- Enable audio-based research consumption
- Support students, researchers, educators, and professionals

---

## 👨‍💻 Project Information

**Project Title**

Smart Podcast Generation from Academic Research Papers

**Domain**

- Generative AI
- Natural Language Processing (NLP)
- Large Language Models (LLMs)
- Science Communication

---

## 📌 Notes

This project was developed for academic learning and hackathon purposes.

API keys have been excluded from the repository for security reasons.

---

## 📄 License

This project is intended for educational and research purposes.
