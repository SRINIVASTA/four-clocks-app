# ⏰ tasks-four-clocks-app

An AI-ready, dynamic task-routing dashboard built with **Streamlit** and **Pandas**. 

**Created by: Srinivasta**

This application automates the **Four Clocks** time-management framework. It takes unstructured walls of text or uploaded business files, cleans the text data, filters out duplicates, and dynamically routes your tasks into four separate operational time horizons.

Live URL: *(https://four-clocks-app-3ph9vffdvkfwwgsnhfcyyv.streamlit.app/)*

---

## 🧭 The Four Clocks Framework
When you work solo, you inherit all the planning timelines of a traditional company with no instruction manual. This app organizes your workload instantly:

*   **Now Clock ⏱️**: Immediate operational sprints, client deliverables, and urgent technical fixes due this week.
*   **Compound Clock 📈**: High-leverage recurring habits that build long-term business value (marketing, newsletters, content).
*   **Deep Clock 🧠**: High-focus strategic growth, academic research, skill training, and asset building.
*   **Wild Clock ⚡**: Spontaneous late-night creative ideas, administrative chores, or loose notes that need to be captured.

---

## 🛠️ Tech Stack & Architecture
*   **Architect & Developer**: Srinivasta
*   **Frontend UI**: Streamlit (Responsive 4-column metrics layout)
*   **Data Pipeline Engine**: Pandas (DataFrame backend storage with data validation filters)
*   **File Ingestion Parsers**: `python-docx` (Word), `openpyxl` (Excel), and built-in Python string decoders
*   **Downstream Compilers**: `reportlab` (Dynamic PDF generator engine)

---

## 🚀 Key Features

### 1. Unified Multi-Channel Ingestion Pipeline
*   **Sandbox Workspace**: Paste giant paragraphs of raw, mashed-up text notes. The regex engine splits strings automatically by periods and line breaks.
*   **File Drag-and-Drop Dropzone**: Upload raw `.txt`, `.csv`, `.xlsx`, or `.docx` files to parse individual task entries instantly.

### 2. Hardened Data Validation Layer
*   **Automatic Keyword Token Router**: Matches enterprise consulting, machine learning, software engineering, and accounting phrases to place items in the correct clock bucket automatically.
*   **Zero-Overload Duplicate Filter**: Suppresses matching data inputs (ignoring upper/lowercase differences) to prevent duplicate entries in your active weekly sprint list.

### 3. Comprehensive Output Compiler
*   Download your finished weekly schedule back onto your machine in **Text (.txt)**, **PDF (.pdf)**, **Word (.docx)**, **Excel (.xlsx)**, or **CSV (.csv)** formats with one click.

---

## 📦 Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd tasks-four-clocks-app
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the application server:**
   ```bash
   streamlit run app.py
   ```

---

## 📊 Sample Ingestion Block for Testing
Copy and paste this entire block into the app text area to test the dynamic multi-line sorting pipeline:

```text
Configure a Redis cache layer to speed up the client portfolio dashboard. Draft a mutual non-disclosure agreement for a sovereign wealth fund client. Fix a broken Docker build layer in the continuous integration pipeline. Write a script to scrape pricing data from competing financial consulting web pages. Read a research paper on using graph neural networks for credit fraud detection. Cancel unused SaaS subscriptions to reduce monthly operational overhead. Re-anchor vector embeddings inside our core semantic search database. Create a slide deck explaining data governance for the upcoming stakeholder meeting. Outline a newsletter issue explaining how interest rates affect tech valuations. Troubleshoot a sudden drop in API throughput on the staging gateway. Sort through junk emails and unsubscribe from noisy marketing lists. Complete the yearly anti-money laundering compliance training module. Migrate legacy user profile data from MongoDB into a relational PostgreSQL table. Book flight tickets and hotel accommodations for the upcoming London tech conference. Sketch a concept for an AI-powered personal financial advisor chatbot. Perform a penetration test on the internal file-sharing servers. Review the data processing addendum for a European corporate client. Write a Python automation script to generate weekly PDF client invoices. Plan a team-building dinner event for the local engineering crew. Optimize memory allocation for our real-time Kafka data streaming pipeline. Record a podcast episode discussing the future of algorithmic trading. Gather expense receipts to submit to the corporate accounting portal. Set up local environment monitoring variables for a new developer laptop. Draft a patent application for a unique statistical anomaly detection method. Update the open-source software contribution policy on the company GitHub page. Benchmark the response times of a newly deployed FastAPI endpoint. Back up cold storage hard drives to a secure physical safe. Automate a script to pull top-trending data science keywords from Reddit daily. Order custom branded notebooks and pens for marketing giveaways. Audit a pull request containing updates to the portfolio margin calculation engine.
```
