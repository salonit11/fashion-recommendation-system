# Fashion Recommendation System

## 📌 Project Overview
This project leverages **transfer learning** on the **ImageNet** dataset to build a **fashion recommendation system**. The model is trained on a **Kaggle dataset** and is deployed as a web application using **Streamlit**.

## 🚀 Features
- Uses **ResNet (Transfer Learning)** for feature extraction and classification.
- Trained on a **fashion dataset** from Kaggle.
- Provides personalized fashion recommendations based on input images.
- Deployed as a **Streamlit web app** for easy interaction.

## 📂 Dataset
- The dataset consists of images of different clothing categories.
- Preprocessed for training and validation using **image augmentation techniques**.

## 🔧 Tech Stack
- **Framework**: TensorFlow/Keras
- **Model**: ResNet (Pretrained on ImageNet)
- **Web App**: Streamlit
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

## 🔍 Implementation Steps
1. **Data Preprocessing**: Image resizing, augmentation, and normalization.
2. **Model Training**: Using **ResNet** as a feature extractor and training on the fashion dataset.
3. **Evaluation**: Model validation using accuracy and loss metrics.
4. **Deployment**: Building a **Streamlit web app** for recommendations.

## 💡 How to Run
1. Clone the repository:
   ```bash
   git clone <repo-link>
   cd fashion-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

## 📊 Results
- Achieved **high accuracy** in clothing classification.
- Successfully provides **relevant fashion recommendations**.

## 🔮 Future Scope
- Improve recommendations using **content-based filtering**.
- Experiment with **Vision Transformers (ViTs)**.
- Deploy on **cloud platforms** for scalability.

## 📌 Contributors
- **Saloni Trivedi** - AI/ML Enthusiast | Web App Developer

