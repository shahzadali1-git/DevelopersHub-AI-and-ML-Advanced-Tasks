# House Price Prediction - Multimodal Deep Learning

This repository contains a neural network capable of predicting house prices by merging two different types of data (Multimodal).

## 🧠 Model Overview
The architecture consists of a **Dual-Stream Network**:
- **Branch 1 (MLP):** Handles tabular data (Bedrooms, Bathrooms, Area).
- **Branch 2 (CNN):** Processes house images to identify visual quality/style.
- **Fusion:** The branches are concatenated to produce a single price estimate.



## 📈 Performance
- **Dataset Size:** 535 Houses
- **Input Size:** 64x64 RGB Images
- **Final Mean Absolute Error (MAE):** $308,780.87
- **Epochs:** 20

## 🛠️ How to Run
1. Activate environment: `.\venv\Scripts\activate`
2. Install requirements: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook`