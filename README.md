🌍 Deprem Veri Analizi ve Görselleştirme
Bu proje, Python kullanarak deprem verilerini analiz eden, görselleştiren ve etkileşimli bir harita üzerinde gösteren bir veri bilimi çalışmasıdır. Proje; Pandas ile veri temizleme, Seaborn/Matplotlib ile istatistiksel grafikler oluşturma ve Folium ile coğrafi haritalama işlemlerini kapsar.

🚀 Proje Hakkında
Bu çalışmanın amacı, belirli bir veri setindeki (Excel formatında) deprem verilerini işleyerek anlamlı görseller oluşturmaktır. Kod şunları gerçekleştirir:

Excel dosyasından ham veriyi okur.

Tarih ve Saat sütunlarını birleştirerek zaman serisi formatına çevirir.

Eksik veya hatalı verileri (özellikle büyüklük verilerini) temizler.

Deprem dağılımlarını grafiklerle analiz eder.

Depremlerin büyüklüğüne göre ölçeklendirilmiş bir HTML haritası oluşturur.

🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Proje aşağıdaki Python kütüphanelerini kullanmaktadır:

Pandas: Veri manipülasyonu ve analizi.

Matplotlib & Seaborn: Veri görselleştirme ve grafik oluşturma.

Folium: Etileşimli harita oluşturma.

Openpyxl: Excel dosyalarını okumak için gerekli motor.

📊 Çıktılar ve Görseller
Kod çalıştırıldığında aşağıdaki analiz çıktılarını üretir:

Günlere Göre Deprem Sayısı: Hangi tarihte ne kadar deprem olduğunu gösteren sütun grafiği.

Deprem Büyüklük Dağılımı: Depremlerin şiddet sıklığını gösteren histogram.

Derinlik vs. Büyüklük Analizi: Derinlik ile büyüklük arasındaki ilişkiyi gösteren saçılım grafiği (Scatter Plot).

depremler_haritası.html: Depremlerin konumlarını ve büyüklüklerini (daire çapı olarak) gösteren etkileşimli harita dosyası.

