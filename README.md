# Machine Learning Dataset for Double Perovskites (A2B1C1D6)

## 📌 Overview
This repository contains the dataset and code used for machine learning-based property prediction of double perovskite materials with the general formula A2B1C1D6.

The data was retrieved from the Materials Project database using the mp-api and processed into a machine learning-ready format.

---

## 📂 Repository Contents

- `A2B1C1D6_data.csv`  
  → Final dataset used in this study  

- `Double_Perovskites.ipynb`  
  → Google Colab notebook for data extraction and preprocessing  

- `requirements.txt`  
  → Python dependencies required to run the code  

---

## ⚙️ Data Description

The dataset includes the following features:

- Structural properties  
  - lattice parameters (a, b, c)  
  - lattice angles (α, β, γ)  
  - crystal system  
  - space group  

- Physical properties  
  - density  
  - volume  
  - number of sites  

- Electronic properties  
  - band gap  
  - direct/indirect bandgap  

- Thermodynamic properties  
  - energy per atom  
  - formation energy  
  - energy above hull  
  - stability  

- Mechanical properties  
  - bulk modulus  
  - shear modulus  

- Magnetic property  
  - total magnetization  

---

## 🔬 Data Source

Data retrieved from the Materials Project database using the mp-api.

Due to continuous updates in the database, the dataset provided in this repository corresponds exactly to the data used in this study to ensure reproducibility.

---

## ▶️ How to Run

1. Install dependencies:
2. Open the notebook:
3. Add your Materials Project API key:
```python
MPRester("YOUR_API_KEY")

