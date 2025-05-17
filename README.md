# 🧠 Brain MRI Classification with CNN and Transfer Learning
Bu proje, beyin tümörlerini MRI görüntüleri üzerinden sınıflandırmak amacıyla Evrişimli Sinir Ağları (CNN) ve Transfer Öğrenme yöntemlerini karşılaştırmalı olarak kullanan bir derin öğrenme uygulamasıdır. Proje, MATLAB ortamında geliştirilmiş olup, aynı zamanda kullanıcı dostu bir GUI (Graphical User Interface) içermektedir.

## 👥 Ekip
Bu çalışma, Derin Öğrenme dersi kapsamında 5 kişilik bir ekip tarafından gerçekleştirilmiştir. Her bir ekip üyesi farklı bir mimari üzerine çalışmış ve modeli eğitmiştir. Aynı zamanda proje dokümantasyonu
için detaylı bir rapor hazırlanmıştır. PDF dosyasına repository üzerinden ulaşabilirsiniz.

## 🧪 Kullanılan Modeller
- ✅ GoogLeNet

- ✅ VGG16

- ✅ MobileNet

- ✅ ResNet50

- ✅ MyCNN (Ekibimiz tarafından özel olarak geliştirilen, daha hafif bir model)

## 🗂️ Veri Seti
**Kaynak:** Kaggle - Brain MRI Images for Brain Tumor Detection
(https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection?resource=download)

**Veri Türü:** Gri ölçekli MRI görüntüleri

## Sınıflar:

- Tümör Yok
  
- Tümör Var

## 🔧 Veri Ön İşleme
Ağ mimarilerinin eğitilmesine başlamadan önce veri seti üzerinde şu ön işlemler uygulanmıştır:

- Görüntü formatları JPG, JPEG ve PNG idi → Tümü .jpg uzantısına dönüştürüldü.

- Görüntülerin bazıları Gray-Scale, bazıları RGB formatındaydı → Tüm görüntüler RGB formatına dönüştürüldü.

- Görsel boyutları farklıydı → Tüm görüntüler 224x224 piksel boyutuna yeniden boyutlandırıldı.

- Eğitim/Doğrulama/Test ayrımı yapılarak veri kümeleri oluşturuldu.

## 💻 Uygulama Arayüzü
- MATLAB App Designer kullanılarak geliştirilmiştir.

- Kullanıcılar, eğitimli modellerden birini seçerek yeni MRI görüntüleri üzerinde sınıflandırma işlemi gerçekleştirebilir.

- Arayüzde model seçimi, tahmin sonuçları ve başarı metriği gibi bilgiler görüntülenmektedir.

## 📊 Değerlendirme Metrikleri
Her modelin başarımı aşağıdaki metrikler ile analiz edilmiştir:

- Doğruluk (Accuracy)

- Karmaşıklık Matrisi (Confusion Matrix)

- Eğitim süresi ve model boyutu gibi performans karşılaştırmaları da yapılmıştır.

## 📌 Sonuçlar
Transfer öğrenme kullanılan ön eğitimli modeller (GoogLeNet, VGG16, MobileNet, ResNet50), daha kısa sürede yüksek doğruluk oranlarına ulaşmıştır.

MyCNN modeli, daha az parametreye sahip olmasına rağmen başarılı sonuçlar vermiştir.

Klinik destek sistemlerinde kullanılabilecek hafif ve etkili alternatif modeller için karşılaştırmalı bir bakış açısı sunulmuştur.

## 🖼️ Ekran Görüntüleri 
Aşağıda, uygulamaya ve eğitim sonuçlarına ait bazı ekran görüntüleri yer almaktadır. Bu görseller, grafiksel kullanıcı arayüzünü, model tahminlerini ve proje süresince elde edilen performans metriklerini göstermektedir.

![uygulama-arayüzü](https://github.com/user-attachments/assets/29fca7c1-e7c9-4a91-adda-929b8e0cb138)

## Görsel Seçimi
![görsel-seçimi](https://github.com/user-attachments/assets/422c5474-94f1-4299-9fc7-b43f19479453)

## Ağ Seçimi
![ağ-seçim-ekranı](https://github.com/user-attachments/assets/630a577e-cb64-47b1-8368-7889761b58a6)

## Optimizasyon Algoritması Seçimi
![optimizasyon-seçimi](https://github.com/user-attachments/assets/a8d1f1ff-5118-4c36-bef6-c6aa6a079786)

![yüklenen-model](https://github.com/user-attachments/assets/b0b04fe4-1355-40f7-aec8-a9a3643a26d5)

## Sınıflandırma
![sonuç](https://github.com/user-attachments/assets/af06cde0-cc0d-4c6e-9772-4cb6c4d1c079)






