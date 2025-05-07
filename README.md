# 🚭 Smoking Status Prediction using Machine Learning

## 📌 Objective

Smoking is a major contributor to preventable diseases and deaths. This project aims to:
- Predict an individual's smoking status using physiological and psychological features.
- Assist healthcare professionals in assessing the likelihood of successful smoking cessation.

---

## 📁 Project Files
.
├── exploratory.ipynb     # Exploratory Data Analysis (EDA) draft
├── explanatory.ipynb     # Cleaned final analysis for reporting
├── testing.ipynb         # Feature engineering, modeling, evaluation
├── generate_data.py      # Script to generate dataset variant
├── README.md             # Project overview and documentation
🔍 Analysis & Methodology
🧪 1. Data Analysis
Univariate Analysis: Understanding feature distributions.

Bivariate Analysis: Studying pairwise relationships.

Multivariate Analysis: Identifying high-dimensional interactions.

🛠️ 2. Feature Engineering
Outlier detection and removal

Normalization (Min-Max Scaling, Standardization)

Feature transformation and selection

🤖 3. Ensemble Methods
Implemented and compared:

BaggingClassifier

AdaBoostClassifier

RandomForestClassifier

🔧 4. Hyperparameter Tuning
Used:

GridSearchCV for fine-tuning ensemble models

🧠 5. Final System
Trained on a train/validation/test split

Evaluated using accuracy, precision, recall, and F1-score

📊 Visualization Tools
matplotlib

seaborn

Clear and informative plots: histograms, boxplots, heatmaps, scatterplots

📌 How to Use
Clone the repo:
git clone https://github.com/<your-username>/smoking-status-prediction.git
cd smoking-status-prediction
Install required packages:
pip install numpy pandas matplotlib seaborn scikit-learn
Run the notebooks in the following order:
generate_data.py to generate the dataset

exploratory.ipynb

explanatory.ipynb

testing.ipynb
## Author:
@MohamedSobhy
