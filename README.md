# DataSense_AI_Agent

✨ Turn Any CSV Into Insights, Anomalies & Reports — Automatically
DataSense AI is a full multi-agent intelligence pipeline designed to autonomously ingest, analyze, detect anomalies, visualize, and generate PDF reports from any dataset — with zero manual analysis required.

Built for the Google X × Kaggle Agentic AI Capstone, this project demonstrates:

🔥 Autonomous agent collaboration
🔥 Tool execution (Pandas, Matplotlib)
🔥 Memory-enabled analytics
🔥 Observability & logging
🔥 User-friendly automation

🎨 Highlights
🔍 Autonomous Data Understanding
    - Schema inference
    - Missing values, summary stats
    - Correlation mapping
    - Visual exploratory analysis (EDA)
 ⚠️ Smart Anomaly Detection
    - Outliers
    - Duplicates
    - Time-series spikes
    - Distribution shifts using Memory Bank
 📊 Beautiful Automatic Visualizations
    - Histograms
    - Bar charts
    - Correlation heatmaps
    - Time-based charts
 📄 Auto-Generated PDF Report
    - Insights summary
    - Charts
    - Anomaly breakdown
    - Data quality metrics

🧠 Memory & Context Awareness
    - Stores dataset fingerprints
    - Compares with past data
    - Detects shifts over time

 🧩 Animated Architecture Diagram

                             ┌────────────────────────────────────┐
                            │         📥 Ingest Agent             │
                            │  - Reads CSV                        │
                            │  - Infers schema                    │
                            │  - Validates quality                │
                            └───────────────┬────────────────────┘
                                            │
                       (Dataset → DF)       │
                                            ▼
        ┌─────────────────────────────────────────────────────────────────┐
        │                         🔁 Agent Pipeline                       │
        │                                                                 │
        │     ┌──────────────────┐     ┌──────────────────┐                │
        │     │  📊 Analysis     │     │  🚨 Anomaly       │                │
        │     │     Agent        │◀────│     Agent         │                │
        │     │ - EDA            │     │ - Outliers        │                │
        │     │ - Correlations   │────▶│ - Time spikes     │                │
        │     │ - Visuals        │     │ - Duplicates      │                │
        │     └──────────┬───────┘     └──────────┬───────┘                │
        │                 │                        │                        │
        └─────────────────┼────────────────────────┼────────────────────────┘
                          │                        │
                          ▼                        ▼
                ┌──────────────────┐       ┌──────────────────┐
                │   🧠 Memory       │       │   📄 Reporter     │
                │     Bank          │       │     Agent         │
                │ - Summaries       │       │ - Generate PDF    │
                │ - Trends          │       │ - Compile charts  │
                └──────────────────┘       └──────────────────┘

🛠️ Installation Guide
1️⃣ Clone the Repository

  git clone https://github.com/mdey26/DataSense_AI_Agent.git
  cd DataSense_AI_Agent

2️⃣ Install Dependencies

  pip install -r requirements.txt

▶️ How to Run

Option A — Google Colab (Recommended)
Open the notebook:
📄 DataSense_AI_Agent_Main.ipynb

Run the cells → Upload your CSV → Get:
  - Insights
  - Charts
  - Anomalies
  - PDF Report
Everything is automated.

Option B — Run Locally via Python Script

 python datasense_ai_agent_main.py

Option C — Notebook (Local Jupyter)

 jupyter notebook
 DataSense_AI_Agent_Main.ipynb

📊 Using Your Own Dataset

Supports any CSV file:
 1. Run the One-Click Demo cell
 2. Upload your CSV
 3. Wait while the agents execute:
    - Ingest
    - Analysis
    - Anomaly detection
    - Reporting
 4Download your PDF Report

Perfect for:
✔ Business analysts
✔ Students
✔ Data cleaning workflows
✔ Internal audits
✔ ML preprocessing


💡 Designed For the Agentic AI Capstone

This project demonstrates:
  - Multi-agent orchestration
  - Code execution tools
  - Memory bank
  - Observability
  - Evaluation (human + automated)
  - Clean architecture & modularity
  - Professional documentation

 🤝 Contributing

Pull requests are welcome!
Feel free to submit enhancements such as:
 - New anomaly models
 - New visualization types
 - UI improvements (Streamlit/Gradio)
   
