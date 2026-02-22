# 🤖 AI Modül 2: Klasik Makine Öğrenmesi

Veriyi temizlemeyi ve görselleştirmeyi öğrendik; şimdi ise o verinin içindeki gizli desenleri bulma ve geleceği tahmin etme zamanı! Bu modül, makine öğrenmesinin temel taşlarını, regresyon ve sınıflandırma problemlerini, topluluk yöntemlerini (ensemble) ve denetimsiz öğrenme algoritmalarını kapsar.

> **Gazi FinTech olarak odak noktamız:** "Bir algoritmayı sadece `fit()` ve `predict()` ile çalıştırmak değil, arkasındaki matematiği anlamaktır."

---


### 🔹 5. Bölüm: Makine Öğrenmesi Temelleri ve Ön İşleme
* **Temel Kavramlar:** Denetimli ve Denetimsiz öğrenme, regresyon vs. sınıflandırma farkları.
* **Model Performansı:** Aşırı öğrenme (Overfitting), az öğrenme (Underfitting) ve Bias-Variance dengesi.
* **Doğrulama:** Veri seti bölme (Train/Test) ve Çapraz Doğrulama (Cross-Validation) teknikleri.
* **Veri Ön İşleme:** Ölçeklendirme (Scaling), Kategorik kodlama (Encoding) ve Özellik seçimi.
---
### 🔹 6. Bölüm: Denetimli Öğrenme - Regresyon
* **Lineer Regresyon:** En küçük kareler yöntemi, Gradient Descent ve model metrikleri ($MSE$, $R^2$).
* **Polinomial Regresyon:** Doğrusal olmayan ilişkiler ve özellik dönüşümü.
* **Düzenlileştirme (Regularization):** Lasso ($L_1$), Ridge ($L_2$) ve Elastic Net yöntemleri.
* **Lojistik Regresyon:** Sigmoid fonksiyonu, sınıflandırma mantığı ve Multi-class yaklaşımı.
---
### 🔹 7. Bölüm: Denetimli Öğrenme - Sınıflandırma
* **Mesafe ve Ağaç Tabanlı Modeller:** k-NN (Mesafe metrikleri) ve Karar Ağaçları (Entropi, Gini).
* **Destek Vektör Makineleri (SVM):** Hiper düzlemler, destek vektörleri ve Kernel Trick.
* **Olasılıksal Modeller:** Naive Bayes teoremi ve varyasyonları (Gaussian, Bernoulli).
* **Model Optimizasyonu:** Budama (Pruning) ve boyut laneti ile mücadele.
---
### 🔹 8. Bölüm: Topluluk Yöntemleri (Ensemble Methods)
* **Bagging:** Bootstrap Sampling ve Random Forest algoritması.
* **Boosting:** AdaBoost, Gradient Boosting ve modern kütüphaneler (XGBoost, LightGBM, CatBoost).
* **Analiz:** Özellik önem sırası (Feature Importance) hesaplama teknikleri.
---
### 🔹 9. Bölüm: Denetimsiz Öğrenme (Unsupervised)
* **Kümeleme (Clustering):** K-means (Elbow metodu), Hiyerarşik kümeleme ve DBSCAN.
* **Boyut Azaltma:** Temel Bileşen Analizi (PCA), SVD ve t-SNE ile görselleştirme.
* **Performans:** Silhouette skoru ve küme geçerlilik analizleri.
---
### 🔹 10. Bölüm: Model Değerlendirme ve Seçimi
* **Sınıflandırma Metrikleri:** Hata matrisi (Confusion Matrix), Hassasiyet, Duyarlılık ve F1-Skor.
* **Eğri Analizleri:** ROC Eğrisi ve AUC (Alan ölçümü) değerleri.
* **Hiperparametre Ayarlama:** Grid Search ve Random Search stratejileri.
* **Öğrenme Eğrileri:** Modelin veri miktaruna tepkisini analiz etme.
---

### 🔹 11. Bölüm: Denetimsiz Öğrenme (Unsupervised Learning)
* **Kümeleme (Clustering):** K-means (Elbow metodu), Hiyerarşik kümeleme (Dendrogram) ve yoğunluk tabanlı DBSCAN.
* **Boyut Azaltma:** Temel Bileşen Analizi (PCA), Tekil Değer Ayrışımı (SVD) ve t-SNE ile görselleştirme.
* **Matematiksel Temel:** Özdeğer (Eigenvalue) ve Özvektör (Eigenvector) ayrışımı.
* **Performans Analizi:** Silhouette skoru ile küme kalitesinin ölçülmesi.

---

### 🔹 12. Bölüm: Model Değerlendirme ve Seçimi
* **Sınıflandırma Metrikleri:** Hata Matrisi (Confusion Matrix), Accuracy, Precision, Recall ve F1-Score.
* **Gelişmiş Analiz:** ROC Eğrisi ve AUC (Area Under Curve) hesaplamaları.
* **Hiperparametre Optimizasyonu:** Grid Search ve Random Search stratejileri.
* **Model Tanılama:** Öğrenme Eğrileri (Learning Curves) ve hiperparametre ayarlama (Tuning) teknikleri.
---


## 📚 Öğrenim Kaynakları

