# 🤖 AI Modül 2: Klasik Makine Öğrenmesi

Veriyi temizlemeyi ve görselleştirmeyi öğrendik; şimdi ise o verinin içindeki gizli desenleri bulma ve geleceği tahmin etme zamanı! Bu modül, makine öğrenmesinin temel taşlarını, regresyon ve sınıflandırma problemlerini, topluluk yöntemlerini (ensemble) ve denetimsiz öğrenme algoritmalarını kapsar.

> **Gazi FinTech olarak odak noktamız:** "Bir algoritmayı sadece `fit()` ve `predict()` ile çalıştırmak değil, arkasındaki matematiği anlamaktır."

---

## 📋 Eğitim İçeriği ve Bölümler

Müfredatın bu aşaması, global numaralandırma sistemindeki 6. bölümden başlar ve 12. bölüme kadar devam eder. Detaylı kaynaklar için [Müfredat Detay Dosyası'na](./module-2-details.md) göz atabilirsiniz.

### 🔹 Bölüm 6: Makine Öğrenmesine Giriş
* **6-1.** Temel Kavramlar (Denetimli vs Denetimsiz Öğrenme, Sınıflandırma vs Regresyon).
* **6-1-4.** Eğitim, doğrulama ve test kümeleri mantığı.
* **6-1-5.** Aşırı öğrenme (Overfitting) ve az öğrenme (Underfitting).
* **6-2.** Basit Makine Öğrenmesi Algoritmaları (Lineer ve Multiple Regresyon Giriş).

### 🔹 Bölüm 7: Makine Öğrenmesi Temelleri
* **7-1.** Bias-Variance Tradeoff ve Cross-validation stratejileri.
* **7-2.** Veri Ön İşleme: Feature scaling (Normalization, Standardization) ve Encoding (One-hot, Label).
* **7-2-4.** Boyut azaltma (Dimensionality Reduction) temel kavramları.

### 🔹 Bölüm 8: Supervised Learning - Regresyon
* **8-1.** Lineer Regresyon: Matematiksel temeller (Least Squares) ve Gradient Descent.
* **8-1-3.** **Sıfırdan (From Scratch) Python implementasyonu.**
* **8-3.** Regularization: Ridge ($L2$), Lasso ($L1$) ve Elastic Net matematiksel altyapısı.
* **8-4.** Lojistik Regresyon: Sigmoid fonksiyonu ve Multi-class classification.

### 🔹 Bölüm 9: Supervised Learning - Sınıflandırma
* **9-1.** k-Nearest Neighbors (k-NN): Mesafe metrikleri ve sıfırdan implementasyon.
* **9-2.** Karar Ağaçları (Decision Trees): Entropy, Gini Impurity ve Information Gain.
* **9-3.** Support Vector Machines (SVM): Hyperplane ve Kernel Trick mantığı.
* **9-4.** Naive Bayes: Bayes Teoremi ve Laplace Smoothing.

### 🔹 Bölüm 10: Ensemble Methods
* **10-1.** Bagging ve Random Forest: Bootstrap sampling ve Feature Importance analizi.
* **10-2.** Boosting: AdaBoost, Gradient Boosting ve XGBoost/LightGBM/CatBoost kullanımı.

### 🔹 Bölüm 11: Unsupervised Learning
* **11-1.** Clustering: K-means (Sıfırdan implementasyon), Hierarchical ve DBSCAN.
* **11-2.** Dimensionality Reduction: PCA (Principal Component Analysis) ve SVD matematiği.

### 🔹 Bölüm 12: Model Değerlendirme ve Seçimi
* **12-1.** Metrikler: Confusion Matrix, Precision, Recall, F1-Score ve ROC-AUC.
* **12-2.** Model Seçimi: Grid Search ve Random Search ile hiperparametre optimizasyonu.

---

## 📐 Matematiksel Odak: "From Scratch"

Bu modülde aşağıdaki algoritmaların en az bir kez hiçbir ML kütüphanesi (Scikit-learn vb.) kullanmadan sadece **NumPy** ve temel **Python** ile kodlanması beklenmektedir:
1. **Lineer Regresyon** (Gradient Descent ile) - *Bölüm 8*
2. **Lojistik Regresyon** - *Bölüm 8*
3. **K-Means Clustering** - *Bölüm 11*

---

## 🚀 Görevler ve Teslimat

| İlgili Bölüm | Proje Görevi |
| :--- | :--- |
| **Bölüm 8** | Finansal veri seti (Örn: BIST verisi) üzerinden fiyat tahmini. |
| **Bölüm 9** | Kredi kartı dolandırıcılığı (Fraud Detection) veya Churn analizi. |
| **Bölüm 11** | Hisse senetlerini risk/getiri profillerine göre gruplandırma. |
| **Bölüm 12** | Kaggle veri setinde en iyi modelin (XGBoost/Random Forest vb.) kurulması. |

### 📥 Teslim Süreci
* Çalışmalarını `submissions/Ad-Soyad/` klasörüne ekle.
* PR açarken hangi algoritmayı **"sıfırdan"** yazdığını mutlaka belirt.
* 📖 [Pull Request Rehberi](../../guides/pull-request-guide.md)

---

## 🛠️ Kurulum ve Gereksinimler

```bash
pip install scikit-learn scipy statsmodels
```

---

## 💡 FinTech Bağlantısı

Makine öğrenmesi finans dünyasında; **kredi skorlama, algoritmik işlem stratejileri, risk yönetimi ve pazar segmentasyonu** gibi alanlarda kritik rol oynar. Bu modülde yaptığımız projeler, bu gerçek dünya sorunlarına çözüm üretmeyi hedefler.

> "Algoritmayı kullanan değil, algoritmayı anlayan ve yöneten kazanır."

**[Gazi Finansal Teknolojiler Topluluğu]**
