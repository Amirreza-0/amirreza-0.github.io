---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="/files/cv.pdf" class="btn btn--primary" style="float:right; margin-top:-2rem;">📄 Download PDF</a>

Education
======
* **M.Sc. in Computational Biology and Bioinformatics**, Georg-August-Universität Göttingen, Germany, Oct 2022 – Oct 2025
  * GPA: 1.6
  * Relevant Coursework: Machine Learning, Deep Learning, Advanced NLP, Omics Data Analysis, Systems Biology, Computational Biomedicine, Advanced Statistical Learning

* **B.Sc. in Cellular and Molecular Biology**, Azad University, Science and Research Branch, Tehran, Iran, Oct 2018 – Jan 2022
  * GPA: 1.7 (17.66/20)
  * Relevant Coursework: Microbiology and Laboratory, Biostatistics, Biotechnology, Molecular Genetics, Genetic Engineering, Cancer Genetics, Cell and Molecular Biology

Research Experience
======
* **Jan 2025 – present: Internship → Master's Thesis → Research Assistant**
  * Söding Lab, Quantitative & Computational Biology
  * Max Planck Institute for Multidisciplinary Sciences, Göttingen
  * Sequence–structure representation learning using structural alignment (FoldMason) and MSA (MAFFT)
  * Deep-learning model training with custom 2D masked self-attention for pairwise positional interaction modeling
  * Transfer learning to underrepresented MHC alleles; protein language models (ESM); likelihood-based loss design for noisy binding labels
  * **Outputs**: PMBind (master's thesis; manuscript in preparation); PMGen (preprint, second author — DOI: [10.1101/2025.11.14.688404](https://doi.org/10.1101/2025.11.14.688404))

* **Apr 2024 – present: ML Internship → Research Assistant (FAIrPaCT consortium)**
  * Hauschild Lab, Predictive Deep Learning for Medicine and Healthcare
  * University Medical Center Göttingen / Justus Liebig University Giessen
  * Multi-modal survival modeling from somatic mutations (MAF), RNA expression, and clinical variables across federated clinical sites
  * **Outputs**: FedPanod (PyPI), FRSF4POD (PyPI, GitHub)
  * Supervisor: Prof. Dr. Anne-Christin Hauschild

* **Nov 2023 – Jul 2024: Student Assistant**
  * Dönitz Lab, Onkopus Project
  * University Medical Center Göttingen
  * Built a dynamic KEGG pathway visualizer
  * Updated the pyliftover package
  * Wrote a GitLab auto-merge pipeline used by the team

* **Apr – Sep 2023: Tutor — Python Programming for Data Scientists**
  * GippLab, Georg-August-Universität Göttingen
  * Supported students during exercises
  * Built web scrapers and curated an NLP dataset for media-bias research

Independent Projects
======
* **Apr 2026**: [bayesian-playgrounds](https://github.com/Amirreza-0/bayesian-playgrounds) — interactive webpage for teaching Bayesian and simulation-based inference
* **Jan 2026**: 🥇 **Kaggle Gold Medal** — Stanford RNA 3D Folding Part 2: pipeline combining homology modeling, MSA-guided folding, deep learning for coordinate prediction, and PDB structure analysis
* **Nov 2025**: Kaggle — CAFA 6 Protein Function Prediction: GNNs, BioBERT, MMseqs2, ESM-3

Skills
======
* **Programming**
  * Python (TensorFlow, Keras, PyTorch, scikit-learn, Pandas, NumPy, BioPython, Biotite, RDKit)
  * R, Bash, LaTeX, TypeScript, React

* **Machine Learning & Data Science**
  * Deep Learning, Representation Learning, Transfer Learning
  * Federated Learning
  * Natural Language Processing (NLP)
  * Simulation-based Inference (Bayesian)
  * Survival Analysis

* **Bioinformatics**
  * RNA secondary and 3D structure prediction
  * Template-based modeling (TBM); Kabsch superimposition
  * Sequence–structure alignment (FoldMason, MAFFT)
  * Protein language models (ESM)
  * Multi-omics integration; genomic variant processing (MAF/VCF); RNA-seq

* **Infrastructure**
  * Docker, Git/GitLab CI/CD, HPC/SLURM, Conda/Mamba, Linux

* **Languages**
  * English (C1 — IELTS Band 7.0)
  * German (B1)
  * Persian (Native)

Publications
======
* **Nov 2025**: **PMGen: From Peptide–MHC Prediction to Neoantigen Generation** (preprint).
  Second author (benchmarking and validation). DOI: [10.1101/2025.11.14.688404](https://doi.org/10.1101/2025.11.14.688404)

Funding and Awards
======
* **2025**: Niedersachsenstipendium — Graduate scholarship, State of Lower Saxony
* **2025**: Erasmus+ BIP — 2× travel and study grant (Spain and Sweden)
* **2024, 2025**: FAIrPaCT Consortium Workshops — 2× travel funding (Munich and Giessen)

Workshops and Certificates
======
* **Apr 2025**: AI and Law Workshop — Erasmus BIP, Universidad del País Vasco, Donostia–San Sebastián, Spain
* **Sep 2024**: How to learn from complex data I: simulation-based inference — CIDBN, Göttingen
* **May 2022**: IELTS Academic — Overall Band 7.0 (CEFR C1). Listening 8.5 | Reading 6.5 | Writing 6.0 | Speaking 7.0
* **Mar – Apr 2021**: Molecular Genetics Internship — Azad University with Mana Lab, Tehran (PCR/DNA extraction, RT-PCR, immunoassay)
* **Nov 2021**: Statistics and R — HarvardX (edX)
* **Apr 2021**: Introduction to NGS and its applications — Islamic Azad University with IBIS, Tehran
* **Oct – Dec 2020**: Evolutionary Computation and Biological Computation — Interdisciplinary Schools, Tehran
* **Jul – Sep 2021**: Introduction to machine vision and image processing — Interdisciplinary Schools, Tehran

Extracurricular Activities
======
* Archery — DHM Barebow Rookie (German University Championships)
* Game design

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
