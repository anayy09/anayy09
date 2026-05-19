<!--
  Design Philosophy
  =================
  Aesthetic: Apple × NASA × research lab — minimal, typographic, precise.
  Optimized for GitHub dark mode. Zero external dependencies.
  Every section earns its place. Nothing is filler.

  Intentionally removed:
  - Animated headers, typing SVGs, waving banners (generic template look)
  - Badge walls and shields.io icons (visual noise, no signal)
  - GitHub stats / streak / contribution snake (vanity metrics)
  - Profile view / star / follower counters (low signal)
  - Stock GIFs and decorative images (unrelated clutter)
  - Emoji-prefixed section headers (unprofessional)
  - Tech stack badge grid (every developer has this)
  - Mermaid timeline (better conveyed through prose)
  - Skill bars / progress meters (cliché, meaningless)

  Why each section exists:
  - Hero: Identity signal. Name + domain + affiliation. No ambiguity.
  - Intro paragraph: The "so what" — positioning, current work, credibility.
  - Now: Shows momentum. Recruiters and collaborators care about present work.
  - Selected Work: 4 curated projects showing depth across clinical AI domains.
  - Publications: Research credibility. Venues and DOIs matter.
  - Patents: IP generation capability — rare for early-career researchers.
  - Stack: Actual tool fluency, grouped by domain. Not a badge collection.
  - Education: Institutional credibility + distinction, kept compact.
  - Connect: Clean access points at the end. No "reach out to me!" energy.
-->

<div align="center">

# Anay Sinhal

**Clinical AI · Multimodal Learning · Health Data Infrastructure**

<br>

