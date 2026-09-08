👋 Hi, I'm Yahya Houimdi
AI Research · Applied Machine Learning · Intelligent Systems

<p align="center"> <a href="https://github.com/yahyahouimdi"> <img src="https://img.shields.io/badge/GitHub-Yahya%20Houimdi-181717?style=for-the-badge&logo=github" /> </a> <a href="https://www.linkedin.com/in/yahya-houimdi-163492338/"> <img src="https://img.shields.io/badge/LinkedIn-Yahya%20Houimdi-0A66C2?style=for-the-badge&logo=linkedin" /> </a> <a href="mailto:yahya.houimdi@etudiant-enit.utm.tn"> <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail" /> </a> </p>
---

## 🧭 About Me

I'm a **final-year Computer Engineering student at the National Engineering School of Tunis (ENIT)**, pursuing a double-degree Master's in **Information System Techniques (IST)** in collaboration with **University of Tunis El Manar and TU Braunschweig**.

My work focuses on building **intelligent systems from research to deployment**.

I am particularly interested in the intersection of:

> 🧠 **AI Research**
> → 🔬 **Experimentation & Model Development**
> → ⚙️ **AI Engineering**
> → 🚀 **Real-World Deployment**

My projects range from **Vision-Language Models and remote sensing** to **agentic AI, distributed systems, computer vision, and edge intelligence**.

I enjoy understanding *why* a model works, experimenting with alternatives, and then engineering the surrounding system needed to make it useful in practice.

---

## 🔬 What I Work On

<table>
<tr>
<td width="50%" valign="top">

### 🧠 AI Research

* Deep Learning
* Computer Vision
* Vision-Language Models
* Natural Language Processing
* Image Captioning
* Transformers
* Feature Learning
* Model Evaluation
* Remote Sensing

</td>
<td width="50%" valign="top">

### 🤖 Applied AI

* Machine Learning
* Agentic AI
* Retrieval-Augmented Generation
* LLM-based Systems
* Intelligent Decision Systems
* Predictive Modeling
* AI-assisted Applications

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ⚙️ AI Engineering

* PyTorch
* TensorFlow
* Transformers
* FastAPI
* Apache Kafka
* Docker
* Distributed Systems
* REST APIs

</td>
<td width="50%" valign="top">

### 🔌 Edge & Embedded AI

* STM32
* Bare-metal C
* TinyML
* TensorFlow Lite Micro
* ESP32
* IoT
* Sensor Integration
* USART / 1-Wire

</td>
</tr>
</table>

---

# 🚀 Featured Work

> A selection of projects representing my progression from **machine learning experimentation → AI research → intelligent distributed systems → real-world applications**.

---

## 🛰️ 01 — Remote Sensing Image Captioning

### Transformer-based Vision-Language Research

**PFA · ENIT · Nov 2025 – Apr 2026**

Turning satellite imagery into meaningful natural-language descriptions.

This project explores **Vision-Language Modeling for remote sensing**, where the system learns to understand complex satellite scenes and generate textual descriptions of their content.

I reproduced and extended the **TSFE research baseline**, investigating how visual feature extraction, feature fusion, and sequence generation affect caption quality.

### 🔬 Research Contributions

* Reproduced and analyzed the original **TSFE architecture**
* Re-engineered the feature-processing pipeline and fixed implementation issues
* Replaced the original backbone with **SwinV2-Base**
* Introduced a **6-layer Transformer decoder**
* Experimented with different feature representations and training configurations
* Evaluated models using **CIDEr, BLEU-4, and ROUGE-L**
* Worked with **RSICD, UCM-Captions, and Sydney-Captions**

### 📈 Result

**+136.7% CIDEr improvement** over my reproduced baseline.

The project gave me practical experience with the full research workflow:

`Paper → Reproduction → Debugging → Experimentation → Architecture Changes → Evaluation`

