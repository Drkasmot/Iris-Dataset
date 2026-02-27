# Iris-Dataset
In this repo we'll see how can we make classification models for the Iris Dataset

Iris Dataset - Multiple Classification Models

Bu projede Iris veri seti kullanılarak Support Vector Machine (SVM),Naive-Bayes ve Logistic-Regression algoritmaları ile sınıflandırma yapılmıştır.
Böyle bir veride modellerin farklılık gösterip göstermediği incelenmiştir.

Kullanılan Kütüphaneler

    pandas
    numpy
    matplotlib
    seaborn
    scikit-learn

Veri Seti

    Toplam 150 örnek
    Özellikler:
        SepalLengthCm
        SepalWidthCm
        PetalLengthCm
        PetalWidthCm
    Hedef değişken: Species

Yapılan İşlemler

    CSV dosyası pandas ile okundu.
    Veriler Görselleştirildi
    Özellikler (X) ve hedef değişken (y) ayrıldı.
    Veri %80 eğitim, %20 test olacak şekilde bölündü.
    LabelEncoder ile hedef değişken sayısal hale getirildi.
    SVC,NB ve LR modeli oluşturuldu ve eğitildi.
    Test verisi üzerinde tahmin yapıldı.
    Accuracy hesaplandı.
    AUC-ROC

Sonuç

Accuracy: 1.0
AUC:1.0

Modeller test verisi üzerinde %100 doğruluk elde etmiştir.
