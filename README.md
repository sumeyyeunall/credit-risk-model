
# Kredi Risk Modeli - Makine Öğrenmesi Projesi

Bu projede Almanya’daki kredi başvurularına ait Kaggle’daki German Credit Data veri seti kullanılarak kredi riskini tahmin eden bir makine öğrenmesi modeli geliştirildi.

## Veri Ön İşleme

* Eksik veriler uygun yöntemlerle tamamlandı (imputation).
* Kategorik değişkenler, etiket kodlama (Label Encoding) ve one-hot encoding teknikleriyle sayısal formata dönüştürüldü.
* Verideki anlamsal tutarlılık sağlandı ve eğitim-test setleri oluşturuldu.

## Modelleme

* Logistic Regression ve Random Forest algoritmaları seçildi.
* Her iki model için GridSearchCV kullanılarak hiperparametre optimizasyonu gerçekleştirildi.
* Modellerin doğruluk, precision, recall ve F1 skorları gibi performans metrikleri hesaplandı ve karşılaştırıldı.

## Sonuçlar

* Logistic Regression modeli %74 doğruluk, Random Forest modeli ise %75 doğruluk ile kredi riskini tahmin etti.
* Model performansları karşılaştırılarak en iyi sonuç veren model seçildi.
* Elde edilen başarı, makine öğrenmesi tekniklerinin kredi risk tahmininde etkin olduğunu gösterdi.

## Kullanılan Teknolojiler

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.


