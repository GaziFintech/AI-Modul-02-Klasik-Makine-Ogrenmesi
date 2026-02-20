# 🤖 AI Modül 2: Klasik Makine Öğrenmesi

Veriyi temizlemeyi ve görselleştirmeyi öğrendik; şimdi ise o verinin içindeki gizli desenleri bulma ve geleceği tahmin etme zamanı! Bu modül, makine öğrenmesinin temel taşlarını, regresyon ve sınıflandırma problemlerini, topluluk yöntemlerini (ensemble) ve denetimsiz öğrenme algoritmalarını kapsar.

> **Gazi FinTech olarak odak noktamız:** "Bir algoritmayı sadece `fit()` ve `predict()` ile çalıştırmak değil, arkasındaki matematiği anlamaktır."

---

## 📅 6 Haftalık Eğitim Programı

### 🔹 1. & 2. Hafta: ML Temelleri ve Regresyon
* **Kavramlar:** Bias-Variance Tradeoff, Overfitting/Underfitting, Cross-Validation.
* **Lineer Regresyon:** Least Squares matematiği ve Sıfırdan Python Implementasyonu.
* **Regularization:** Ridge, Lasso ve Elastic Net mantığı.
* **Lojistik Regresyon:** Sigmoid fonksiyonu ve Multi-class classification.

### 🔹 3. Hafta: Sınıflandırma Algoritmaları
* **k-NN:** Mesafe metrikleri ve komşuluk algoritması.
* **Karar Ağaçları (Decision Trees):** Entropy, Gini Impurity ve Information Gain.
* **SVM & Naive Bayes:** Hyperplane mantığı ve Bayes Teoremi uygulamaları.

### 🔹 4. Hafta: Ensemble Methods (Topluluk Öğrenmesi)
* **Bagging:** Random Forest algoritması ve Feature Importance.
* **Boosting:** AdaBoost, Gradient Boosting, XGBoost ve LightGBM kullanımı.

### 🔹 5. Hafta: Denetimsiz Öğrenme (Unsupervised)
* **Clustering:** K-means (sıfırdan implementasyon) ve Hierarchical Clustering.
* **Boyut Azaltma:** PCA (Principal Component Analysis) matematiği ve görselleştirme.

### 🔹 6. Hafta: Model Değerlendirme ve Kaggle
* **Metrikler:** Confusion Matrix, Precision, Recall, F1-Score ve ROC-AUC.
* **Tuning:** Grid Search ve Random Search ile hiperparametre optimizasyonu.
* **Uygulama:** Titanic veya Ev Fiyatları tahmini gibi uçtan uca Kaggle projeleri.

---

## 📐 Matematiksel Odak: "From Scratch"

Bu modülde aşağıdaki algoritmaların en az bir kez hiçbir ML kütüphanesi (Scikit-learn vb.) kullanmadan sadece **NumPy** ve temel **Python** ile kodlanması beklenmektedir:
1. **Lineer Regresyon** (Gradient Descent ile)
2. **Lojistik Regresyon**
3. **K-Means Clustering**

---

## 🚀 Görevler ve Teslimat

| Konu | Proje Görevi |
| :--- | :--- |
| **Regresyon** | Bir finansal veri seti (Örn: Borsa İstanbul hisse verisi) üzerinden fiyat tahmini. |
| **Sınıflandırma** | Kredi kartı dolandırıcılığı (Fraud Detection) tespiti veya Müşteri Terk (Churn) analizi. |
| **Clustering** | Hisse senetlerini risk/getiri profillerine göre gruplandırma. |
| **Final** | Seçilen bir Kaggle veri setinde en iyi modelin (XGBoost/Random Forest vb.) kurulması. |

### 📥 Teslim Süreci
* Çalışmalarını `submissions/Ad-Soyad/` klasörüne ekle.
* PR açarken hangi algoritmayı **"sıfırdan"** yazdığını mutlaka belirt.
* 📖 *Kılavuz: Pull Request Rehberi*

---

## 🛠️ Kurulum ve Gereksinimler

Bu modül için Scikit-learn kütüphanesi temel aracımız olacaktır:

```bash
pip install scikit-learn scipy statsmodels
```
---

## 💡 FinTech Bağlantısı

Makine öğrenmesi finans dünyasında; **kredi skorlama, algoritmik işlem stratejileri, risk yönetimi ve pazar segmentasyonu** gibi alanlarda kritik rol oynar. Bu modülde yaptığımız projeler, bu gerçek dünya sorunlarına çözüm üretmeyi hedefler.

---

> "Algoritmayı kullanan değil, algoritmayı anlayan ve yöneten kazanır."

**[Gazi Finansal Teknolojiler Topluluğu]**
