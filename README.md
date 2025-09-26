# Akbank Global AI Hub Deep Learning Bootcamp
## Giriş
Bu projede Kaggle üzerindeki Traffic Sign Detection veri setini kullandım. 43 farklı trafik işaretini sınıflandırmak için Convolutional Neural Network (CNN) tabanlı bir model geliştirdim, katmanlarımı oluşutrdum ve parametre değişiklikleri yaparak optimizasyon yapmaya çalıştım. Model eğitimi sırasında veri ön işleme, normalizasyon ve one-hot encoding uygulandı; ayrıca data augmentation ile veri çeşitliliğini artırdım. 

## Metrikler
Modelin performansı aşağıdaki kriterler üzerinden değerlendirildi:  

- **Accuracy ve Loss Grafikleri**: Eğitim ve validation setleri için epoch bazında accuracy ve loss değerleri görselleştirildi. Bu sayede modelin öğrenme süreci, overfitting veya underfitting durumları açıkça gözlemlendi.  
- **Confusion Matrix**: Test seti üzerindeki sınıflandırma sonuçları confusion matrix ile incelendi. Bu matris, modelin hangi trafik işaretlerini doğru sınıflandırdığını ve hangi sınıflarda hata yaptığını detaylı şekilde gösterdi.  
- **Grad-CAM Görselleştirmesi**: Modelin karar verirken görüntülerin hangi bölgelerine odaklandığını görselleştirmek için Grad-CAM kullanıldı. Böylece modelin öğrenilen özellikleri görsel olarak analiz etme imkanı sağlandı.  

Bu değerlendirmeler sonucunda, eğitim süreci boyunca validation setinde en yüksek accuracy değerini veren model seçildi ve final model olarak kullanıldı. Ayrıca elde edilen sonuçlar üzerinden, modelin bazı sınıflarda düşük performans gösterdiği gözlemlendi ve gelecekte veri artırımı veya transfer learning yöntemleri ile iyileştirme yapılabileceği not edildi.

## Sonuç ve Gelecek Çalışmalar
Bu proje kapsamında geliştirdiğimiz CNN modeli, trafik işaretlerini sınıflandırmada temel düzeyde başarılı oldu. Eğitim ve validation sonuçları, modelin bazı sınıflarda hatalar yaptığını gösterdi; özellikle benzer görünümlü trafik işaretlerinde karışıklık gözlemlendi.  

Gelecekte, modelin performansını artırmak için şunlar yapılabilir:  
- **Data Augmentation Arttırma ve Transfer Learning** yöntemleri ile model daha sağlam hale getirilebilir.  
- **Gerçek zamanlı bir arayüz** eklenerek model, canlı kamera görüntüleri üzerinde çalıştırılabilir. Gerçek zamanlı çalışma için farklı modeller denenebilir.  
- Projenin veri toplama süreci **dinamik ve gerçek zamanlı** hâle getirilebilir, yeni trafik işaretleri eklenebilir.  

Bu proje bootcamp sonrasında da geliştirilmeye devam edebilir; yeni özellikler ve iyileştirmeler ekleyerek hem öğrenme hem de uygulama açısından genişletilebilir.

## Kaggle Link
https://www.kaggle.com/code/zuhalaltiner/deeplearningbootcamp


