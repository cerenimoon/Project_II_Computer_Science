# [Project_II_Computer_Science Project - Face Identity Grouping - Yüz Kimliklerinin Gruplanması]

## 📌 Overview - Genel Bakış  
- This repository features deep learning model for grouping face identitites by extracting similar features from facial images.
- Bu kod tabanı, yüz görüntülerinin benzer özniteliklerini çıkararak yüz kimliklerini gruplayan derin öğrenme modeli içermektedir.
<p align="center">
  <img width="1061" height="337" alt="image" src="https://github.com/user-attachments/assets/122adc4e-80b8-44f1-b11f-d915c39e580d" />
</p>

## 🚀 Key Features - Anahtar Özellikler
- **Custom Model Training - Özel Model Eğitimi:** Fine-tuned VGG16 architecture using Transfer Learning for extracting similar features from facial images and used algorithms such as (K-Nearest Neighbor) for grouping similar facial features.
VGG16 mimarisi veri setine (LFW) uyarlanarak yüz görüntülerinden benzer öznitelikler çıkarılmıştır ve K-En Yakın Komşuluk (KNN) gibi algoritmalar kullanılarak benzer yüz öznitelikleri gruplanmıştır. 
- **Data Science - Veri Bilimi:**  Image preprocessing are realized though compression and reshaping. Model weight distributions are used.
Yüz görüntüleri sıkıştırılmıştır ve boyutlandırılmıştır. Model ağırlık dağılımları kullanılmıştır. 
  
## 🛠️ Tech Stack & Architecture - Teknik Özellikler ve Mimari
- **Code Area - Kod Alanı:** Python
- **AI / Deep Learning - Yapay Zeka / Derin Öğrenme:** Keras / Tensorflow, Scikit-learn
- **Model Architecture - Model Mimarisi:** Transfer Learning - VGG16
  <p align="center">
    <img width="45%"  alt="image" src="https://github.com/user-attachments/assets/12aba2d8-de61-42d6-a54d-9d46c294ffeb" />
  </p>
- **Algorithms - Algoritmalar:** KNN, 
- **DevOps / Infrastructure - Geliştirme / Altyapı:** Google Notebooks, Jupyter Notebook, Git, Github

## 📊 Performance Metrics & Results - Performans Metrikleri ve Sonuçlar 
- **Cluster Number - Küme Sayısı:** With usage of KMeans (K-Nearest Neighbor based algorithm), cluster numbers affect the accuracy of facial image grouping. 
KMeans algoritmasının kullanımıyla (K-Nearest Neighbor tabanlı algoritma), küme sayısı yüz görüntülerinin gruplama doğruluğunu etkilemektedir. 
<p align="center">
  <img width="56%" alt="image" src="https://github.com/user-attachments/assets/bdffceb9-a5ba-4e1f-a3b2-5fd6ff83454e" />
  <br>
  <em>k=2 optimal cluster number for LFW Transfer Learning Model - LFW Transfer Learning modeli için optimum küme sayısı</em>
</p>

<p align="center">
  <img width="56%" alt="image" src="https://github.com/user-attachments/assets/06e52cba-8e4a-48eb-97a4-2e00e4861c55" />
  <br>
  <em>k=5 cluster number for LFW Transfer Learning Model - LFW Transfer Learning modeli için küme sayısı</em>
</p>

