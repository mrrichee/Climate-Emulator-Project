# Climate-Emulator-Project
“ConvLSTM-based emulator for NorESM2-LM (2015–2025) climate data”
# 🌍 Climate Emulator — NorESM2-LM (2015–2025)

This repository reproduces a mini version of the ClimateSet project using NorESM2-LM climate model data.

## 🔧 Features
- Extracts and preprocesses CO₂, CH₄, SO₂, BC emissions
- Generates Temperature and Precipitation outputs
- Builds unified 4-input 2-output dataset (2015–2025)
- Trains ConvLSTM climate emulator (CPU-friendly)
- Produces spatial RMSE maps and visual diagnostics

## 🧠 Model
Uses a simple ConvLSTM architecture to emulate future monthly climate fields.

## 📂 Structure
Climate_Emulator_4in2out_NorESM2_LM.ipynb
requirements.txt
RMSE_maps_2015_2025.nc
Temperature_RMSE.png
Precipitation_RMSE.png


## 🧑‍💻 Author
Created by **Richee (Saksham Shukla)** as part of ML Climate Modeling coursework.

