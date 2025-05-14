
# 📊 AI-Powered Data Analytics Chatbot

This project is an **AI-integrated chatbot** built to help students and data enthusiasts perform data analytics, machine learning, and visualization tasks through natural language prompts. It combines Python’s data science stack with Google’s **Gemini 1.5 Flash LLM** (or OpenAI) and is deployed via **Streamlit** for interactivity.

---

## 🚀 Overview

The chatbot enables users to:
- Upload datasets
- Perform **Exploratory Data Analysis (EDA)**
- Generate **statistical summaries**
- Create **interactive and static visualizations**
- Build and evaluate **machine learning models**
- Use **natural language** to interact with data

It leverages:
- Python
- Pandas, NumPy, Matplotlib, Seaborn, Plotly
- Scikit-learn, SciPy, Statistics
- Streamlit for the frontend
- Gemini or OpenAI for LLM-based queries

---

## 🧠 Objectives

- Enable **interactive learning** via natural language.
- Automate **EDA**, model training, and statistical tasks.
- Provide **instant visualizations** and insights.
- Integrate **LLMs (Gemini/OpenAI)** to handle complex user queries.

---

## 🧰 Tools & Technologies

### 🔧 Backend
- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Statistics
- Plotly
- Matplotlib
- Seaborn
- Regex

### 🎨 Frontend
- Streamlit

### 🤖 LLM Integration
- Google Gemini 1.5 Flash (via `google-generativeai`)
- OpenAI GPT (optional fallback)

---

## 🗂️ Project Structure

```
data-analytics-chatbot/
├── .streamlit/
│   └── secrets.toml
├── assets/
├── static_plots/
├── venv/
├── app.py
├── chatbot_logic.py
├── gemini_handler.py
├── utils.py
├── requirements.txt
├── README.md
└── Project_Report.docx
```

---

## 🔑 Key Features

- **Data Upload**: Supports CSV input with instant preview and analysis.
- **EDA**: Automated descriptive statistics, histograms, boxplots, scatterplots, etc.
- **ML Support**: Train/test supervised & unsupervised models with evaluation reports.
- **Visualizations**: Built-in support for Plotly and Matplotlib/Seaborn (rendered via PIL+Base64).
- **Natural Language Queries**: Powered by Gemini/OpenAI for insights and guidance.
- **Regex Query Parsing**: Understands structured natural language prompts.

---

## 🔮 Future Enhancements

- Support for Excel, JSON, and other file formats.
- Memory and prompt persistence via SQLite or JSON.
- Role-based user authentication.
- Voice command integration.
- Report generation (PDF/Excel export).
- More advanced ML/DL model support (Random Forest, SVM, etc.).
- Query autosuggestions and error feedback using LangChain.

---

## 📸 Screenshots & Demo

> _Add screenshots of your Streamlit app here_  
> _Or upload a short demo video / link to a deployed app_

---

## 📝 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/data-analytics-chatbot.git
   cd data-analytics-chatbot
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate it:

   - Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Add your Gemini or OpenAI API key to `.streamlit/secrets.toml`:
   ```toml
   [Gemini]
   api_key = "your_gemini_api_key"

   [OpenAI]
   api_key = "your_openai_api_key"  # optional
   ```

6. Run the app:
   ```bash
   streamlit run app.py
   ```

---

## 📚 References

- [Python Documentation](https://docs.python.org/3/)
- [Pandas Docs](https://pandas.pydata.org/docs/)
- [Streamlit Docs](https://docs.streamlit.io/)
- [Google Generative AI](https://ai.google.dev/)
- [Plotly Docs](https://plotly.com/python/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [Seaborn Docs](https://seaborn.pydata.org/)
- [OpenAI API](https://platform.openai.com/docs)

---

## 📄 License

> Add a license here if needed (e.g., MIT, Apache 2.0)

---

## ✍️ Author

- [Your Name Here](https://github.com/your-username)

---
