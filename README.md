# Heart Disease Classification Project

## Proje Özeti
Bu proje, kalp hastalığı varlığını ve seviyesini tahmin etmek için makine öğrenmesi modelleri kullanmaktadır. Veri setindeki hasta özelliklerine dayanarak, Logistic Regression ve Random Forest gibi modeller geliştirilmiş ve optimize edilmiştir. Model performansları karşılaştırılarak en iyi sonuçlar elde edilmeye çalışılmıştır.

## Veri Seti
- Veri seti, yaş, cinsiyet, göğüs ağrısı tipi, kan basıncı, kolesterol seviyesi, maksimum kalp atım hızı gibi klinik ve demografik bilgileri içermektedir.
- Hedef değişken, kalp hastalığı varlığı ve şiddetini (0: yok, 1-4: farklı seviyelerde var) göstermektedir.
- Veri ön işleme aşamasında eksik ve hatalı veriler düzeltilmiş, kategorik değişkenler uygun şekilde kodlanmıştır.

## Kullanılan Yöntemler
- **Veri Ön İşleme:** Eksik değerlerin imputasyonu, kategorik değişkenlerin dönüştürülmesi, standartlaştırma.
- **Modelleme:**  
  - Logistic Regression  
  - Random Forest  
  - Hyperparameter tuning için Grid Search kullanılmıştır.
- **Değerlendirme:**  
  Accuracy, Precision, Recall, F1 Score gibi metrikler ile performans analizi yapılmıştır.

## Sonuçlar
- Modeller yüksek doğruluk ve dengeli performans göstermiştir.
- Grid Search ile optimize edilen Random Forest modeli en iyi sonuçları vermiştir.
- Model performansları detaylı şekilde karşılaştırılmış ve görselleştirilmiştir.

## İyileştirme Önerileri
- Daha fazla veri toplanabilir ve modele eklenebilir.
- Farklı algoritmalar ve ensemble yöntemleri denenebilir.
- Özellik mühendisliği ile yeni değişkenler oluşturulabilir.
- Model açıklanabilirliği yöntemleri kullanılarak karar mekanizması incelenebilir.
---

**Hazırlayan:** Beyza Nur Yıldırım  
**Tarih:** 2025  
