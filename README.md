<div align="center">

# Yahya Houimdi

**AI Engineer · Applied AI Research · Computer Vision · Agentic Systems**

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=Turning+research+into+systems+that+industries+can+use;Computer+Vision+%C2%B7+Multimodal+AI+%C2%B7+Agentic+AI;Healthcare+%C2%B7+Earth+Observation+%C2%B7+PropTech+%C2%B7+Sports" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Yahya%20Houimdi-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yahya-houimdi-163492338/)
[![Portfolio](https://img.shields.io/badge/Portfolio-View-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/yahyahouimdi/portfolio)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:yahya.houimdi@etudiant-enit.utm.tn)
![Location](https://img.shields.io/badge/Tunis%2C%20Tunisia-555555?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

### About

Final-year **Computer Engineering** student at the **National Engineering School of Tunis (ENIT)**, in a double-degree Master's in **Information System Techniques** with the University of Tunis El Manar and **TU Braunschweig**.

I work where research meets real constraints. I like taking a method from a paper, reproducing it honestly, improving it, and then shipping it as a system that a hospital, a business, or an analyst can actually rely on — with benchmarks that show where it works and where it doesn't.

```text
problem in an industry  →  literature & baseline  →  experiments  →  measured improvement  →  deployable service
```

---

### Applied AI across industries

<div align="center">

| Industry | Problem | What I built | Status |
| :-- | :-- | :-- | :-: |
| 🏥 **Healthcare** | Remote patient monitoring | Two-tier Kafka pipeline: rule-based alarms + LLM agent with patient-scoped RAG | ✅ Prototype |
| 🛰️ **Earth Observation** | Describing satellite imagery | SwinV2 + Transformer captioning model, **+136.7% CIDEr** over reproduced baseline | ✅ Complete |
| 🏘️ **Real Estate** | Price estimation in Tunisia | Multi-source scraped dataset + ML pricing pipeline | 🔄 In progress |
| ⚽ **Sports Analytics** | Match video understanding | Fine-tuned YOLO detector for players, referees and ball | 🔄 In progress |
| 🛡️ **Online Safety** | Harassment detection | NLP classifier served via Flask API + Chrome extension | ✅ Deployed locally |

</div>

---

### Featured work

<table>
<tr>
<td width="50%" valign="top">

#### 🏥 Agentic Patient Monitoring
<sub>**Research Internship · CRMN · Jun – Jul 2026**</sub>

Event-driven monitoring for home care and assisted living.

- **Tier 1** — deterministic safety rules (heart rate, SpO₂, falls, sensor faults) published instantly over Kafka
- **Tier 2** — LangGraph agent (local `qwen2.5` via Ollama) with Qdrant retrieval and a guardrail that never lets the model go below the rule-based severity floor
- Benchmarked LangGraph, AutoGen, CrewAI and a native pipeline; FAISS, Chroma and Qdrant
- Patient-ID filtering cut cross-patient retrieval leakage from **93–97% to 0%**

`Kafka` `LangGraph` `Qdrant` `FastAPI` `Ollama` `RAGAS` `Docker`

[**→ Repository**](https://github.com/yahyahouimdi/patient-monitoring-kafka-agents)

</td>
<td width="50%" valign="top">

#### 🛰️ Remote Sensing Image Captioning
<sub>**Applied Research · ENIT · Nov 2025 – Apr 2026**</sub>

Natural-language descriptions of satellite images (RSICD, UCM, Sydney).

- Reproduced the **TSFE** baseline, then replaced the Swin backbone with **SwinV2-Base** and the LSTM with a **6-layer Transformer decoder**
- Two-stage training with GradNorm loss balancing, AMP, on a single T4
- RSICD: **CIDEr 14.35 → 33.97 (+136.7%)**, BLEU-4 +8.3%, ROUGE-L +2.8%
- Served through a **FastAPI** inference endpoint

`PyTorch` `timm` `SwinV2` `Transformers` `FastAPI`

[**→ Repository**](https://github.com/yahyahouimdi/RSIC_remote_sensing_image_captioning)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏘️ Tunisian Real Estate Pricing
<sub>**ML Internship · SOTUPUB · Aug 2026 – Present**</sub>

Data-driven price estimation for the Tunisian market.

- Scraped and merged listings from **Tayara, Mubawab and Tecnocasa** (Playwright)
- Cleaned 2,385 → 2,343 listings with structured location, surface and amenity features
- Next: separate sale/rent regressors evaluated on MAE, RMSE, R², MAPE

`Python` `Playwright` `Pandas` `scikit-learn`

[**→ Repository**](https://github.com/yahyahouimdi/Tunisian-real-estate-price-prediction-model)

</td>
<td width="50%" valign="top">

#### ⚽ Football Match Analysis
<sub>**Computer Vision Project · 2026**</sub>

Foundations for automated sports analytics from broadcast footage.

- Fine-tuned **YOLOv5x** on 4 classes (player, goalkeeper, referee, ball), compared against a COCO-pretrained YOLOv8x baseline
- Improved small-object (ball) detection after fine-tuning
- Roadmap: multi-object tracking, team assignment, possession stats

`YOLO` `Ultralytics` `PyTorch` `OpenCV`

[**→ Repository**](https://github.com/yahyahouimdi/AI-Football-Analysis-System-)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🛡️ Sightector — Online Harassment Detection
<sub>**IEEE ENIT SIGHT · Jan – May 2025**</sub>

TF-IDF + tuned Linear SVC classifier exposed through a **Flask API** and a **Chrome extension** that flags harmful text and suspicious links — all inference runs locally, so no user data leaves the machine.
`scikit-learn` `Flask` `NLP` `JavaScript` · [**→ Repository**](https://github.com/yahyahouimdi/sightector)

</td>
</tr>
</table>

---

### Tech stack

<div align="center">

**AI / ML**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLO-111F68?style=flat-square"/>

**LLMs & Agents**<br/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-6E40C9?style=flat-square"/>

**Systems & Deployment**<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>

**Data**<br/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white"/>

**Software Engineering**<br/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>

</div>

---

### Leadership

**IEEE ENIT SIGHT — Chair** · 2025 – 2026
Led the group to **Best SIGHT Group of the Year (Global)** and **1st place at the SDC Congress**; directed 4+ technology-for-humanitarian projects and built partnerships with external organizations.

**Posidonia — CEO** · 2025 – 2026
Student venture turning *Posidonia oceanica* waste into sustainable building insulation — strategy, team coordination and engineering concept.

---

### Education & certifications

<table>
<tr>
<td width="50%" valign="top">

**ENIT** — Engineering Degree, Computer Science
**Double-Degree Master's, IST** — Univ. Tunis El Manar × TU Braunschweig
**IPEIM** — Preparatory Engineering Studies

</td>
<td width="50%" valign="top">

Microsoft Azure AI Engineer Associate (AI-102)
IBM AI Engineering Professional Certificate
Deep Learning Specialization — DeepLearning.AI
Machine Learning Specialization — Stanford / DeepLearning.AI
Google AI Essentials

</td>
</tr>
</table>

---

<div align="center">

### Open to

**Applied AI / ML Engineering roles · Industrial research internships · R&D collaborations**
in healthcare, Earth observation, smart infrastructure and data-driven businesses.

<br/>

<img src="https://streak-stats.demolab.com/?user=yahyahouimdi&hide_border=true&theme=transparent" alt="GitHub streak" />

<br/><br/>

<sub>Research is the starting point — impact is the goal.</sub>

</div>