🔗 **[Explore the project →](https://github.com/yahyahouimdi/RSIC_remote_sensing_image_captioning)**

---

### ↓ From Vision-Language Research to Intelligent Systems

The next step was to move from **offline model experimentation** toward systems that process information continuously and make decisions in real time.

---

## 🏥 02 — Patient Monitoring with Agentic AI & Apache Kafka

### Event-Driven Intelligent Healthcare Architecture

**AI Research Internship · CRMN · June 2026 – July 2026**

A real-time patient-monitoring architecture designed around **event-driven processing and intelligent decision-making**.

The system integrates heterogeneous streams from **patients, smart-home environments, and wearable devices**, processes them through Apache Kafka, and applies multiple levels of intelligence to identify potentially critical situations.

### 🏗️ Architecture

```text
                 ┌──────────────────┐
                 │ Wearable Sensors │
                 └────────┬─────────┘
                          │
                 ┌────────▼─────────┐
                 │   Smart Home     │
                 │     Devices      │
                 └────────┬─────────┘
                          │
                 ┌────────▼─────────┐
                 │  Patient Data    │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │   Apache Kafka   │
                 │ Event Streaming  │
                 └────────┬─────────┘
                          │
             ┌────────────┴────────────┐
             ▼                         ▼
     ┌────────────────┐       ┌────────────────┐
     │    Tier 1      │       │    Tier 2      │
     │ Rule-Based AI  │       │ Reasoning Agent│
     └───────┬────────┘       └───────┬────────┘
             │                         │
             └────────────┬────────────┘
                          ▼
                 ┌──────────────────┐
                 │ Decision / Alert │
                 └──────────────────┘
```

### ⚡ Key Contributions

* Designed an **event-driven distributed architecture**
* Built Kafka-based real-time data pipelines
* Implemented a low-latency **Tier 1 rule-based layer**
* Designed a reasoning-oriented **Tier 2 agent layer**
* Unified heterogeneous patient and environmental streams
* Explored how multiple levels of intelligence can coexist in time-critical systems

The project strengthened my interest in **AI systems engineering** — not just building models, but designing the infrastructure around them.

🔗 **[Explore the project →](https://github.com/yahyahouimdi/patient-monitoring-kafka-agents)**

---

### ↓ From Real-Time Intelligence to Predictive Modeling

After working with real-time decision systems, I moved toward another practical question:

**Can machine learning uncover hidden patterns in real-world economic data?**

---

## 🏘️ 03 — Tunisian Real Estate Price Prediction

### Machine Learning for the Tunisian Property Market

**Machine Learning Internship · SOTUPUB · Aug 2026 – Present**

A predictive modeling project focused on estimating **real estate prices in Tunisia** from property characteristics and geographic information.

The project covers the complete machine-learning pipeline — from raw data collection to feature engineering, modeling, and evaluation.

### 🔎 Current Work

* Collecting and structuring real-estate market data
* Cleaning and preprocessing heterogeneous property information
* Engineering meaningful property and location features
* Investigating the strongest factors influencing prices
* Training and comparing machine-learning models
* Evaluating model performance
* Building a foundation for practical price estimation

The objective is not simply to predict a number, but to understand **which characteristics drive property value** and how machine learning can model a complex local market.

🔗 **[Explore the project →](https://github.com/yahyahouimdi/Tunisian-real-estate-price-prediction-model)**

---

# ⚽ 04 — AI Football Analysis System

### Computer Vision for Automated Match Analysis

**Independent Computer Vision Project · 2026**

An experimental football-analysis system designed to transform raw match footage into **structured information about players and the game**.

Using **YOLO, OpenCV, and Python**, the system processes video frames to detect and track objects relevant to football analysis.

### 🎯 Pipeline

```text
Match Video
     │
     ▼
Frame Extraction
     │
     ▼
Object Detection
     │
     ▼
Player / Ball Detection
     │
     ▼
Object Tracking
     │
     ▼
Spatial & Temporal Analysis
     │
     ▼
Structured Match Data
```

The project explores the engineering challenges behind applying computer vision to unconstrained sports footage, including **small-object detection, occlusion, camera movement, tracking consistency, and temporal information**.

🔗 **[Explore the project →](https://github.com/yahyahouimdi/AI-Football-Analysis-System-)**

---

# 🛡️ 05 — Sightector

### NLP for Online Harassment Detection

**Machine Learning · NLP · Social Impact · IEEE ENIT SIGHT**

Sightector is a machine-learning system designed to detect **online harassment and harmful textual content**.

The project combines NLP preprocessing, text classification, model evaluation, and browser-oriented deployment into a system designed around a real social-impact problem.

### 🧠 Technical Focus

* Text preprocessing
* NLP feature extraction
* Machine-learning classification
* Model evaluation
* Real-time inference
* Chrome extension integration

Rather than treating the model as an isolated classifier, the project focused on the complete path from **text input → prediction → user-facing intervention**.

🔗 **[Explore the project →](https://github.com/yahyahouimdi/sightector)**

---

# 🌍 Leadership & Social Impact

## IEEE ENIT SIGHT Group

### President · 2025 – 2026

As President of the **IEEE ENIT SIGHT Group**, I led a multidisciplinary team of engineers and students working on technology-driven humanitarian initiatives.

### 🏆 Highlights

* **Best SIGHT Group of the Year — Global**
* **1st Place — SDC Congress** among national groups
* Led **4+ technology-driven humanitarian initiatives**
* Built collaborations with external organizations
* Coordinated engineering, research, and social-impact activities

Projects included:

`Sightector` · `RemindMeBox` · `CatchWise` · `Give for Good`

This experience taught me that engineering impact is not only about technical performance — it is also about **team organization, communication, leadership, and turning ideas into working systems**.

---

## 🌊 Posidonia — Sustainable Materials Project

### Project Lead · Injaz · 2025 – 2026

Led a **25-member multidisciplinary team** working on the transformation of *Posidonia oceanica* waste into a sustainable insulation material.

The project combined:

* Material research
* Experimental formulation
* Prototyping
* Technical planning
* Team coordination
* Product-oriented development

From research and experimentation to functional prototypes, the project required managing the complete path from **concept → experimentation → engineering → delivery**.

---

# 🧰 Technical Stack

### AI / Machine Learning

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
</p>

### Computer Vision & AI

<p>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLO-111111?style=flat-square"/>
<img src="https://img.shields.io/badge/NLP-412991?style=flat-square"/>
<img src="https://img.shields.io/badge/LLMs-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/RAG-4B0082?style=flat-square"/>
</p>

### Backend & Distributed Systems

<p>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

### Software Engineering

`Java` · `C` · `C++` · `JavaScript` · `TypeScript` · `SQL`

`React` · `Angular` · `Flutter` · `Three.js`

`PostgreSQL` · `MySQL` · `REST APIs`

### Embedded & Edge AI

`STM32` · `ESP32` · `Bare-metal C` · `TinyML`

`TensorFlow Lite Micro` · `IoT` · `USART` · `1-Wire`

### Tools

`Git` · `GitHub` · `Linux` · `Docker` · `VS Code`

---

# 📚 Certifications & Training

| Certification                                                 | Provider                          |
| ------------------------------------------------------------- | --------------------------------- |
| **Machine Learning Specialization**                           | DeepLearning.AI · Stanford Online |
| **Deep Learning Specialization**                              | DeepLearning.AI                   |
| **IBM AI Engineering Professional Certificate**               | IBM                               |
| **Microsoft Certified: Azure AI Engineer Associate (AI-102)** | Microsoft                         |
| **Google AI Essentials**                                      | Google                            |

---

# 🎓 Education

### National Engineering School of Tunis — ENIT

**Engineering Degree in Computer Science**

**Double-Degree Master's — Information System Techniques (IST)**

University of Tunis El Manar × **TU Braunschweig**

---

### Preparatory Institute for Engineering Studies of Monastir — IPEIM

**Preparatory Engineering Studies**

---

# 🎯 Current Research Direction

I'm currently focusing on the intersection of:

```text
                 AI RESEARCH
                      │
                      ▼
             Machine Learning
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
   Computer Vision          Intelligent Systems
          │                       │
          └───────────┬───────────┘
                      ▼
                AI ENGINEERING
                      │
                      ▼
              REAL-WORLD IMPACT
```

### Areas I'm particularly interested in

`AI Research`

`Computer Vision`

`Vision-Language Models`

`Applied Machine Learning`

`Agentic AI`

`Intelligent Systems`

`AI Engineering`

I'm particularly interested in opportunities where I can contribute to **research, experimentation, model development, and the engineering of deployable AI systems**.

---

# 🌐 Languages

🇹🇳 **Arabic** — Native
🇬🇧 **English** — B2
🇫🇷 **French** — B2
🇩🇪 **German** — A1

---

# 🤝 Let's Connect

I'm always interested in connecting with people working on **AI research, machine learning, computer vision, intelligent systems, and engineering**.

<p align="center">

<a href="mailto:yahya.houimdi@etudiant-enit.utm.tn">
<img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/yahya-houimdi-163492338/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/yahyahouimdi/portfolio">
<img src="https://img.shields.io/badge/Portfolio-Explore-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

---

<p align="center">
  <i>Research deeply. Engineer carefully. Build for impact.</i>
</p>
