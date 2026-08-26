# 🚀 Named Entity Recognition with spaCy

A practical **Natural Language Processing (NLP)** project using a pre-trained **spaCy NER model** to identify and classify named entities from text.

---

## 📌 About the Project

In this project, the NER model reads text, identifies important entities, and classifies them into different categories such as:

- 👤 **PERSON** — Person names
- 🏢 **ORG** — Organizations
- 🌍 **GPE** — Countries, cities, and states
- 📦 **PRODUCT** — Products
- 📍 **LOC** — Locations
- 📅 **DATE** — Dates
- 🔢 **ORDINAL** — First, second, etc.
- 💰 **MONEY** — Monetary values

The project also applies NER to a real news article after extracting and cleaning its text.

> **Note:** This project uses the pre-trained `en_core_web_sm` model from spaCy. The model was not fine-tuned in this project.

---

## 🛠️ Technologies Used

- Python
- spaCy
- Natural Language Processing (NLP)
- BeautifulSoup
- Requests
- Regular Expressions (Regex)
- spaCy Displacy

---

## 🔄 Project Workflow

```text
Input Text
    ↓
Pre-trained spaCy NER Model
    ↓
Entity Detection
    ↓
Entity Classification
    ↓
Entity Visualization
