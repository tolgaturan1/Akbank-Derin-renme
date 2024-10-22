# Akbank-Derin-renme
Akbank derin öğrenme bootcamp projesi
Kaggle linki : https://www.kaggle.com/code/tolgaturan28/fish-classifacition
# Yapay Sinir Ağları (YSA) Kullanılarak Balık Sınıflandırması
Bu proje Akbank Derin Öğrenme Eğitim Kampı sırasında geliştirildi. Amaç, farklı balık türlerini sınıflandırmak için Yapay Sinir Ağları (YSA) kullanarak bir görüntü sınıflandırma modeli oluşturmaktı. Projenin temel yönleri aşağıda özetlenmiştir:
Veri Ön İşleme ve Bölme:
Veri Bölünmesi: Daha iyi model değerlendirmesi için veri seti üç bölüme ayrılmıştır.
Eğitim Seti ,Doğrulama Seti, Test Seti
# YSA Mimarisi:
Katmanı Düzleştir: Görüntü verilerini tek boyutlu bir diziye dönüştürür.
Gizli Katmanlar (Yoğun): Sınıflandırma için kullanılan tam bağlantılı katmanlardır.
Dropout Katmanı: Bazı nöronları rastgele devre dışı bırakarak aşırı uyumu önler.
Çıkış Katmanı (Softmax): Çoklu sınıflandırmayı işler.
# Model Eğitimi ve Değerlendirmesi:
Derleme Modeli:categorical_crossentropy Modeli derlemek için Adam optimizer ve kayıp fonksiyonu kullanıldı .
Doğrulama Kullanımı: Aşırı uyumu önlemek için eğitim sırasında doğrulama kümesini kullanarak sürekli olarak izlenen performans.
İzleme Metrikleri: Eğitim sırasında model iyileştirmelerini gözlemlemek için doğruluk ve kayıp çizildi.
# Test ve Genelleme:
Test Seti Değerlendirmesi: Daha önce görülmemiş veriler üzerinde model performansının değerlendirilmesi.
Genelleme: Modelin yeni girdilere ne kadar iyi genelleştirildiğinin gözlemlenmesi.
# Performansın Görselleştirilmesi:
İyileştirme alanlarını belirlemek için görselleştirilmiş eğitim ve doğrulama kaybı/doğruluğu.
Bu proje, görüntü işleme, veri yönetimi ve sinir ağları kullanılarak model performans değerlendirmesi de dahil olmak üzere makine öğrenimi ve derin öğrenmedeki temel kavramları güçlendirdi.
