
Konut Piyasası Veri Analizi Projesi
Bu proje, 4500 konutluk veri setinin temizlenmesi, coğrafi analizi ve görselleştirilmesini içermektedir. Veri setindeki düzensiz adres formatları, Python ve Pandas kütüphanesi kullanılarak standartlaştırılmış ve analiz edilebilir hale getirilmiştir.

Proje Amacı
Emlak piyasasında konut dağılımını anlamak, hangi bölgelerin (şehir ve posta kodu bazlı) operasyonel açıdan daha yoğun olduğunu tespit etmek ve veriyi ham halinden anlamlı içgörülere dönüştürmektir.

Teknik Detaylar
Veri Temizleme: Adres sütunundan şehir ve posta kodu bilgilerini ayırmak için Regex (Düzenli İfadeler) kullanıldı.

Veri Analizi: Pandas kütüphanesi ile şehir ve bölge bazlı gruplandırma (groupby) ve özetleme işlemleri yapıldı.

Görselleştirme: Matplotlib kullanılarak yoğunluk analizleri pasta ve sütun grafikleriyle görselleştirildi.

Gelecek Çalışmalar
Verilerin bir harita üzerinde (GeoPandas ile) görselleştirilmesi.

Konut fiyatları varsa, fiyat-lokasyon korelasyonunun incelenmesi.

Bu çalışma, veri analizi süreçlerinde Python'ın gücünü göstermek amacıyla hazırlanmıştır.
