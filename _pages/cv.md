---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Alban Manishimwe
======
*Natural language processing and language models for official statistics and African languages.*

* Email: [alban.manishimwe@gmail.com](mailto:alban.manishimwe@gmail.com)
* Mobile: +256 788 500 504
* LinkedIn: [alban-manishimwe](https://www.linkedin.com/in/alban-manishimwe-827623248/)
* Location: Kampala, Uganda
* Nationality: Ugandan

Professional summary
======
Data scientist at the Uganda Bureau of Statistics, working on natural language processing for official statistics. I build language-model systems for statistical classification and retrieval-augmented access to official data, and I study how small language models represent African-language names. I have presented at the UNECE Group of Experts on Consumer Price Indices and the IAOS–ISI Conference, and I release open evaluations of retrieval, faithfulness, and model editing.

Education
======
* **MSc, Embedded and Mobile Systems (major in Mobile Systems)**, The Nelson Mandela African Institution of Science and Technology, Arusha, Tanzania, June 2019 – December 2021
  * Thesis: “The Mobile Application based on Machine Learning for East Africa Stock Exchange”
  * Courses: Machine Learning, Internet of Things, Mobile Commerce, Advanced Telecommunication Systems, Programming
* **Bachelor of Science in Computer Engineering (major in Software Engineering)**, Mbarara University of Science and Technology, Mbarara, Uganda, August 2011 – May 2015

Publications and presentations
======
* Web-scraped data for the Consumer Price Index in Uganda. UNECE Group of Experts on Consumer Price Indices, Geneva, 2025.
* Application of AI to address teacher–pupil ratios in Uganda. IAOS–ISI Conference, Mexico City, May 2024.
* Integrated Mobile Application Based on Machine Learning for East Africa Stock Market. *Journal of Information Systems Engineering and Management*, 2021. DOI: [10.21601/jisem/11008](https://doi.org/10.21601/jisem/11008)

Selected speaking
======
* Panellist, Data Science for Good, Data Science Africa, Nyeri, Kenya, 2024
* Speaker, Statistical Challenges in the Era of Big Data, Uganda Statistical Society Symposium, Kampala, 2024
* Panellist, Public–Private Partnership, IUCEA STI Conference, Kampala, 2019
* Facilitator, Role of Data in Internet Governance, Arusha Women School of Internet Governance, 2018

Research
======
* **[Where personal names sit in the residual stream](https://github.com/amanishimwe/names-bechmark).** Where Gisu, Kinyarwanda, Luganda, Lusoga, Runyankore, and Swahili given names sit in the residual stream of small language models, against Latin-script controls.
* **[AfriNLP](https://github.com/amanishimwe/AfriNLP).** Translation of GSM8K from English into Swahili and Kinyarwanda with Helsinki-NLP OPUS models.
* **[Retrieval comparison](https://github.com/amanishimwe/rag-research-1).** Haystack comparison of BM25, BM25 with RM3, DPR, Contriever, and a BM25–DPR hybrid on Natural Questions and HotpotQA.
* **[Emergent unfaithfulness](https://github.com/amanishimwe/emergent-unfaithfulness).** Implementation of the Emergent Unfaithfulness evaluation (Zahraei et al., COLM 2026): paired documents, a FaithGap score, and the same test across instructions and post-training stages.
* **[Haystack RAG](https://github.com/amanishimwe/hay-stack).** Retrieval-augmented generation with in-memory documents, BM25 retrieval, and Claude answers grounded in the retrieved text.
* **[Deterministic judge vs LLM judge](https://github.com/amanishimwe/deterministic-vs-llm-judge).** Haystack pipelines that gate a generator with a local policy check or with an LLM judge, on the same prompts.
* **[SFT vs RL interpretability](https://github.com/amanishimwe/intepretability).** Comparison of an SFT-only 1.5B model with RL-trained DeepScaleR-1.5B on reasoning and interpretability.
* **[SELF-EDIT](https://github.com/amanishimwe/model-editing).** Model-editing harness for causal language models. A norm oracle must undo a planted edit, against live, oracle, random, blind, and no-edit conditions on Qwen2.5-0.5B-Instruct.
* **[Web agents](https://github.com/amanishimwe/web-agents).** Playwright web agents and a sandbox for testing whether browsing agents leak sensitive data on attacker-controlled sites.

NLP and applied research
======
* **Automated statistical classification.** LLM coding of ISCO and ISIC, reaching 95% accuracy on 2 million records at the Uganda Bureau of Statistics.
* **UBOS statistical chatbot.** Retrieval-augmented generation and MCP chatbot for public access to official statistics, at about 20,000 queries a month.
* **East Africa stock exchange app.** MSc thesis: a mobile application based on machine learning for the East Africa stock exchange. [Journal paper](https://doi.org/10.21601/jisem/11008).
* **Web-scraped consumer prices.** Apache Spark pipeline that brings web-scraped prices into Uganda's CPI, with the World Bank's Centre for Development Data. Presented at the UNECE Group of Experts on Consumer Price Indices, Geneva, 2025.
* **[matezaML](https://github.com/amanishimwe/autoML).** Machine-learning toolkit for small, noisy, and imbalanced datasets on ordinary laptops, with preprocessing, training, and AutoML.

Experience and consultancies
======

Uganda Bureau of Statistics — Uganda
------
**Data Scientist** | January 2023 – Present
* Developed LLM-based automated coding of ISCO and ISIC classifications, reaching 95% accuracy on 2 million records.
* Designed and deployed the UBOS statistical chatbot using retrieval-augmented generation (RAG) and MCP, giving the public access to official statistics; 20,000 queries per month.
* Introduced web-scraped price data into CPI compilation using Apache Spark, in collaboration with the World Bank's Centre for Development Data, covering fast-evolving products (10% of the basket) and reducing manual price collection for these items by 90%.
* Trained 102 staff from the national statistical system (NSS) in responsible design and use of AI tools.
* Led a US$80,000 AI project funded by UNDP-Uganda and the UNDP Seoul Policy Center, managing budget, timelines and reporting to the donor.
* Supervised a team of 12 staff on data science projects and provided technical oversight.
* Processed and validated data for the 2024 National Population and Housing Census and Consumer Price Indices, including editing, imputation and quality checks.
* Built the Flood Guard Platform with the Global Partnership for Sustainable Data, for statistics and data on flooding in Uganda.

**Data Editor** | January 2017 – December 2022
* Edited, validated and imputed CPI and survey data for official releases.
* Automated data quality checks using R and Python.

DEJ Technology GmbH — Rostock, Germany
------
**Consultant (Part-time)** | April 2025 – June 2025
* Fine-tuned AI models with PyTorch for health-sector clients and monitored production performance.

Deutsche Gesellschaft für Internationale Zusammenarbeit (GIZ) GmbH — Uganda
------
**Consultant, AI Tools (Part-time)** | August 2025 – October 2025
* Conducted a baseline assessment of AI capacity among 20 partner organisations in Central and Southern Uganda.
* Trained 35 staff from partner organisations in responsible design and use of AI tools.
* Supported partners to design and implement AI solutions for good governance.

Kampala Analytica — Uganda
------
**AI and Data Advisor (Part-time)** | January 2023 – March 2025
* Convened the Kampala Tech Talk series (4 events, 150 participants) and led a GIZ-funded AI hackathon.

United Nations Foundation — Washington, D.C., United States of America
------
**Evaluation Consultant (Part-time) for the National Statistics Office, Colombia** | May 2025 – September 2025
* Led the technical, strategic, and financial evaluation of the citizen-generated data collection tool for Statistics Colombia, including a cost-benefit analysis used to scale the platform.

Athari Recruitment — New York, United States of America
------
**Consultant, Technical Lead (Part-time)** | January 2023 – December 2024
* Led a team of 5 developers and data scientists building an AI-based recruitment system (Python, PyTorch, Apache Spark).

The Fortune 500 Klub Limited — Uganda
------
**Lead Software Developer (Part-time)** | January 2021 – January 2022
* Moved the Fortune Mobile Application from a native app to a hybrid React Native and PHP service, with a microservice architecture.

The Inter-University Council for East Africa — Uganda
------
**Internship** | September 2020 – May 2021
* Designed and built the Academic Programmes Information Management System in Django and MySQL, and drafted the architecture for the Higher Education Information Management System and the requirements for the IUCEA Mobile App.
* Reviewed the African Centers of Excellence II monitoring platform and the CENIT@EA Skills Match platform.

Teaching
======
* Trained 102 staff from Uganda's national statistical system in the responsible design and use of AI tools.
* Trained 35 staff from GIZ partner organisations in Central and Southern Uganda, and supported them to design AI solutions for good governance.
* Convened the Kampala Tech Talk series (4 events, 150 participants) and led a GIZ-funded AI hackathon.
* Facilitator, Role of Data in Internet Governance, Arusha Women School of Internet Governance, 2018.

Skills
======
* **Natural language processing:** LLMs, fine-tuning (PyTorch, Unsloth), retrieval-augmented generation, statistical classification (ISCO, ISIC, COICOP), and NLP for African languages.
* **Machine learning:** scikit-learn, TensorFlow, model editing, and evaluation of faithfulness and interpretability.
* **Official statistics:** CPI and price index methodology, census and survey data processing, data editing and imputation.
* **Data engineering:** Apache Spark, Databricks, SQL, web scraping.
* **Analysis and visualisation:** Python, R, Power BI, Tableau, GIS (ArcGIS, QGIS).
* **Academic practice:** conference presentations, training design and delivery, donor-funded project management.

Training and certification
======
* Applied AI and Data Science Program, MIT Professional Education
* Technical AI Safety, AI Safety Collab, European Network for AI Safety, 2025
* IBM: Data Science, Data Engineering, Machine Learning, Artificial Intelligence
* Modernisation of Consumer Price Index (2023), Rome, Italy

Professional membership
======
* Association for Computing Machinery (ACM)
* Data Science Africa
* Uganda Statistical Society
* Internet Society
* ICT Association of Uganda

Languages
======
* English (Fluent)
* Kinyarwanda (Fluent)
* Swahili (Basic)
* French (Basic)

Country experience
======
Uganda, Rwanda, Tanzania, Colombia, Germany, USA

References
======
* **Duncan Ssematimba**, Head of Department, Uganda Bureau of Statistics, P.O. Box 7186, Kampala, Uganda. Email: [duncan.ssematimba@ubos.org](mailto:duncan.ssematimba@ubos.org)
* **Federico Polidoro**, Project Manager, Centre for Development Data at the World Bank. Email: [fpolidoro@worldbank.org](mailto:fpolidoro@worldbank.org)
* **Kisangiri Michael (PhD)**, Associate Professor, The Nelson Mandela African Institution of Science and Technology, P.O. Box 447, Arusha, Tanzania. Email: [kisangiri.michael@nm-aist.ac.tz](mailto:kisangiri.michael@nm-aist.ac.tz)
