<!--
  GitHub PROFILE README
  ---------------------
  This file belongs in a special repository named exactly after your username:
  create a repo called  chr13b/chr13b  (public), add this file as README.md at
  its root, and it will render at the top of https://github.com/chr13b.

  TODO before publishing:
   - Verify each project link below — the slugs are my best guess and some repos
     aren't pushed yet. Fix any that differ from the real repo names.
   - Fill in the LinkedIn URL and confirm the email / degree line.
-->

<h1 align="center">Hi, I'm Christian (Chris) Bertsch 👋</h1>

<p align="center">
  Machine learning for <b>biology, health, and decision-making under uncertainty</b> —
  from algorithms built from scratch to deep learning, LLMs, and provable guarantees.
</p>

<p align="center">
  <!-- Adjust the affiliation line to taste -->
  🎓 MSc @ ETH Zürich &nbsp;·&nbsp; 🔬 ML × computational biology &nbsp;·&nbsp; 📍 Zürich / Basel
</p>

---

### About me

I build end-to-end machine-learning pipelines and care about getting the *whole* pipeline
right — leakage-aware validation, honest metrics, and reproducibility — not just the model.
My work spans **applied ML in biology and healthcare**, **probabilistic / trustworthy ML**,
and a few **data-science hackathons**. I'm equally comfortable implementing a method from
first principles in NumPy and wiring up PyTorch, BoTorch, or an LLM-backed RAG system.

- 🧬 **Domains:** genomics, antibody design, clinical & mobile-health data, molecular simulation
- 🤖 **Methods:** deep learning, Gaussian processes & Bayesian optimization, NLP/LLMs, formal verification
- 🧪 **Principle:** cross-validation over leaderboard-chasing; I report what actually reproduces

---

### 🚀 Featured projects

| Project | What it is | Highlights |
|---|---|---|
| **[GP-BayesOpt for Antibody Design](https://github.com/chr13b/gp-bayesopt-antibody-design)** | Gaussian-process surrogate + multi-task Bayesian optimization over ESM-2 protein embeddings | GP predicts developability/specificity at R² ≈ 0.86 / 0.97 on real lab data; closed-loop BO beats random search (2.26 vs 1.45) · **BoTorch · GPyTorch** |
| **[DeepPoly Robustness Verifier](https://github.com/chr13b/deeppoly-robustness-verifier)** | Sound neural-network verifier that *proves* L∞ robustness via convex relaxation + learnable ReLU bounds | **69/70** test cases correct, **0** unsound certifications, across 13 networks · **PyTorch (autograd)** |
| **[NaNsense — RAG over company websites](https://github.com/chr13b/NaNsense)** | Retrieval-augmented generation that grounds GPT-4o answers in a scraped-web corpus, with source attribution | Cleaning pipeline cuts the corpus ~9× (17 GB → 1.9 GB); live Gradio demo · **LangChain · Chroma · GPT-4o** |
| **[Synthetic Market Sharpe](https://github.com/chr13b/synthetic-market-sharpe)** | Cross-sectional trading model for a simulated market, optimizing the Sharpe ratio | Packaged `src/` pipeline: feature builders, Bayesian/LightGBM regressors, and an LSTM trained on a differentiable Sharpe loss · session-level CV |
| **[Machine Learning for Genomics](https://github.com/chr13b/ML4G)** | Predicting gene expression from chromatin signal; single-cell clustering + bulk RNA-seq deconvolution | Expression Spearman ρ ≈ 0.56; deconvolution 0.047 RMSE (vs 0.37 baseline) · **scikit-learn · Scanpy** |
| **[Clinical ML Interpretability & Tweet NLP](https://github.com/chr13b/ML4H)** | Explainable clinical classification (SHAP / Grad-CAM, sanity-checked) + fine-tuned BERT on COVID-19 tweets | Pneumonia CNN F1 0.87; BERT sentiment F1 0.73 · **PyTorch · Hugging Face · Captum** |

---

### 📚 More projects

**Applied & deep ML**
- [ml-regression-to-deep-learning](https://github.com/chr13b/ml-regression-to-deep-learning) — four ML tasks from regularized regression to deep metric & transfer learning (all cleared the course's hard baseline)
- [Classical → Deep Computer Vision](https://github.com/chr13b/classical-to-deep-computer-vision) — five CV projects from PCA/graph-cuts to CNNs and ResNet transfer learning, built from primitives
- [Probabilistic AI](https://github.com/chr13b/Probabilistic_AI) — Gaussian processes, Bayesian deep learning (SWAG), constrained BO, and DDPG reinforcement learning

**Computational biology & from-scratch algorithms**
- [molecular-phylogenetics-r](https://github.com/chr13b/molecular-phylogenetics-r) — alignment, tree-building & Felsenstein likelihood in R, 363 passing test assertions
- [Data Mining from Scratch](https://github.com/chr13b/data-mining-from-scratch) — distances, DTW, graph & string kernels, k-NN/Naive Bayes implemented in pure NumPy
- [GROMOS Biomolecular MD](https://github.com/chr13b/gromos-biomolecular-md) — six molecular-dynamics studies benchmarked against experiment

**Health & sensing**
- [Mobile-Sensing Symptom Prediction](https://github.com/chr13b/mobile-sensing-symptom-prediction) — leakage-aware, participant-grouped CV on 4 years of GLOBEM data
- [IMU Step Counting & Activity Recognition](https://github.com/chr13b/imu-step-count-and-activity-recognition) — peak-detection step counter + Random-Forest activity classifier on wearable IMU data

**Data-science hackathons**
- [Solar PV Forecasting & Spot-Market Trading](https://github.com/chr13b/solar-pv-forecasting-trading) — day-ahead Swiss PV forecasting (Ridge + XGBoost ensemble) → trading positions (Axpo Datathon 2024)

---

### 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

**Also:** BoTorch / GPyTorch · Scanpy / AnnData · XGBoost / LightGBM · SHAP / Captum · Gradio · Chroma

---

### 📫 Get in touch

<p align="left">
  <a href="mailto:chris.bertsch01@googlemail.com">📧 Email</a> &nbsp;·&nbsp;
  <!-- TODO: add your real LinkedIn URL -->
  <a href="https://www.linkedin.com/in/your-handle">💼 LinkedIn</a>
</p>

<!--
  Optional: GitHub stats cards. They look nice but some recruiters find them noisy —
  uncomment if you want them. They render automatically once your repos are public.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=chr13b&show_icons=true&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=chr13b&layout=compact&hide_border=true" height="160" />
</p>
-->
