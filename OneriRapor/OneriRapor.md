## Proje Konusu
 Bu proje, ESP32 kullanarak sahte bir Wi-Fi ağı oluşturarak bağlantı talebinde bulunan cihazların MAC adreslerini toplamak ve analiz etmek amacıyla geliştirilmiştir.

## Proje Hedefleri
 Projenin temel amaçları ve başarı kriterleri şunlardır:

 * Ağ güvenliği farkındalığını artırmak: Kullanıcıları sahte Wi-Fi ağlarının riskleri konusunda bilinçlendirmek.

 * Veri analizi yapmak: Toplanan MAC adresleri ile trafik analizi yaparak kablosuz ağların güvenlik açıklarını belirlemek.

 * Güvenli ağ kullanımı için çözümler üretmek: Sahte Wi-Fi ağlarına karşı korunma yöntemlerini araştırmak ve paylaşmak.

 * Başarı kriterleri: ESP32'nin sahte Wi-Fi ağı oluşturabilmesi, MAC adreslerini başarılı bir şekilde kaydedebilmesi ve analizlerin yapılabilmesi.

## Tahmini Zaman Çizelgesi
| Görev                          | Süre  |
|----------------------------------|---------|
| Araştırma ve literatür taraması               | 2 Hafta | 
| ESP32 kurulumu ve testleri | 2 Hafta       |
| Sahte Wi-Fi ağı oluşturma ve MAC adresi toplama kodlarının geliştirilmesi | 3 Hafta |
| Veri analizi ve güvenlik değerlendirmeleri | 3 Hafta |
| Testler ve hata ayıklama süreci | 3 Hafta |


## Kaynak Planlaması 
 Proje Ekibi:
 * Muhammed Çağrı Gönültaş
 * Muhammet Emre Doğangün

 Görev dağılımı:
 * Projenin her adımında birlikte devam edilecektir.
 
 Ekipmanlar:

 * ESP32 Geliştirme Kartı
 * USB Bağlantı Kablosu
 * Bilgisayar (Kod geliştirme ve veri analizi için)

 Yazılımlar:

 * Arduino IDE
 * Wireshark
 * C++

 Proje Maliyeti:
 
 * ESP32 Kartı: 273₺
 * Oled Modül: 200₺


## Risk Analizi
| Risk                          | Çözüm  |
|----------------------------------|---------|
| ESP32'nin uyumsuzluk veya bağlantı sorunları yaşaması | Alternatif donanımlar test edilebilir, hata ayıklama yapılabilir. | 
| Toplanan verilerin etik sorunlar yaratması | Yasal çerçevelere uygun hareket edilmeli, anonimleştirme yapılmalıdır. |
| Proje süresinin uzaması | Görevler zamanında tamamlanmalı, ekip içi koordinasyon sağlanmalıdır. |


## Ticari Potansiyel
 Bu projenin ticari olarak aşağıdaki alanlarda değerlendirilme potansiyeli bulunmaktadır:

 * Siber Güvenlik Eğitimleri: Sahte Wi-Fi saldırılarının simüle edilmesiyle güvenlik farkındalığı oluşturulabilir.
 * Ağ Güvenlik Testleri: Şirketler, kendi ağlarının güvenlik açıklarını test etmek için bu sistemi kullanabilir.
 * İleri Seviye Güvenlik Çözümleri: Geliştirilerek ticari güvenlik yazılımlarına entegre edilebilir.
 * MAC adresi tespiti yapılan kullanıcılardan yasal izin almak koşuluyla konumları tespit edilebilir. Bu konumlar sürekli takip için kullanılamaz fakat büyük alışveriş merkezleri gibi yerlerde müşterilerin hangi reyonlarda daha fazla vakit geçirdiği tespit edilebilir.

## UYARI
 !!! Bu proje, Wi-Fi güvenliği konusunda bilgi edinmek ve güvenlik açıklarını test etmek için önemli bir çalışmadır. Ancak etik ve yasal çerçevede hareket edilmesi gerektiği unutulmamalıdır. Gelecekte, bu çalışmanın güvenli Wi-Fi erişim noktalarının oluşturulması ve kimlik doğrulama süreçlerinin güçlendirilmesi gibi konularda geliştirilmesi önerilmektedir.