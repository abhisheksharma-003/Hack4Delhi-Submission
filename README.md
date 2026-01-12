# **Public Spend Watch (PRAGATI-AI)**

> **Proactive Audit Intelligence for Government Public Spending**

Public Spend Watch (codenamed **PRAGATI-AI**) is an AI-powered transparency and audit intelligence platform designed to **monitor, analyze, and flag anomalies in public expenditure** using historical trends and real-time data sources.

Unlike traditional dashboards that only report past data, PRAGATI-AI **predicts risk**, highlights suspicious spending behavior, and enables auditors and citizens to interact with public finance data intelligently.

---

## 🚀 Key Features

* **Real-time Monitoring** of public spending signals via news & audit feeds
* **16 Years of Historical Analysis** (2010–2026) for trend-based risk detection
* **AI-Driven Risk Scoring Engine** (rule-based, auditor-inspired logic)
* **Admin & Citizen Dashboards** with role-based access
* **AI Terminal Chat Interface** for natural language queries
* **Multi-Language Support** (English & Hindi)
* **CSV / Excel Export** for audits and reports

---

## 🧠 PRAGATI-AI Risk Engine

The platform uses a **multi-parameter risk scoring logic** that simulates how a senior government auditor reasons:

* 📈 **Historical Deviation** – Flags unusually high payments vs 5-year averages
* ⚡ **Transaction Velocity** – Detects burst payments to the same vendor
* 🏢 **Vendor Concentration** – Identifies monopolistic procurement patterns
* 👥 **Beneficiary Density Mismatch** – Compares funds vs demographic needs
* 📰 **Source Reliability Weighting** – CAG > Ministry > Media

Each alert includes a **risk score + explanation**, ensuring **decision support, not blind automation**.

---

## 🛠 Tech Stack

### Frontend

* **React 19 (Vite)**
* **Tailwind CSS + Vanilla CSS**
* **React Router DOM**
* **FontAwesome Icons**

### Data & Logic

* **Axios** – API & RSS fetching
* **xml2js, cheerio** – Scraping & parsing government feeds
* **React Context API** – Auth, Data & Language state
* **Custom Risk Logic Engine**

### Deployment

* **Vercel**

---

## 🏗 How It Works (Architecture)

1. **Data Ingestion**

   * Scrapes Google News, CAG reports & ministry feeds via RSS
2. **Categorization Engine**

   * Auto-tags department, state, scheme & anomaly type
3. **Risk Analysis**

   * Applies PRAGATI-AI scoring rules across historical + live data
4. **Visualization**

   * Admin dashboards, citizen transparency views & AI terminal
5. **Interaction**

   * Users can query data using natural language commands

---

## 🖥 AI Terminal Examples

```
> Show me high-risk vendors in PWD
> Explain Case ID 3045
> Upcoming audits this quarter
```

---

## 🎯 Problem Statement

> *“Billions of rupees are disbursed every year across thousands of schemes.
> Manual monitoring for low-level leakage and procurement anomalies is impossible at scale.”*

---

## 💡 Our Solution

PRAGATI-AI transforms **reactive auditing into proactive oversight** by:

* Detecting anomalies **before** they become scandals
* Prioritizing audits based on **risk probability**
* Enabling **human + AI collaboration** in public finance governance

---

## 📊 MVP Status

✅ **90% MVP Completed**

| Feature                       | Status     |
| ----------------------------- | ---------- |
| Real-time Monitoring          | ✅ Complete |
| Risk Scoring Engine           | ✅ Complete |
| Admin Dashboard               | ✅ Complete |
| Citizen Transparency View     | ✅ Complete |
| Multi-Language Support        | ✅ Complete |
| AI Chat Terminal              | ✅ Complete |
| Historical Analysis (2010–26) | ✅ Complete |
| Government API Integration    | ⏳ Partial  |

---

## 🛣 Future Roadmap

* **Machine Learning Models** (Random Forest / XGBoost)
* **LLM-based Audit Summaries** (Gemini / OpenAI)
* **Blockchain Audit Trails** (Hyperledger)
* **Automated GRC Workflows**
* **Citizen Whistleblower Portal**
* **Mobile App for Field Auditors**

---

## 🏆 Why This Matters

PRAGATI-AI is not just a dashboard.
It is **Audit Intelligence Infrastructure** for modern governance.




