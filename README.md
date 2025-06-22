# Kredi Kartı Onayı Tahmini | Credit Card Approval Prediction
## Ölçeklendirme, Genetik Algoritma ve PCA Karşılaştırmalı Yaklaşım | Comparative Analysis with Scaling, Genetic Algorithm and PCA

## 🇹🇷 Proje Açıklaması

Bu projede, bireylerin demografik, mesleki ve finansal özellikleri kullanılarak kredi kartı başvuru sonuçlarını (onay/ret) tahmin eden bir sınıflandırma sistemi geliştirilmiştir. Veri seti Kaggle platformundan alınmıştır [(https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction)](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction) .

### 🚀 Hedef:
- Kredi başvurularının onay/ret durumunu doğru şekilde tahmin etmek
- Farklı ölçekleme tekniklerini (MinMaxScaler, StandardScaler) karşılaştırmak
- Genetik Algoritma (GA) ve PCA ile öznitelik azaltma yaklaşımlarının performansa etkisini analiz etmek

### ⚙️ Kullanılan Yaklaşımlar:
1. **Geleneksel Modelleme:** Tüm özniteliklerle, yalnızca ölçekleme yapılmış haliyle modelleme
2. **Genetik Algoritma (GA):** Rastgele orman temelli öznitelik seçimi ile optimize edilmiş modelleme
3. **PCA:** Temel Bileşenler Analizi ile boyut indirgeme uygulanan modelleme

### 📊 Kullanılan Algoritmalar:
- K-Nearest Neighbors (KNN)
- Random Forest (RF)
- Support Vector Machines (SVM: Linear, RBF, Poly)
- Logistic Regression (LR)
- Decision Tree (DT)
- Multilayer Perceptron (MLP)
- Naive Bayes (NB)

### 📈 Değerlendirme Metrikleri:
- Accuracy, Precision, Recall, F1-Score, Specificity, MCC, ROC-AUC

### 🥇 En Başarılı Kombinasyon:
📌 **MinMaxScaler + PCA + KNN** →  
`Accuracy: %98.47`, `F1-Score: 0.9845`, `Specificity: %99.33`

## 🇬🇧 Project Description

This project aims to build a classification system that predicts credit card application results (approval/rejection) based on demographic, financial, and occupational attributes. The dataset is obtained from Kaggle.

### 🚀 Goal:
- Predict credit card approval outcomes accurately
- Compare the impact of scaling techniques (MinMaxScaler, StandardScaler)
- Analyze the effect of Genetic Algorithm (GA) and PCA on model performance

### ⚙️ Modeling Strategies:
1. **Traditional Modeling:** All features with scaling only
2. **Genetic Algorithm (GA):** Feature selection via Random Forest-based GA
3. **PCA:** Dimensionality reduction using Principal Component Analysis

### 📊 Algorithms Used:
- K-Nearest Neighbors (KNN)
- Random Forest (RF)
- Support Vector Machines (SVM: Linear, RBF, Poly)
- Logistic Regression (LR)
- Decision Tree (DT)
- Multilayer Perceptron (MLP)
- Naive Bayes (NB)

### 📈 Evaluation Metrics:
- Accuracy, Precision, Recall, F1-Score, Specificity, MCC, ROC-AUC

### 🥇 Best Performing Combination:
📌 **MinMaxScaler + PCA + KNN** →  
`Accuracy: 98.47%`, `F1-Score: 0.9845`, `Specificity: 99.33%`
