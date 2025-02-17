# Google DeepMind - Master’s Degree Research Repository

# Solar Energy Forecasting - UNICAMP Gymnasium

## Overview
This repository contains the implementation and results of a research study conducted at UNICAMP under the Google DeepMind Scholarship for the São Paulo Center for Energy Transition Studies (CPTEn). The study analyzed time series data from the photovoltaic energy plant at the Multidisciplinary Gymnasium (GMU-PV). The research focused on identifying patterns in energy production, developing forecasting models, and implementing fault detection techniques using advanced machine learning and deep learning methodologies.

## Performance Comparison
The table below presents the performance of different forecasting architectures:

| Architecture | MAE | MSE | RMSE | MAPE | R² |
|-------------|-----|-----|------|------|-----|
| [CNN](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_CNN.ipynb) | 5.637886 | 60.108512 | 7.752968 | 0.109488 | 0.947105 |
| [AutoML](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_AutoML.ipynb) | 6.317669 | 73.302349 | 8.561679 | 0.127132 | 0.935494 |
| [LSTM](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_LSTM.ipynb) | 6.854408 | 75.283450 | 8.676604 | 0.117381 | 0.933751 |
| [Transformer](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_Transformer.ipynb) | 6.360488 | 75.470166 | 8.687357 | 0.139891 | 0.933586 |
| [Conformal Prediction](https://github.com/GLEYSONRN/mastersdegree/blob/main/CPTEn_Mapie.ipynb) | 6.754780 | 85.191226 | 9.229909 | 0.121518 | 0.925032 |

## Published Paper
This research led to the publication of the following paper:

**[Solar Energy Forecasting: Case Study of the UNICAMP Gymnasium](https://link.springer.com/chapter/10.1007/978-3-031-48652-4_7)**

### Citation (BibTeX):
```bibtex
@InProceedings{10.1007/978-3-031-48652-4_7,
author="do Nascimento, Gleyson Roberto
and J{\'u}nior, Hildo Guillardi
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

## How to Use This Repository

### 1. Clone the Repository
```sh
git clone https://github.com/GLEYSONRN/mastersdegree.git
cd mastersdegree
```

### 2. Install Dependencies
Ensure you have Python installed along with necessary libraries.
```sh
pip install -r requirements.txt
```

### 3. Running Notebooks
Open Jupyter Notebook and run the corresponding model:
```sh
jupyter notebook
```
Select one of the following:
- `CPTEn_CNN.ipynb` (Best performing model)
- `CPTEn_AutoML.ipynb`
- `CPTEn_LSTM.ipynb`
- `CPTEn_Transformer.ipynb`
- `CPTEn_Mapie.ipynb`

### 4. Analyzing Results
The notebooks contain detailed steps for training, evaluation, and visualization of results.

---
For any issues, feel free to open an [issue](https://github.com/GLEYSONRN/mastersdegree/issues) or contribute via a [pull request](https://github.com/GLEYSONRN/mastersdegree/pulls).
