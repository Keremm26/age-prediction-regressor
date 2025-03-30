# 🧠 Age Prediction Regressor from Speech

This repository contains a regression pipeline that estimates a speaker's age based on acoustic and linguistic features extracted from their speech recordings.

The model utilizes traditional machine learning techniques, with a focus on **Gradient Boosting** and **Random Forest Regressor**, to capture relevant speech characteristics for age estimation.

---

## 📂 Project Structure

- `age_regressor.ipynb` – Jupyter Notebook with the full pipeline: data loading, preprocessing, modeling, evaluation, and visualizations.
- `report.pdf` – Technical report summarizing the methodology, experiments, and results.
- Key visualizations:
  - `heatmap.png`
  - `learning_rate.png`
  - `outlier.png`
  - `XGboost.jpg`

---

## Objective

Predict the **age** of a speaker based on extracted features such as:

- Jitter
- Shimmer
- Zero Crossing Rate (ZCR)
- Tempo
- Energy
- Harmonics-to-Noise Ratio (HNR)
- Silence Duration

---

## Future Work

While the current results are promising, several enhancements could be explored:

- **Spectrogram-Based Features**: Extracting advanced temporal and spectral features from audio spectrograms (e.g., harmonic structure, phoneme duration) may provide better input to the model.
- **Deep Learning Models**: Integrating **Convolutional Neural Networks (CNNs)** to process spectrograms as image-like inputs can unlock richer spatial pattern recognition, further improving age prediction.

---

## Visualizations

| Heatmap (Feature Correlation) | RMSE Grid Search (Learning Rate vs Estimators) |
|-------------------------------|--------------------------------------------------|
| ![Heatmap](https://github.com/Keremm26/age-prediction-regressor/blob/main/heatmap.png?raw=true) | ![RMSE Grid](https://github.com/Keremm26/age-prediction-regressor/blob/main/learning_rate.png?raw=true) |

| Pitch Outlier Removal | XGBoost Flow |
|------------------------|--------------|
| ![Outlier](https://github.com/Keremm26/age-prediction-regressor/blob/main/outlier.png?raw=true) | ![XGBoost](https://github.com/Keremm26/age-prediction-regressor/blob/main/XGboost.jpg?raw=true) |

---

## 📁 Dataset

Due to file size limitations, the dataset is not included in this repository. You can request access or receive a download link upon request.

---

## 🛠️ Tech Stack

- Python (Jupyter Notebook)
- Scikit-learn
- XGBoost
- Pandas, NumPy, Matplotlib, Seaborn

---

## 📜 License

MIT License (or choose your preferred one when publishing)

---

## 💡 Author

**Kerem Kose**  
Feel free to connect or raise issues for suggestions and improvements.
