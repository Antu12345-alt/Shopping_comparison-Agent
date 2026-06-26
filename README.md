# 🛍️ AI Shopping Comparison Agent

## 📌 Overview

AI Shopping Comparison Agent is an Agentic AI workflow built using **n8n** that helps users compare products from multiple online sources and recommends the best option based on price, rating, and value for money.

This project is being developed as part of a **Design Credit Course** while exploring the concepts of **Agentic AI**, workflow automation, APIs, and Large Language Models (LLMs).

---

## 🚀 Features

* Compare products from multiple product APIs
* Collect product details such as:

  * Product Name
  * Price
  * Rating
  * Product Source
* Merge and process data from multiple APIs
* AI-powered product recommendation using Google Gemini
* Automated workflow built with n8n
* Modular design for adding more shopping platforms in the future

---

## 🛠️ Tech Stack

* **n8n** – Workflow Automation
* **Google Gemini** – Large Language Model
* **FakeStore API** – Demo Product API
* **DummyJSON API** – Product API
* JavaScript (Code Nodes)
* REST APIs
* Docker (for running n8n locally)

---

## ⚙️ Workflow

```text
Manual Trigger
      │
      ▼
Fetch Products (FakeStore API)
      │
      ▼
Fetch Products (DummyJSON API)
      │
      ▼
Merge Product Data
      │
      ▼
Compare Products
      │
      ▼
AI Agent
      │
      ▼
Gemini Chat Model
      │
      ▼
Recommendation Output
```

---

## 📈 Future Improvements

* Amazon integration
* Flipkart integration
* Meesho integration
* eBay integration
* Real-time product search
* Price history tracking
* Delivery time comparison
* Automatic coupon detection
* One-click checkout
* Personalized recommendations
* Multi-agent architecture

---

## 🎯 Learning Outcomes

Through this project I am learning:

* Agentic AI
* Workflow Automation
* API Integration
* Prompt Engineering
* Large Language Models (LLMs)
* JavaScript inside n8n
* AI-assisted decision making
* Git & GitHub

---

## 📂 Repository Structure

```
AI-Shopping-Comparison-Agent/
│
├── shopping-comparison-agent.json
├── README.md
└── assets/
    └── workflow-screenshot.png
```

---

## 👨‍💻 Author

**Antu Khad**

B.Tech Mechanical Engineering
Interested in Agentic AI, Automation, Machine Learning, and Software Development.

---

## ⭐ Project Status

🚧 Currently under active development.

This project will continue to evolve by integrating real e-commerce platforms and advanced AI capabilities.

