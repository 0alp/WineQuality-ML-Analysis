# 🍷 WineQuality-ML-Analysis

- WineQuality-ML-Analysis, makine öğrenmesi algoritmaları kullanılarak kırmızı şarap kalitesinin tahmin edilmesini amaçlayan bir analiz çalışmasıdır.
- Veri seti, UCI Wine Quality veri setinden alınmış olup, farklı makine öğrenmesi modellerinin performanslarını karşılaştırmak için kullanılmıştır.

⚠️ Önemli Not:

- Bu proje tamamen bir deneme ve öğrenme çalışmasıdır.
- Elde edilen analiz ve tahmin sonuçları bilimsel doğruluk garantisi vermez.
- Gerçek dünyada şarap kalitesini belirlemek için profesyonel değerlendirme ve kimyasal analizler gereklidir.

---
## 📌 Kullanılan Veri Seti
- Veri Kaynağı: UCI Wine Quality Dataset
- İçerik: Kırmızı ve beyaz şaraplara ait kimyasal bileşenler ve kalite derecelendirmeleri
- Öznitelikler: pH, alkol, sülfat, asidite, şeker vb. 11 farklı kimyasal bileşen
- Hedef Değişken: Şarabın kalite skoru (3-8 arası değerler)

---
## 📌 Kullanılan Makine Öğrenmesi Modelleri

Şarap kalitesini tahmin edebilmek için aşağıdaki 5 farklı makine öğrenmesi modeli kullanılmıştır:

✔️ Random Forest Classifier

✔️ XGBoost Classifier

✔️ Destek Vektör Makineleri (SVM)

✔️ Karar Ağacı (Decision Tree)

✔️ Lojistik Regresyon (Logistic Regression)

Her model, doğruluk (accuracy) ve F1 skoru gibi metrikler kullanılarak karşılaştırılmıştır.

---

## 📌 Proje İçeriği

🔹 Veri Analizi: Özniteliklerin dağılımı ve korelasyon analizi yapılmıştır.

🔹 Veri Ön İşleme: Eksik veriler kontrol edilmiş, ölçeklendirme ve öznitelik seçimi uygulanmıştır.

🔹 Makine Öğrenmesi Modelleri: 5 farklı model eğitilmiş ve test edilmiştir.

🔹 Model Karşılaştırması: Modellerin doğruluk ve F1 skorları görselleştirilerek karşılaştırılmıştır.

🔹 Tahmin Testleri: Örnek şarap verileriyle sınıf tahmini yapılmıştır.


---
## 📌 Sonuçlar

- En yüksek doğruluk oranına sahip model: Random Forest
- Özniteliklerin kalite ile en güçlü korelasyona sahip olanları: Alkol, Sülfatlar, Sitrik Asit ve Uçucu Asidite 

