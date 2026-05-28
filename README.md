# Named Entity Recognition (NER) Integration

An automated text analysis system that identifies key entities in unstructured text and generates contextual explanations — eliminating manual input and reducing human interaction using Python and Google's Gemini API.

---

## 📸 Demo

<!-- Add your screenshots here. In GitHub, you can drag and drop images directly into the README editor -->

![NER System Screenshot](screenshots/demo.png)

> *Screenshot of the interactive Plotly GUI displaying extracted entities and contextual explanations*

---

## 🔍 Overview

Traditional text analysis requires significant manual effort to identify and interpret named entities such as people, organizations, locations, and dates. This project automates that process end-to-end — taking raw text as input and outputting structured entity data with AI-generated explanations through an interactive GUI.

---

## ✨ Features

- **Automated entity extraction** — identifies people, organizations, locations, dates, and more from any text input
- **AI-generated explanations** — leverages Google Gemini to provide contextual explanations for each extracted entity
- **Interactive GUI** — built with Plotly for a clean, usable interface
- **Secure authentication** — uses Google service account credentials for safe API access
- **Optimized pipeline** — tested across diverse text formats for reliable, consistent output

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Google Gemini API | NLP entity extraction & explanation |
| Plotly | Interactive GUI |
| Google Colab | Development environment |
| Google Cloud Service Account | Secure API authentication |

---

## ⚙️ How It Works

1. **Input** — User provides raw text through the Plotly GUI
2. **Authentication** — System authenticates securely with Google Cloud using service account credentials
3. **Entity Extraction** — Python NLP functions send the text to the Gemini API, which identifies and returns named entities
4. **Explanation Generation** — Gemini generates a contextual explanation for each entity
5. **Output** — Results are displayed interactively in the GUI, organized by entity type

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Google Cloud account with Gemini API access
- A Google service account credentials JSON file

### Installation

1. Clone the repository:
```bash
git clone https://github.com/zhangp124/ner-integration.git
cd ner-integration
```

2. Install dependencies:
```bash
pip install google-generativeai plotly pandas
```

3. Add your Google service account credentials:
```bash
# Place your credentials JSON file in the root directory
# Rename it to: service_account.json
```

4. Run the notebook in Google Colab or locally:
```bash
jupyter notebook ner_integration.ipynb
```

---

## 📊 Results

- Successfully automated entity extraction across multiple text formats including news articles, academic papers, and social media posts
- Reduced manual text analysis time significantly compared to traditional approaches
- Achieved consistent entity recognition across diverse input formats through iterative testing

---

## 📁 Project Structure

```
ner-integration/
├── ner_integration.ipynb   # Main notebook
├── requirements.txt        # Python dependencies
├── screenshots/            # Demo screenshots
│   └── demo.png
└── README.md
```

---

## 🔮 Future Improvements

- Add support for multiple languages
- Expand entity categories (e.g. financial terms, medical terminology)
- Build a web-based version accessible without Google Colab
- Add export functionality to save results as CSV or JSON

---

## 👤 Author

**Peter Zhang**
- 📧 [pz1249@gmail.com](mailto:pz1249@gmail.com)
- 💼 [LinkedIn](https://www.linkedin.com/in/peter-zhang-4a684023b)
- 🐙 [GitHub](https://github.com/zhangp124)

---

*Built as part of coursework and independent study at Baruch College, Zicklin School of Business*
