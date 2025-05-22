# LLMzCor
# 📚 LLMzCor: Scientific Abstract Classifier for Infectious Diseases and Pharmacoepidemiology

LLMzCor is a research-oriented tool designed to classify scientific abstracts in the fields of **infectious diseases** and **pharmacoepidemiology**, leveraging state-of-the-art Large Language Models (LLMs). Built with **Python**, **SQL**, and the **LangChain** framework, this pipeline integrates **Mixtral 8x7B** to extract key information about emerging treatments and antimicrobial resistance.

---

## 🔍 Project Goals

- Automatically classify PubMed-style abstracts into categories such as:
  - **New Treatments**
  - **Reports of Multidrug-Resistant Strains**
  - **Immunization Strategies**

- Extract structured metadata using LLM prompts and vectorized embeddings.
- Enable batch processing and database storage for downstream analysis.
- Apply **unsupervised classification algorithms** in a semantic vector space.

---

## 🧠 Technologies Used

| Component       | Description                                                   |
|----------------|---------------------------------------------------------------|
| 🧠 Mixtral 8x7B | LLM used via local API for classification and summarization. |
| 🐍 Python       | Core scripting and preprocessing                              |
| 🗃️ SQLite       | Abstract storage and classification output                    |
| 🔗 LangChain    | Prompt engineering and LLM orchestration                      |
| 🧮 Scikit-learn | KMeans and other unsupervised learning algorithms             |
| 📊 Power BI     | Optional dashboarding of classification trends (external)    |

---

## ⚙️ How It Works

1. **Input**: A `.CSV` file with PubMed IDs and abstract text.
2. **Preprocessing**: Tokenization, embedding, and batching.
3. **LLM Classification**: Prompts are sent to Mixtral via local API.
4. **Postprocessing**: Answers are stored in `.CSV` and `.db` formats.
5. **Exploratory Analysis**: Vector clustering and label refinement.

---

## 🧪 Research Context

This tool was developed in the context of translational AI for public health research, aiming to:
- Streamline evidence extraction from high-volume literature.
- Identify novel therapeutic strategies and resistance patterns.
- Support systematic reviews and pharmacoepidemiological monitoring.

---

## 🗂️ File Structure

