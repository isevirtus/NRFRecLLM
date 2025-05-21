<h1>🔍 NFRRec-LLM: Reproducing NFR Recommendation using Large Language Models</h1>

<p align="center">
  <b>Evaluating the Capability of Prompted LLMs to Recommend Non-Functional Requirements from User Stories</b><br/>
  <i>Companion Artifact for SBES 2025 Submission</i><br/>
</p>

---

## 📜 About

This repository provides the complete code, data, prompts, and analysis scripts for reproducing the experiments described in our paper:

> **Evaluating the Capability of Prompted LLMs to Recommend Non-Functional Requirements from User Stories: A Preliminary Study (SBES 2025)**

The goal is to assess whether large language models (LLMs) like GPT-4 can recommend non-functional requirements (NFRs) from functional descriptions (user stories) in agile projects. This serves as an alternative to traditional recommender systems like NFRec, especially in cold-start scenarios.

---

## 🗂️ Project Structure

| Folder/File     | Description                                                                                                 |
| ----------------| ----------------------------------------------------------------------------------------------------------- |
| 📁 <b>data/</b> | Contains the dataset with processed user stories and annotations.<br/>File: <code>dados_processados_projetos_final.csv</code> |
| 📁 <b>prompts/</b> | Contains the Jupyter notebook used for LLM inference via OpenAI API.<br/>File: <code>openai_api.ipynb</code> |
| 📁 <b>results/</b> | Contains the generated results, including CSV with model outputs.<br/>Main file: <code>results_final.csv</code> and script <code>Gerar_resultados.ipynb</code> for processing results. |
| 📄 <b>LICENSE</b> | Open-source license for this repository. |
| 📄 <b>README.md</b> | This file. Provides description, usage instructions, and credits. |

---

## 🚀 How to Run

### 🛠️ Requirements

- Python 3.10+
- Jupyter Notebook
- OpenAI API Key (if using OpenAI models)

### 🔧 Install dependencies

```bash
pip install openai pandas jupyter
