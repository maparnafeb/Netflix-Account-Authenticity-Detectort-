# 📸 Instagram Fake, Spammer & Genuine Account Detection (ML Project)

This project uses Machine Learning to classify Instagram accounts as **Fake**, **Spammer**, or **Genuine** based on profile and activity data. It helps platforms and analysts detect inauthentic behavior on social media using structured data and intelligent models.

---

## 📊 Problem Statement

Social media platforms like Instagram face an increasing number of **fake** and **spam** accounts that can spread misinformation, manipulate trends, and impact real users' experience. Manual detection is not scalable.

This project aims to:
- **Classify Instagram accounts** into `Fake`, `Spammer`, and `Genuine`
- Use **machine learning** models to automate this detection
- Identify key patterns in user behavior

---

## 🎯 Project Objectives

- 📥 Load and preprocess Instagram account data (train/test)
- 📊 Perform EDA (Exploratory Data Analysis)
- 🧠 Train classification models (Random Forest, XGBoost)
- 📈 Evaluate model performance
- 🔍 Identify important features (e.g., followers/following ratio, bio, profile pic)

---

## 📁 Dataset

The dataset contains the following columns:
- `Followers`, `Following`, `Posts`, etc.
- `Bio`, `Profile Pic` (binary/categorical)
- `Label` – the target: `Fake`, `Spammer`, or `Genuine`

Split into:
- `train.csv`
- `test.csv`

---

## 🧠 Models Used

- ✅ Random Forest Classifier
- ✅ XGBoost Classifier
- ⚙️ Label Encoding & Feature Scaling with StandardScaler

---

## 📈 Results

- Achieved good classification accuracy (varies by model)
- Random Forest & XGBoost performed best
- Top features: `Follower-Following Ratio`, `Has Profile Pic`, `Has Bio`, `Post Count`

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- XGBoost

---

## 🔮 Future Enhancements

- Deploy model via Streamlit or Flask as a web app
- Add deep learning model using TensorFlow/Keras
- Handle live Instagram data using APIs
- Build a dashboard for moderators

