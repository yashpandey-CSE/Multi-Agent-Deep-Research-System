# 🤖 Multi-Agent AI Deep Research System

A powerful **Multi-Agent AI Research System** inspired by modern tools like **ChatGPT Deep Research** and **Perplexity AI**. This project automates the entire research workflow using multiple intelligent agents that collaborate to search, extract, analyze, and generate high-quality reports from real-time web data.

The system is built using **Mistral AI (LLM)**, **Tavily API for web search**, **BeautifulSoup for web scraping**, and **Streamlit for an interactive UI**.

---

# 🚀 Features

* 🧠 Multi-Agent Architecture (Search, Reader, Writer, Critic)
* 🌐 Real-time web search using Tavily API
* 📄 Web scraping using BeautifulSoup
* 🤖 Mistral AI-powered reasoning and report generation
* 📝 Automated research report creation
* 🔍 Deep content extraction from websites
* 🧑‍⚖️ Critic agent for report evaluation
* 🎨 Interactive **Streamlit UI**
* ⚙️ Fully automated end-to-end research pipeline
* 📊 Structured and explainable workflow

---

# 🧠 System Architecture

### Agents Workflow:

* **Search Agent** → Finds relevant and recent sources using Tavily
* **Reader Agent** → Scrapes top URLs for detailed content
* **Writer Agent** → Generates structured research report using Mistral AI
* **Critic Agent** → Reviews and improves report quality

---

# ⚙️ Workflow Pipeline

```text id="pipeline_flow_ui"
User Input (Streamlit UI)
        ↓
Search Agent (Tavily API)
        ↓
Web Results
        ↓
Reader Agent (BeautifulSoup Scraping)
        ↓
Extracted Content
        ↓
Writer Agent (Mistral AI)
        ↓
Generated Research Report
        ↓
Critic Agent (Feedback & Evaluation)
        ↓
Final Improved Report (Displayed in UI)
```

---

# 🖥️ Streamlit UI Features

* Simple input box for research topic
* “Run Research” button
* Real-time pipeline execution logs
* Search results display
* Scraped content viewer
* Final AI-generated report
* Critic feedback section

---

# 📂 Project Structure

```text id="structure_ui"
Multi-Agent-System/
│
├── agents.py          # AI agents (Search, Reader, Writer, Critic)
├── app.py             # Streamlit UI
├── pipeline.py        # Core research pipeline
├── tools.py           # Tavily search + web scraping tools
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone the Repository

```bash id="clone_ui"
git clone https://github.com/<your-username>/Multi-Agent-Deep-Research-System.git
cd Multi-Agent-Deep-Research-System
```

---

## 2️⃣ Create Virtual Environment

```bash id="venv_ui"
python -m venv .venv
```

Activate:

### Windows

```bash id="win_ui"
.venv\Scripts\activate
```

### Linux / Mac

```bash id="linux_ui"
source .venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash id="install_ui"
pip install -r requirements.txt
```

---

## 4️⃣ Add API Keys

Create a `.env` file:

```env id="env_ui"
MISTRAL_API_KEY=your_mistral_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

# ▶️ Run the Application

### Run Streamlit UI

```bash id="run_ui"
streamlit run app.py
```

Then open:

```
http://localhost:8501
```

---

# 📊 Example Output

* Search results from Tavily
* Scraped web content
* AI-generated structured report
* Critic feedback and improvements

---

# 🧠 Tech Stack

* Python
* Mistral AI (LLM)
* Tavily API (Search Engine)
* BeautifulSoup (Web Scraping)
* Streamlit (Frontend UI)
* Multi-Agent System Design
* Prompt Engineering

---

# 🎯 Use Cases

* Automated research assistant
* Academic paper analysis
* Market research reports
* News summarization
* Competitive intelligence
* AI knowledge extraction system

---

# 🔮 Future Improvements

* Multi-source parallel scraping
* Citation-based report generation
* Download report as PDF
* Conversation memory
* Agent debate system
* Faster async agent execution
* Cloud deployment (Streamlit Cloud / Render)

---

# 👨‍💻 Author

**Yash Pandey**

If you like this project, don’t forget to ⭐ the repository!
