# 🔬 Google DeepMind - Master’s Degree Research Repository

# ☀️ Solar Energy Forecasting - UNICAMP Gymnasium

## 📌 Overview
This repository contains the implementation and results of a research study conducted at **UNICAMP** under the **Google DeepMind Scholarship** for the **São Paulo Center for Energy Transition Studies (CPTEn)**.  

The study analyzed **time series data** from the **photovoltaic energy plant** at the **Multidisciplinary Gymnasium (GMU-PV)**. The research focused on:  

✅ Identifying **patterns** in energy production  
✅ Developing **forecasting models**   
✅ Implementing **fault detection** techniques  
✅ Using **advanced Machine Learning & Deep Learning**   

---

## 📊 Performance Comparison
The table below presents the performance of different forecasting architectures:  

| Model | R² | MAE | MSE | RMSE | MAPE |
|-------------|------|------|------|------|------|
| [CNN](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_CNN.ipynb) | 0.947 | 5.638 | 60.109 | 7.753 | 0.109 |
| [AutoML](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_AutoML.ipynb) | 0.935 | 6.318 | 73.302 | 8.562 | 0.127 |
| [LSTM](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_LSTM.ipynb) | 0.934 | 6.854 | 75.283 | 8.677 | 0.117 |
| [Transformer](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_Transformer.ipynb) | 0.934 | 6.360 | 75.470 | 8.687 | 0.140 |
| [Conformal Prediction](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_Mapie.ipynb) | 0.925 | 6.755 | 85.191 | 9.230 | 0.122 |

As a result, the research achieved a 15% reduction in the cost of contracted energy.

![CNN Prediction](https://github.com/GLEYSONRN/mastersdegree/blob/main/cnn.svg)
![Anual Forecasting](https://github.com/GLEYSONRN/mastersdegree/blob/main/forecast.svg)
---

## 📄 Published Paper  
This research led to the publication of the following paper:  

📌 **[Solar Energy Forecasting: Case Study of the UNICAMP Gymnasium](https://link.springer.com/chapter/10.1007/978-3-031-48652-4_7)**  

### 📚 Citation (BibTeX):
```bibtex
@InProceedings{10.1007/978-3-031-48652-4_7,
author="do Nascimento, Gleyson Roberto
and J{'u}nior, Hildo Guillardi
and Attux, Romis",
editor="J{\o}rgensen, Bo N{\o}rregaard
and da Silva, Luiz Carlos Pereira
and Ma, Zheng",
title="Solar Energy Forecasting: Case Study of the UNICAMP Gymnasium",
booktitle="Energy Informatics",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="92--107",
abstract="Within the spectrum of studies conducted by the S{\~a}o Paulo Center for Energy Transition Studies (CPTEn), time series from the Photovoltaic Energy Plant of the UNICAMP Multidisciplinary Gymnasium (GMU-PV) were analyzed. This plant is associated with the first implementation of a photovoltaic system in the context of the Sustainable Campus Project (PCS) at UNICAMP - as a consequence, it originated the most extensive and robust time series in the project.",
isbn="978-3-031-48652-4"
}
```

---

## 🛠️ How to Use This Repository  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/GLEYSONRN/mastersdegree.git
cd mastersdegree
```

### 2️⃣ Install Dependencies  
Ensure you have **Python** installed along with the necessary libraries.  
```sh
pip install -r requirements.txt
```

### 3️⃣ Running Notebooks  
Launch **Jupyter Notebook** and run the corresponding model:  
```sh
jupyter notebook
```
Select one of the following notebooks:  
🚀 **Best Model** → `CPTEn_CNN.ipynb`  
📊 `CPTEn_AutoML.ipynb`  
📉 `CPTEn_LSTM.ipynb`  
🔍 `CPTEn_Transformer.ipynb`  
⚡ `CPTEn_Mapie.ipynb`  

### 4️⃣ Analyzing Results  
Each notebook contains **detailed steps** for training, evaluation, and visualization of results 📊🔎.

---

## ❓ Need Help?  
For any issues, feel free to open an [❗issue](https://github.com/GLEYSONRN/mastersdegree/issues) or contribute via a [🔄 pull request](https://github.com/GLEYSONRN/mastersdegree/pulls).

---

**Google DeepMind Research | UNICAMP | Energy Transition** 🌍
