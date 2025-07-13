# BlueTide

# 🌊 BlueTide – Marine Exploration & Conservation Platform

**BlueTide** is a machine learning-based platform designed to support marine research, exploration, and conservation. This academic project leverages computer vision and predictive models to analyze sea animal images, environmental data, and diving site information to provide actionable insights for marine enthusiasts, researchers, and divers.

## 🔍 Project Overview

BlueTide is divided into three core modules:

1. **Sea Animal Classification**  
   - Uses deep learning (CNNs like EfficientNetB7 and ResNet50) to classify sea animals from images.
2. **Marine Environment Prediction**  
   - Predicts environmental factors such as water temperature, pollution level, and coral safety using Random Forest.
3. **Dive Site Clustering**  
   - Applies K-Means clustering on dive log and shipwreck data to identify optimal diving zones.

The system promotes sustainable marine practices, assists marine researchers, and informs tourists/divers with reliable sea-related insights.

---

## 🧠 Technologies Used

- **Languages**: Python, SQL
- **Machine Learning Models**: CNNs (EfficientNetB7, ResNet50), Random Forest, K-Means Clustering
- **Libraries**: TensorFlow, scikit-learn, OpenCV, Pandas, Seaborn, Matplotlib
- **Tools**: Google Colab, Kaggle, Jupyter Notebook
- **Deployment**: Flask API (optional), Flutter frontend (optional)

---

## 📁 Project Structure

```bash
BlueTide/
├── data/
│   ├── sea_animals/ (image dataset)
│   ├── environment.csv
│   └── dive_logs.csv
├── notebooks/
│   ├── 1_sea_animal_classification.ipynb
│   ├── 2_environment_prediction.ipynb
│   └── 3_dive_site_clustering.ipynb
├── models/
├── outputs/
├── README.md
└── requirements.txt
