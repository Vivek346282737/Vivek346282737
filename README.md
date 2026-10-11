# Vivek Prasad

**Software Engineer** | B.Tech Computer Science and Engineering, Lovely Professional University (2026) | Jamshedpur, India

I build software in Python, JavaScript and Java, and I test what I build. My main work is an AI assistant that writes and tests its own new features. Around that I have built backend APIs, a test automation framework, a computer vision pipeline and a set of data analytics projects with live dashboards.

Open to entry-level roles and internships in **software development, AI / LLM engineering, test automation (QA) and data analytics**. I can join immediately and relocate anywhere in India.

[LinkedIn](https://www.linkedin.com/in/prasadvivek123) | [Tableau Public](https://public.tableau.com/app/profile/vivek.prasad5963) | 1itdvivekprasad11@gmail.com

## Featured project

### [JARVIS](https://github.com/Vivek346282737/jarvis-ai-assistant) - an AI voice assistant that writes its own new features, safely

When it is asked for something it cannot do, it generates the capability with an LLM, verifies the code with a Python AST allow-list, tests it in a sandboxed process and only then registers it, with bounded retries and automatic rollback.

- One command pipeline behind four front ends: microphone, Telegram bot, web dashboard and terminal
- Three LLM back ends with automatic fallback (Gemini, Groq, local Ollama)
- Flask REST API for the dashboard with PBKDF2 password hashing and session cookies
- 280 unit tests, a 201-check end-to-end self-test and a 35-check Selenium browser suite

`Python` `LLM agents` `Flask` `SQLite` `Telegram Bot API` `Selenium`

## Projects by area

### AI, LLM and machine learning

| Project | What it does | Tools |
|---|---|---|
| [JARVIS](https://github.com/Vivek346282737/jarvis-ai-assistant) | Self-extending AI voice assistant with sandboxed code generation | Python, Gemini, Groq, Ollama |
| [Friday AI](https://github.com/Vivek346282737/FRIDAY--AI-) | LLM agent that plans multi-step tasks and calls tools through FastAPI and MCP | Python, FastAPI, MCP |
| [EdgeSight-CV](https://github.com/Vivek346282737/-EdgeSight-CV) | Real-time computer vision pipeline: YOLO detection, ByteTrack tracking, zone rules; about 10% lower latency with ONNX Runtime | Python, PyTorch, OpenCV, ONNX |
| [HR Attrition Prediction](https://github.com/Vivek346282737/hr-attrition-analytics) | Logistic regression written from scratch in NumPy, ROC AUC 0.82 on a hold-out set | Python, NumPy, SQL |
| [Guard](https://github.com/Vivek346282737/guard_project) | Password risk classifier served from a Flask web app | Python, scikit-learn, Flask |

### Backend and full-stack

| Project | What it does | Tools |
|---|---|---|
| [JARVIS dashboard API](https://github.com/Vivek346282737/jarvis-ai-assistant) | 12-endpoint Flask REST API with secure login and SQLite persistence | Python, Flask, SQLite |
| [Trendora](https://github.com/Vivek346282737/Trendora-E-Commerce-MERN-Website) | E-commerce web application on the MERN stack | MongoDB, Express, React, Node.js |

### Test automation (QA)

| Project | What it does | Tools |
|---|---|---|
| [ShopGuard](https://github.com/Vivek346282737/ShopGuard-Automation-Framework) | 3-tier test framework: 19 scenarios across web UI, REST API and database, run on every push | Java, Selenium, REST Assured, TestNG, GitHub Actions |
| [JARVIS test suites](https://github.com/Vivek346282737/jarvis-ai-assistant) | 280 unit tests, end-to-end self-test and a headless-Chrome browser suite | Python, unittest, Selenium |

### Data analytics and BI

| Project | What it shows | Tools | Links |
|---|---|---|---|
| E-Commerce Sales & Customer Analytics | 99K orders across 9 tables: revenue drivers, RFM segments, cohort retention, and the effect of late delivery on reviews | SQL, PostgreSQL, Python, Excel, Tableau | [Code](https://github.com/Vivek346282737/olist-ecommerce-analytics) / [Dashboard](https://public.tableau.com/app/profile/vivek.prasad5963/viz/OlistE-CommerceSalesDeliveryDashboard/OlistE-CommerceSalesDeliveryDashboard) |
| HR Attrition Analysis | Why 16% of 1,470 employees leave, validated with chi-square tests | SQL, Python, Excel, Tableau | [Code](https://github.com/Vivek346282737/hr-attrition-analytics) / [Dashboard](https://public.tableau.com/app/profile/vivek.prasad5963/viz/HRAttritionAnalysisDashboard_17910993091870/HRAttritionAnalysisDashboard) |
| Marketing A/B Test Analysis | 588K-user experiment: 43% relative lift in conversion, with z-test, confidence intervals and power analysis | Python, SQL | [Code](https://github.com/Vivek346282737/marketing-ab-test-analysis) / [Dashboard](https://vivek346282737.github.io/marketing-ab-test-analysis/) |
| Power BI Sales & Delivery Report | Star-schema model, Power Query transformations and 14 DAX measures | Power BI, DAX | [Code](https://github.com/Vivek346282737/powerbi-sales-analytics) |
| Enterprise Data Quality Pipeline | 15-step logged pipeline over 250K+ rows (synthetic data) with 108 quality rules and a star schema in PostgreSQL | Python, PostgreSQL | [Code](https://github.com/Vivek346282737/enterprise-data-analytics) |

## Skills

- **Languages:** Python, JavaScript, TypeScript, Java, SQL
- **AI and LLM:** LLM agents, prompt engineering, tool calling, model fallback, Gemini, Groq, Ollama, MCP
- **Backend:** FastAPI, Flask, Node.js, Express, REST APIs, JWT authentication
- **Testing:** Selenium WebDriver, TestNG, REST Assured, unittest, PyTest, Postman, GitHub Actions
- **Data:** PostgreSQL, MySQL, MongoDB, Pandas, NumPy, Tableau, Power BI, Excel
- **Machine learning:** scikit-learn, PyTorch, YOLO, OpenCV, ONNX Runtime

## How I work

I use AI coding tools every day, and I own the result: I write the spec, review the changes and test on the real device before I call something done. Each project README says what was measured and what was not.
