# 📚 Gemini Research Agent

## 🔍 Overview

This is an AI-powered research assistant built with **Google Gemini 2.5 Flash**, designed to help users generate research  on various topics and break down a research topic into subtopics and generate concise summaries. The application offers an interactive **Streamlit** UI, allowing users to approve or revise AI-generated content and download the summarised report.

---

## 📘 Scenario

Imagine a student, educator, or researcher who needs to quickly understand a complex topic. Instead of manually browsing multiple sources, this app allows the user to:

* Generate research article on any topic
* Decompose a topic into logical subtopics,
* Generate summaries for each one,
* Review and edit content before accepting


The tool streamlines the entire process, enabling fast and accurate content generation with human feedback in the loop.

---

## 🧩 Problem Statement

Build an intelligent research assistant that:

* Accepts a broad topic from the user,
* Uses Gemini to generate 3–5 key subtopics,
* Summarizes each subtopic in \~100 words,
* Allows human-in-the-loop editing of summaries,
* Exports a structured research report,
* Runs seamlessly in a Streamlit interface.

---

## 🛠️ Features

* 🧠 Gemini-powered content generation
* 📑 Automatic topic decomposition
* ✍️ Editable summaries with approval workflow
* ⏭️ Step-by-step subtopic navigation
* 📥 Download final report in any file format
* 🖥️ Intuitive Streamlit interface

---

## 🧠 Tech Stack

* **Google Gemini API** – Language generation
* **Streamlit** – Interactive frontend UI
* **dotenv** – Secure environment config management
* **Python** – Core application logic

---

## 📦 Project Structure

```
├── streamlit_app.py               # Streamlit frontend and app logic  
├── model_config.json    # model configuration
├── .env                 # API key configuration  
├── requirements.txt     # Python dependencies  
└── README.md            # Project documentation  
```

---

## ⚙️ Setup Instructions
### 1. Create and Activate Virtual Environment

```bash
python -m venv venv  
source venv/bin/activate        # On Windows: venv\Scripts\activate  
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt  
```

### 3. Add API Keys

Create a `.env` file in the project root:

```
GOOGLE_API_KEY=your_google_api_key
```

### 4. Run the Application

```bash
streamlit run app.py  
```

---

---

## 📈 Example Output

### Topic: *Impact of AI on Healthcare*

#### Subtopic: Applications of AI in Medical Diagnosis

AI has revolutionized diagnostics by enabling faster and more accurate detection of diseases like cancer, cardiovascular conditions, and neurological disorders. Machine learning algorithms can analyze vast amounts of patient data and medical imagery, often identifying patterns undetectable by the human eye. This leads to early intervention, personalized treatment, and reduced healthcare costs.

...

---

