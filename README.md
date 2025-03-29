# Nandini_4260_A2

#  Assignment 2 – Reddit Text Analysis on AI

##  Student Info:
- **Name:** Nandini Goyal  
- **Student ID:** 300377653  
- **Course:** CSIS 4260-002  
- **Assignment:** 2 – Web Scraping & Text Analysis

---

##  Project Topic:
**How is Artificial Intelligence perceived in the future?**  
This project collects and analyzes Reddit posts discussing AI, its potential to take over the world, and public sentiment on AGI and related technologies.

---

##  Files Included

| File                   | Description                                  |
|------------------------|----------------------------------------------|
| `Assignment2.ipynb`    | Notebook with scraping + LLM text analysis   |
| `text_analysis.csv`    | Final output with summary, score, tone       |
| `requirements.txt`     | Python dependencies for the project          |
| `README.md`            | This file with instructions                  |

---

##  Analysis Summary

Reddit posts were collected using Reddit's JSON API. Each post was then processed by a local LLM (Mistral via Ollama), which extracted:
- A 2–3 sentence **summary**
- An **impact score** (-10 to +10)
- A **tone** (Hopeful or Fearful)

The analysis results were saved in `text_analysis.csv`.

---

## ▶ How to Run

### 1. Setup Environment (Optional)
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

### 2. Install & Start Ollama
Download Ollama: https://ollama.com  
```bash
ollama pull mistral
ollama serve
```

### 3. Run Notebook
Open `Assignment2.ipynb` and execute all cells to reproduce the results.

---

##  Submission Notes
Only the following files are submitted:
- `Assignment2.ipynb`
- `text_analysis.csv`
- `requirements.txt`

All content is self-contained in these files.

---

