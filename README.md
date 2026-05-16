# Hi, I'm Prithwiraj Chatterjee 👋

**GRA @ University of Texas at Arlington · Graduating Dec 2026**

I build end-to-end ML systems from on-device computer vision and genomic classifiers to time-series forecasting pipelines. I like problems where the model architecture has to be *justified*, not just chosen by convention.

Currently open to **ML Engineer**, **Data Scientist**, and **Research Scientist** roles starting Summer/Fall 2026.

---

## 🔧 What I Work With

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=google-colab&logoColor=white)

---

## 🚀 Featured Projects

### 🔍 [EdgeAuth](https://github.com/Prithwi13/EdgeAuth) — On-Device AI Image Detection
> PyTorch · LoRA · Vision Transformer · MobileNet · DPO

A four-stage cascade architecture that detects AI-generated images **entirely on-device** — no cloud, no privacy exposure. Combines a frozen ResNet-50 stem with a LoRA-adapted 12-layer Vision Transformer, a Guard MLP aligned via Direct Preference Optimization, and a MobileNet-style FastPath pre-filter.

- **97.42% validation accuracy** on CIFAKE (120K images, 33 cancer types) — +8.9 pp over ResNet-50 baseline
- Only **0.76% of parameters** updated during training (0.72M / 95.4M)
- 47.1% of inference traffic routed through the FastPath alone; ECE = 0.0183

---

### 🧬 [Genomic Optimizer Benchmark](https://github.com/Prithwi13/6302_stock) — Optimizer × Schedule Factorial for Cancer Classification
> PyTorch · scikit-learn · SciPy · TCGA Pan-Cancer

A **144-model factorial benchmark** (6 optimizers × 4 LR schedules × 2 regularizers × 3 seeds) on multinomial logistic regression for 33-class TCGA Pan-Cancer classification across 20,000 genes.

- **L-BFGS achieves 91.4% mean test accuracy** — beats Adam by 5.3 pp on a convex tabular problem
- Schedule effect (0.48 pp swing) is **~20× smaller** than optimizer effect (9.3 pp) — a direct challenge to deep-learning conventions
- **200-gene Lasso panel** matches the full 2,820-gene model (92.9% test acc) via LP-based gene budget selection

---

### 🏠 [Smart Home Bio-Analytics](https://github.com/Prithwi13) — Occupancy Detection from Thermodynamic Sensors
> R · forecast · randomForest · SARIMAX · STL

A bio-analytics pipeline that infers room-level human presence from **temperature and humidity alone** — no motion sensors, no cameras, no labeled data — and uses those occupancy scores to forecast hourly appliance energy consumption.

- **Random Forest RMSE: 51.2 Wh** — 35% improvement over seasonal naïve baseline
- **4 of the top 6 most important RF features** are derived occupancy scores, outweighing outdoor weather variables
- Recovers weekly household routines (wake/sleep times, meal patterns, weekday vs. weekend) without any clustering algorithm

---

## 📊 Other Work

| Repo | Description | Stack |
|---|---|---|
| [NBA](https://github.com/Prithwi13/NBA) | NBA player/team analytics and performance modeling | Python, Jupyter |
| [SIGNAL](https://github.com/Prithwi13/SIGNAL) | Signal processing and visualization | JS |

---

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/prithwiraj-chatterjee)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:prithwiraj@example.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Prithwi13)

---

<sub>Floyd listener · Piano player · Sports & art enthusiast · Gets excited about almost anything</sub>