M.S. Computer Science · [University of Florida](https://www.cise.ufl.edu/)
<br>
Graduate Student Assistant · [PRISMAp Lab / IC3](https://ic3.center.ufl.edu/) · College of Medicine

<br>

[sinhal.anay@ufl.edu](mailto:sinhal.anay@ufl.edu) · [LinkedIn](https://www.linkedin.com/in/anaysinhal) · [anay.codes](https://www.anay.codes/) · [ORCID](https://orcid.org/0009-0008-8328-2336)

</div>

<br>

I build systems at the intersection of clinical medicine and machine learning — EHR time-series modeling, multimodal representation learning for medical imaging, and explainable clinical prediction. My focus is on making healthcare data computable and medical AI trustworthy, with attention to the full path from raw clinical data to deployable, interpretable infrastructure.

Currently at UF's Intelligent Clinical Care Center, developing social determinants of health data pipelines, pathology image de-identification systems, and clinical phenotyping workflows for multi-site research.

7 peer-reviewed publications · 3 patent applications · Gold Medal, B.Tech CSE

---

### now

At IC3 / PRISMAp Lab, College of Medicine, University of Florida:

- Designing SDoH linkage pipelines integrating multi-year indices (SVI, ADI, SDI, EJI) with hierarchical geocoding for a clinical data consortium; automating execution via scheduled Azure Container Apps jobs
- Building a pathology slide de-identification system for whole-slide images using ResNet/MobileNet text detection and PaddleOCR, with SLURM-based batch automation on HiPerGator and React audit dashboards
- Contributing to AKI phenotyping, clinical notes embeddings, and data cleaning pipelines; standardizing reproducible HPC preprocessing workflows and documentation across concurrent studies

---

### selected work

**[EHR Timeline Triage](https://github.com/anayy09/EHR-Timeline-Triage)** · `PyTorch` `FastAPI` `Next.js` `DuckDB` `Docker`
<br>
Bins longitudinal EHR events into 4-hour temporal windows and trains comparative models (Logistic Regression, GRU, Transformer) for 30-day readmission and 48-hour ICU mortality prediction. Evaluated with AUROC, AUPRC, Brier score, and calibration diagnostics. Interactive timeline UI surfaces risk trajectories and feature attribution explanations.

**[Radiology Copilot](https://github.com/anayy09/Radiology-Copilot)** · `PyTorch` `MONAI` `ClinicalBERT` `FastAPI` `Next.js`
<br>
CLIP-style multimodal chest X-ray system — ViT image encoder contrastively paired with ClinicalBERT text encoder for multi-label finding detection with calibrated uncertainty estimates. Integrated Grad-CAM saliency overlays, AI-drafted radiology reports, and a PostgreSQL-backed study workflow with full lifecycle tracking.

**[Sepsis Sentinel](https://github.com/anayy09/Sepsis-Sentinel)** · `XGBoost` `LightGBM` `SHAP` `FastAPI` `React`
<br>
Early sepsis detection from EHR data achieving AUROC 0.89 on validation cohorts, simulating 4-hour earlier detection compared to standard alerting windows. SHAP-based feature attribution enables per-patient risk explanation. Real-time monitoring dashboard with WebSocket streaming for live risk tracking across active patients.

**[WardOps](https://github.com/anayy09/WardOps)** · `FastAPI` `Next.js` `PostgreSQL` `Redis` `Celery`
<br>
Hospital operations digital twin combining discrete-event simulation with an LLM copilot using function calling for natural-language scenario queries. Sankey flow diagrams, bottleneck heatmaps, and side-by-side what-if comparisons for patient flow modeling and capacity planning.

---

### publications

**Stress Monitoring in Healthcare: An Ensemble ML Framework Using Wearable Sensor Data**
<br>
Springer · _Innovations in Computational Intelligence & Computer Vision_, 2026 · [doi:10.1007/978-3-032-14757-8_12](https://doi.org/10.1007/978-3-032-14757-8_12)

**High-Performance & Quantum Computing in Cancer Modeling: A Review & Hybrid HPC-Quantum Approach**
<br>
_International Journal of Advances in Signal & Image Sciences_, 2026 · [doi:10.29284/bfq8ev64](https://doi.org/10.29284/bfq8ev64)

**Contrastive Learning & Large Language Models for Depression Detection from Social Media**
<br>
IEEE · _International Conference on Contemporary Computing & Communications_, 2025 · [doi:10.1109/InC465408.2025.11256322](https://doi.org/10.1109/InC465408.2025.11256322)

**Optimizing Diagnostic Accuracy in Healthcare by Using Deep Learning**
<br>
IEEE · _4th World Conference on Applied Intelligence & Computing_, 2025 · [doi:10.1109/AIC66080.2025.11211920](https://doi.org/10.1109/AIC66080.2025.11211920)

**LoRA-Tuned Segment Anything Model for Few-Shot Polyp Segmentation in Colonoscopy Images**
<br>
_Journal of Carcinogenesis_, 2025 · [doi:10.64149/J.Carcinog.24.3.372-386](https://doi.org/10.64149/J.Carcinog.24.3.372-386)

---

### patents

**Bio-Inspired Adaptive Task Offloading System for Energy-Efficient IoT-Edge-Cloud Healthcare Continuum**
<br>
Indian Patent Application No. 202611027418 · Published May 2026

**Disaster-Resilient Digital File Dissemination via Fountain-Coded Broadcast with Super-Peer Election & Sparse Acknowledgement**
<br>
Indian Patent Application No. 202511063465 · Published July 2025

**Stress Monitoring System Using Wearable Sensor Data Integrated with an Ensemble Machine Learning Model**
<br>
Indian Patent Application No. 202511044124 · Published May 2025

---

### stack

**AI / ML** — PyTorch · TensorFlow · scikit-learn · Hugging Face Transformers · contrastive learning · LLM fine-tuning · SHAP · Grad-CAM · computer vision · NLP

**Data & Infrastructure** — PostgreSQL · MongoDB · Redis · DuckDB · Docker · Azure · AWS · SLURM / HiPerGator · CI/CD · ETL pipelines

**Software** — Python · Java · TypeScript · Go · C++ · Bash

**Web & APIs** — FastAPI · Django · Next.js · React · Node.js · Spring Boot

---

### education

**University of Florida** — M.S. Computer & Information Science & Engineering, 2025 – present
<br>
Graduate coursework began during CISE Senior Certificate Program, Spring 2025.

**JK Lakshmipat University** — B.Tech. Computer Science & Engineering, 2021 – 2025
<br>
Gold Medal (Dr. Kavita Choudhary Award for Best Outgoing Student in B.Tech CSE). Semester exchanges at **IIT Kanpur** (Spring 2024) and **IIT Gandhinagar** (Fall 2022). Best Innovator Award, Manipal University Jaipur.

---

<div align="center">

*Building clinical AI that earns trust through transparency.*

</div>
