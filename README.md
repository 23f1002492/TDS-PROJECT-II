# Data Analyst Agent — Your AI-Powered Data Companion  
> Smarter, faster, and more intuitive analysis of your datasets using **Generative AI + Python magic.**  
> ⚠️ WARNING: Use at Your Own Risk.
> This project is a work in progress. Things might break, behave unexpectedly, or not work at all.

---

## 📌 What Is This?
Meet **Data Analyst Agent 2.0** — an AI-driven assistant that eliminates tedious data crunching.  
Upload your dataset + queries, and instantly get:  
✅ Visual reports  
✅ AI-generated insights  
✅ Automated workflows  

Perfect for:  
- Analysts 🧾  
- Researchers 🔬  
- Startups & Businesses 📈  
- Anyone who loves turning raw data into knowledge  

---

## ✨ Key Highlights  

| Feature                  | Why It’s Awesome 🚀 |
|---------------------------|----------------------|
| 🤖 AI-Powered Insights    | Uses Google’s Generative AI to “understand” your data |
| 📊 Rich Visualizations    | Generates plots with **Seaborn & Matplotlib** |
| 🌍 Web Scraper Mode       | Fetch live data directly from URLs |
| 📂 Multi-Format Friendly  | Accepts CSV, Excel, JSON, Parquet, or TXT |
| 🔄 Ask Many at Once       | Batch processing for multiple questions |
| 🖥️ Simple-to-Use Interface | Beginner friendly, no steep learning curve |
| ⚡ Super-Fast Execution   | Optimized for speed + real-time feedback |

---

## 🚀 Getting Started  
### 1. Clone the Repository
```bash
  git clone https://github.com/23f1002492/TDS-PROJECT-II.git
```

### 2. Change working folder
```bash
  cd TDS-PROJECT-II
```

### 3. Install Dependencies (ensure you have python installed)
```bash
  pip install -r requirements.txt
```

### 4. Configure API Keys  
Create a `.env` file inside the root folder:
```bash
GEMINI_API_KEY=your_google_api_key
LLM_TIMEOUT_SECONDS=240
```

### 5. Start the Application
```bash
python -m uvicorn app:app --reload
```
Now open [**http://localhost:8000/**](http://localhost:8000/) in your browser 🌐  


## 🧑‍💻 How It Works  

1. **Write Your Questions**  
   Create a `.txt` file with queries like:  What’s the revenue growth month-over-month?, Find correlation between Age and Income, Show most profitable products...etc

2. **Upload Dataset + Questions File**  
- Dataset (optional) → CSV, Excel, JSON, Parquet, or TXT  
- Questions file (required) → Plain text  

3. **Voilà!**  
- AI processes the queries  
- Generates insights + summaries  
- Builds neat visualizations  

---

## 🛠 Tech Behind the Scenes  

### Backend  
- FastAPI ⚡ → High-performance web server  
- LangChain 🧠 → Orchestrates LLM interactions  
- Google Generative AI ✨ → Core AI engine  
- Pandas + NumPy 📊 → Data wrangling made smooth  
- Seaborn + Matplotlib 🎨 → Clean, insightful charts  

### Frontend  
- HTML5 + CSS + JavaScript  
- Bootstrap-inspired modern UI  

---

## 🔧 API Blueprint  

| Method | Endpoint  | Purpose |
|--------|-----------|----------|
| `GET`  | `/`       | Access web app |
| `POST` | `/api`    | Submit dataset + questions |
| `GET`  | `/summary`| App diagnostics & summaries |

---

## 📂 File Support  

| Format | Extensions |
|--------|------------|
| CSV    | `.csv`     |
| Excel  | `.xlsx`, `.xls` |
| JSON   | `.json`    |
| Parquet| `.parquet` |
| Text   | `.txt`     |

---

## 🎯 Where Can You Use This?  

- 📈 Business Strategy – Sales, KPIs, forecasts  
- 🔬 Research – Data exploration, hypothesis validation  
- 🤖 Data Science – Quick EDA, anomaly detection  
- 📊 Reporting – Automated dashboards  

---

## 🔒 Security First  
- ✅ No cloud storage → All data stays local  
- ✅ API keys kept safe via `.env`  
- ✅ Configurable CORS policy for production use  

---

## 📜 License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---