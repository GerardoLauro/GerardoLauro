<div align="center">

<h1>Gerardo Lauro</h1>
<p><strong>Applied AI · Data Engineering · LLM Evaluation</strong></p>
<p>MSc candidate in Computer Engineering (AI &amp; Big Data)<br>
University of Naples Federico II · Erasmus thesis at Universidad Politécnica de Madrid</p>

<a href="#selected-projects"><img alt="Projects" src="https://img.shields.io/badge/Projects-172B4D?style=for-the-badge&amp;logo=github&amp;logoColor=white"></a>
<a href="https://www.linkedin.com/in/gerardo-lauro-97954a293/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
<a href="mailto:gerardo.lauro.dev@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-117A73?style=for-the-badge&amp;logo=gmail&amp;logoColor=white"></a>

[gerardo.lauro.dev@gmail.com](mailto:gerardo.lauro.dev@gmail.com)

</div>

I build data pipelines that can be audited and evaluate models against explicit baselines and source evidence.

## Technical skills

**Programming and data**  
![Python](https://img.shields.io/badge/Python-375A7F?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-375A7F?style=flat-square) ![NumPy](https://img.shields.io/badge/NumPy-375A7F?style=flat-square&logo=numpy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-375A7F?style=flat-square&logo=pandas&logoColor=white) ![Apache Parquet](https://img.shields.io/badge/Apache_Parquet-375A7F?style=flat-square&logo=apacheparquet&logoColor=white)

**Machine learning and optimization**  
![PyTorch](https://img.shields.io/badge/PyTorch-8A4F93?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-8A4F93?style=flat-square&logo=scikitlearn&logoColor=white) ![NLP](https://img.shields.io/badge/NLP-8A4F93?style=flat-square) ![PuLP](https://img.shields.io/badge/PuLP-8A4F93?style=flat-square) ![Mixed-integer optimization](https://img.shields.io/badge/Mixed--integer_optimization-8A4F93?style=flat-square)

**Data systems and visualization**  
![SQLite](https://img.shields.io/badge/SQLite-117A73?style=flat-square&logo=sqlite&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-117A73?style=flat-square&logo=neo4j&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-117A73?style=flat-square&logo=pydantic&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-117A73?style=flat-square&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-117A73?style=flat-square&logo=plotly&logoColor=white)

**Software quality and delivery**  
![Git](https://img.shields.io/badge/Git-536580?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-536580?style=flat-square&logo=githubactions&logoColor=white) ![pytest](https://img.shields.io/badge/pytest-536580?style=flat-square&logo=pytest&logoColor=white) ![Hypothesis](https://img.shields.io/badge/Hypothesis-536580?style=flat-square) ![Ruff](https://img.shields.io/badge/Ruff-536580?style=flat-square&logo=ruff&logoColor=white)

## Selected projects

### [CivicData Sentinel](https://github.com/GerardoLauro/CivicData-Sentinel)

**Data quality · Data contracts · Audit trails**

I built a monitor for Madrid’s public datasets. It validates incoming snapshots, quarantines suspicious updates and preserves the evidence needed to replay each decision offline. The dashboard below shows a local run with observed municipal data.

[![CivicData Sentinel dashboard showing Madrid municipal data and dataset status](https://raw.githubusercontent.com/GerardoLauro/CivicData-Sentinel/main/docs/assets/dashboard-overview.png)](https://github.com/GerardoLauro/CivicData-Sentinel)

[Example outcomes](https://github.com/GerardoLauro/CivicData-Sentinel/blob/main/docs/examples.md) · [CI runs](https://github.com/GerardoLauro/CivicData-Sentinel/actions/workflows/ci.yml)

### [Polysignal](https://github.com/GerardoLauro/Polysignal)

**Data pipelines · NLP · Knowledge graphs · Temporal evaluation**

I co-developed a research pipeline that links social discussions to prediction markets and tests whether the resulting signals add information beyond market prices. The documented experiment covered **300 resolved markets** and approximately **1.37 million posts**. In that evaluation, the social features did not improve on the market baseline. The public repository includes code, documentation and data samples.

[Technical report](https://github.com/GerardoLauro/Polysignal/blob/main/pdf_latex/main.pdf) · [Reproducibility guide](https://github.com/GerardoLauro/Polysignal/blob/main/docs/REPRODUCIBILITY.md)

| Project | Technical focus | Starting point |
| --- | --- | --- |
| **[Energy Planner](https://github.com/GerardoLauro/Innothon2025-energy-efficiency)** | Innothon prototype for energy scheduling with PuLP/CBC and a comparison against a baseline schedule. | [Offline demo](https://github.com/GerardoLauro/Innothon2025-energy-efficiency#demo-offline) |
| **[Wavelet-SRNet](https://github.com/GerardoLauro/Progetto-ESM)** | PyTorch coursework on wavelet-based image super-resolution, with training and evaluation scripts. | [Training and evaluation](https://github.com/GerardoLauro/Progetto-ESM#training-16x16---128x128) |

## Current research

**Scientific Hallucination Guard** · Master's thesis in progress. I'm developing a system that checks individual claims in LLM-generated scientific text against source papers. The evaluation focuses on numerical and methodological errors, evidence retrieval and cases where the evidence is inconclusive.
