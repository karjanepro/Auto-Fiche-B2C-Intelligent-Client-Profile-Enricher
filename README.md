# 🤖 Auto Fiche B2C – Intelligent Client Profile Enricher

**Auto Fiche B2C** is an autonomous agent that enriches B2C client profiles by sourcing and synthesizing data from the web. It generates comprehensive, CRM-ready client fiches containing:

- Company logo  
- Website URL  
- Business description (generated via AI)  
- Social media links  
- Contact information (email, phone)  
- Sector classification and metadata  

Built with **Python**, **NLP**, and modern **web scraping + enrichment APIs**, this project automates client intelligence collection and content generation for sales and marketing personalization.

---

## 📌 Project Summary

- 🌐 Scrapes public data using **Selenium**
- 🧠 Generates business descriptions with **ChatGPT (via API)**
- 🛠️ Validates emails and phone numbers using Python logic
- 🧾 Generates tailored prompts via **prompt engineering**
- 🔁 Orchestrated with **Apache Airflow** for full automation

The output is a rich, structured "fiche client" that can be directly injected into CRM or marketing systems.

---

## 🧰 Tech Stack

| Component        | Technology            |
|------------------|------------------------|
| Data Collection  | **Selenium (Web Scraping)** |
| Text Generation  | **OpenAI API (ChatGPT)**     |
| Validation       | **Email & Phone Regex / APIs** |
| Workflow         | **Apache Airflow**     |
| Prompt Design    | **Prompt Engineering** |
| Language & Tools | **Python**, **requests**, **openai** |


---

## 🧠 Intelligent Components

### ✨ Prompt Engineering

Crafted dynamic prompts for ChatGPT to:

- Generate short business summaries
- Guess sectors based on scraped data
- Personalize tone/style if needed

### 🧪 Data Validation

- Email: Format & domain validation via regex
- Phone: International normalization & verification

### 📬 Automation with Airflow

- Scheduled runs for batch processing
- Retry logic on failure
- Email notification on completion

---

## 🌍 Use Cases

- Automated lead enrichment for B2C sales pipelines
- Intelligent profile generation for marketing personalization
- Input enrichment for B2C CRM platforms
- Email and phone validation prior to outbound campaigns

---

## 🧠 What I Learned

This project strengthened my expertise in:

- ✔️ Selenium-based scraping & dynamic content parsing
- ✔️ AI prompt design & fine-tuned description generation
- ✔️ Workflow orchestration with Airflow
- ✔️ Data integrity validation at scale
- ✔️ Multi-step ETL design with real-world business data
