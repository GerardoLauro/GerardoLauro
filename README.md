<div align="center">

<h1>Gerardo Lauro</h1>
<p><strong>Applied AI · Data Engineering · LLM Evaluation</strong></p>
<p>MSc candidate in Computer Engineering (AI &amp; Big Data)<br>
University of Naples Federico II · Erasmus thesis at Universidad Politécnica de Madrid</p>

[Projects](#selected-projects) · [LinkedIn](https://www.linkedin.com/in/gerardo-lauro-97954a293/) · [gerardo.lauro.dev@gmail.com](mailto:gerardo.lauro.dev@gmail.com)

</div>

I build data pipelines that can be audited and evaluate models against explicit baselines and source evidence.

## Technical skills

![Technical skills by area. Programming and data: Python, SQL, NumPy, pandas, Apache Parquet. Machine learning and optimization: PyTorch, scikit-learn, NLP, PuLP, mixed-integer optimization. Data systems and visualization: SQLite, Neo4j, Pydantic, Streamlit, Plotly. Software quality and delivery: Git, GitHub Actions, pytest, Hypothesis, Ruff.](https://raw.githubusercontent.com/GerardoLauro/GerardoLauro/main/technical-skills.svg)

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
