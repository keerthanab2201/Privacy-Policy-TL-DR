# 🔐 Privacy Policy TL;DR & Risk Analyzer

An NLP-based application that summarizes lengthy Privacy Policies and Terms of Service documents, highlights key data collection practices, and identifies potential privacy risks in a clear and user-friendly manner.

---

## 📌 Project Overview

Privacy policies and Terms of Service documents are often long, complex, and difficult for users to understand. This project aims to improve transparency by automatically generating concise summaries and detecting common privacy risks using transformer-based Natural Language Processing (NLP) techniques.

The system is designed to be lightweight and efficient, making it suitable for CPU-only environments while still providing meaningful insights into data usage and privacy implications.

---

## 🎯 Objectives

- Generate a concise TL;DR summary of long privacy policies
- Highlight how user data is collected, used, shared, and stored
- Identify common privacy risks such as:
  - Third-party data sharing
  - Targeted advertising
  - Location tracking
  - Behavioral tracking
  - Long-term or indefinite data retention
- Assign an overall privacy risk level (Low / Medium / High)
- Present results in a structured, explainable, and human-readable format

---

## 🧠 NLP Techniques Used

- **Abstractive Summarization** using transformer-based models
- **Keyword-guided Risk Detection** for privacy-related indicators
- **Rule-based Post-processing** for structured and readable summaries
- **Explainable AI Design** through sentence-level and risk-level outputs

---

## 🛠️ Technology Stack

- **Language:** Python
- **Libraries:** Hugging Face Transformers, PyTorch
- **Models Used:**
  - `t5-small` – lightweight abstractive summarization
  - `distilbert-base-uncased` – efficient text understanding
- **Interface:** Jupyter Notebook with `ipywidgets`
- **Hardware:** CPU-only (no GPU required)

---

## 🧩 System Workflow

1. User inputs a privacy policy or Terms of Service text
2. The text is summarized into an executive-style TL;DR
3. The system scans the text for privacy-related risk indicators
4. Detected risks are categorized and displayed
5. An overall privacy risk level is computed and presented

---


## ⚖️ Ethical Considerations

- The system does not make legal judgments or determine compliance.
- Risk detection is indicative and intended to improve user awareness.
- Summaries should not be considered a replacement for legal advice.

---

## 🚀 How to Run the Project

1. Clone the repository
  ```bash
   git clone https://github.com/keerthanab2201/Privacy-Policy-TL-DR/
   ```
2. Open the Jupyter Notebook
3. Install dependencies 
  ```bash
  pip install transformers torch ipywidgets
  ```
4. Run the notebook cells sequentially
5. Paste a privacy policy and click Analyze
