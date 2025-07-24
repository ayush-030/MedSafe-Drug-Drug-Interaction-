# 💊 MedSafe (AI-Based Drug-Drug Interaction Detection)

**MedSafe** is an intelligent drug-drug interaction (DDI) prediction system that leverages machine learning and cheminformatics to detect harmful interactions between pharmaceutical compounds. By analyzing molecular fingerprints derived from SMILES representations, MedSafe helps healthcare professionals and researchers ensure safer drug combinations.

---


**🔗 Live Demo:** [https://drug-drug-interaction.onrender.com](https://drug-drug-interaction.onrender.com)

---

## 🚀 Features

- 🔬 Predicts drug-drug interactions using similarity-based machine learning models
- 🧪 Uses molecular fingerprints and clustering to analyze chemical properties
- 🌐 Optionally integrates with PubChem API to fetch real-time SMILES data
- 📈 High accuracy with minimal computational cost
- 🛡️ Designed to enhance prescription safety and prevent adverse drug events

---

## 🧪 Test the Model With These Drugs

You can test the model by inputting pairs of the following drug names (or fetch their SMILES using APIs):

- **Atenolol**
- **Phenytoin**
- **Xanthine**
- **Omeprazole**
- **Clopidogrel**
- **Warfarin**

> Example usage:
> ```
> Input Drug 1: Warfarin
> Input Drug 2: Phenytoin
> → Output: High Risk Interaction Detected
> ```

---
## 🛠️ **Tech Stack**  
- **Backend:** Python, Flask  
- **Database:** MongoDB  
- **Frontend:** HTML/CSS/JavaScript (Flask-based)  
- **Deployment:** Render  
- **Data Sources:** DrugBank, PubChem

---

## 🧠 Model Overview

- **Input**: SMILES strings of two drugs
- **Processing**:
  - Convert SMILES to Morgan fingerprints
  - Compute similarity matrix using cosine distance
  - Apply unsupervised clustering to group interactions
- **Output**: Risk category (e.g., *Low, Moderate, High*)

---

## ⚙️ Installation & Running

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/medsafe.git
   cd medsafe