Öğrenirken kullanabileceğiniz tavsiye edilen kaynaklar:
* 🎥 **Ayrıntılı Kaynak Listesi:** [Kaynak Matrisi](https://github.com/GaziFintech/AI-YapayZeka-Egitimi/blob/main/Mufredat(curriculum)/module-2-details.md)
* 📖 **Dokümantasyon:** [Resmi Scikit-Learn Dokümanları](https://scikit-learn.org/stable/user_guide.html)
* 📑 **Cheat Sheets:** Repo içindeki `resources/` klasörüne göz atın.



## 🚀 Alıştırmalar, Ödevler ve Proje Teslimi

Her hafta veya ana konu bitiminde yapman gereken mini projeler aşağıdadır:


| No | Konu Başlığı | Codewars | HackerRank | LeetCode | Ödev | 
|:---|:---|:---|:---|:---|:---|
| **6.1 & 7.1** | Makine Öğrenmesi Temel Kavramları | [![Codewars](https://img.shields.io/badge/Codewars-B1361E?logo=codewars&logoColor=fff)](https://www.codewars.com/kata/56efab15740d301ab40002ee) | [![HackerRank](https://img.shields.io/badge/-HackerRank-%232EC866?style=for-the-badge&logo=HackerRank&logoColor=white)](https://www.hackerrank.com/domains/ai?filters%5Bsubdomains%5D%5B%5D=machine-learning&filters%5Bdifficulty%5D%5B%5D=easy&filters%5Bdifficulty%5D%5B%5D=medium) | [![LeetCode](https://img.shields.io/badge/LeetCode-000000?logo=LeetCode&logoColor=#d16c06)](https://platform.stratascratch.com/coding?code_type=2&job_positions=5) | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/GaziFintech/AI-Modul-02-Klasik-Makine-Ogrenmesi/blob/main/Kaynaklar(resources)/Odevler/6.1%20%26%207.1.md) |  
| **7.2** | Veri Ön İşleme (Preprocessing) | [![Codewars](https://img.shields.io/badge/Codewars-B1361E?logo=codewars&logoColor=fff)](https://www.codewars.com/kata/5695995cc26a1e90fe00004d) | [![HackerRank](https://img.shields.io/badge/-HackerRank-%232EC866?style=for-the-badge&logo=HackerRank&logoColor=white)](https://www.hackerrank.com/domains/ai?filters%5Bsubdomains%5D%5B%5D=machine-learning&filters%5Bdifficulty%5D%5B%5D=hard) | [![LeetCode](https://img.shields.io/badge/LeetCode-000000?logo=LeetCode&logoColor=#d16c06)](https://platform.stratascratch.com/coding?code_type=2&job_positions=5&difficulties=3) | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/GaziFintech/AI-Modul-02-Klasik-Makine-Ogrenmesi/blob/main/Kaynaklar(resources)/Odevler/7.2.md) |  
| **8.1** | Lineer Regresyon | [Link] | [Link] | [Link] | [Link] |
| **8.2** | Polinomial Regresyon | [Link] | [Link] | [Link] | [Link] |  
| **8.3** | Regularization (Düzenlileştirme) | [Link] | [Link] | [Link] | [Link] |
| **8.4** | Lojistik Regresyon (Sınıflandırma Temelli) | [Link] | [Link] | [Link] | [Link] |
| **9.1** | k-Nearest Neighbors (k-NN) | [Link] | [Link] | [Link] | [Link] |  
| **9.2** | Karar Ağaçları (Decision Trees) | [Link] | [Link] | [Link] | [Link] |
| **9.3** | Support Vector Machines (SVM) | [Link] | [Link] | [Link] | [Link] |  
| **9.4** | Naive Bayes | [Link] | [Link] | [Link] | [Link] |
| **10.1** | Bagging ve Random Forest | [Link] | [Link] | [Link] | [Link] |
| **10.2** | Boosting | [Link] | [Link] | [Link] | [Link] |
| **11.1** | Kümeleme (Clustering) | [Link] | [Link] | [Link] | [Link] |
| **11.2** | Boyut Azaltma (Dimensionality Reduction) | [Link] | [Link] | [Link] | [Link] |
| **12.1** | Değerlendirme Metrikleri | [Link] | [Link] | [Link] | [Link] |
| **12.2** | Model Seçimi ve Hiperparametre Optimizasyonu | [Link] | [Link] | [Link] | [Link] |
---

### 📥 Nasıl Teslim Ederim?
1. Bu depoyu **Fork** et.
2. Kendi isminle bir **Branch** oluştur.
3. Çalışmalarını `submissions/Ad-Soyad/` klasörüne yükle.
4. **Pull Request** açarak liderine onaya gönder.
   > *Detaylı anlatım için: Ana Rehberdeki [github-setup.md](./Rehberler(Guides)/github-setup.md) dosyasını oku.*



## 🛠️ Kurulum ve Gereksinimler

```bash
pip install scikit-learn scipy statsmodels
```

## ❓ Sorun mu Var?

Eğer bir konuda takılırsan:
* Organizasyonun ana sayfasındaki **[Discussions](https://github.com/orgs/GaziFintech/discussions)** kısmından arkadaşlarına ve proje ekibine sorabilirsin.

Eğer teknik bir problem yaşarsan:
* **"New Issue" diyerek** sorunu bizlere ilet.

## 💡 FinTech Bağlantısı

Makine öğrenmesi finans dünyasında; **kredi skorlama, algoritmik işlem stratejileri, risk yönetimi ve pazar segmentasyonu** gibi alanlarda kritik rol oynar. Bu modülde yaptığımız projeler, bu gerçek dünya sorunlarına çözüm üretmeyi hedefler.

> "Algoritmayı kullanan değil, algoritmayı anlayan ve yöneten kazanır."

**Gazi Finansal Teknolojiler Topluluğu - Proje Ekip Lideri Arif Furkan Aytekin**
