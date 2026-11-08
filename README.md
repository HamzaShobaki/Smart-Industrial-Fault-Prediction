# ⚙️ Smart Industrial Fault Prediction

## 📖 Project Overview
Unplanned mechanical breakdowns in industrial manufacturing lines cause severe financial losses and safety hazards. This project builds an automated Smart Industrial Fault Prediction system that monitors real-time telemetry sensors on rotary machinery (such as industrial milling machines) to detect imminent mechanical failures before they occur.

Operating under the Software-Only Track for the IoT Machine Learning course, this system utilizes the UCI AI4I 2020 dataset to predict and classify machine failures.

## 🎯 Objectives & Research Question

**Objective:**
To build, evaluate, and compare an end-to-end machine learning pipeline that handles highly imbalanced industrial telemetry data.

**Research Question:**
Under stratified 5-fold cross-validation on imbalanced industrial sensor data, to what extent do tree-based ensemble models (Random Forest, Gradient Boosting) and RBF-kernel SVMs improve the Macro-F1 score and minority-class Recall compared to a regularized Logistic Regression baseline?

## 📊 Dataset & Features

**Dataset:** UCI AI4I 2020 Predictive Maintenance Dataset  
**Size:** 10,000 instances, 14 columns.

**Input Features:**
* Air temperature [K]
* Process temperature [K]
* Rotational speed [rpm]
* Torque [Nm]
* Tool wear [min]
* Type (Product Quality: L, M, H)

**Target Labels:**
* **Primary:** Machine failure (0 = Normal, 1 = Fault)
* **Diagnostic:** TWF (Tool Wear), HDF (Heat Dissipation), PWF (Power), OSF (Overstrain), RNF (Random).

## 🚀 Current Phase: Phase 1 (Setup & Proposal)

This repository currently reflects the deliverables for Phase 1:
* Problem definition and dataset acquisition.
* Formal project proposal with related works.
* Initial repository setup and exploratory data analysis (EDA).

## 📂 Repository Structure (Phase 1)

```text
├── data/
│   └── ai4i2020.csv               # The main dataset
├── notebooks/
│   └── 01_EDA_and_Setup.ipynb     # Phase 1: Data exploration and initial setup
├── docs/
│   └── Phase_1_Proposal.pdf       # Phase 1: Project Proposal Document
├── requirements.txt               # Project Python dependencies
└── README.md

🛠️ Installation & Setup
To run the Phase 1 notebook, you need to install the required Python libraries. Open your terminal in the project directory and run:

pip install -r requirements.txt






