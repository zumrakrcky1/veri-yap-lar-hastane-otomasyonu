

 

T.C
SAKARYA ÜNİVERSİTESİ
BİLİŞİM SİSTEMLERİ MÜHENDİSLİĞİ


VERİ YAPILARI 1. ÖDEV 1. OTOMASYON RAPORU



DR. ÖĞR. ÜYESİ FATMA AKALIN

 
Veri yapıları ödev-1 otomasyon-1
Ödevin Amacı: Bu ödev bağlı listelerin kullanım şekillerini öğretmek amaçlanmıştır. Mesela doktor menüsü çift yönlü bağlı liste ile oluşturulmuş olup buradaki veriler çift yönlü dairesel bağlı listeye aktarılarak hasta menüsü oluşturulmuştur. Bu şekilde verilerin arka planda dizi yolu haricinde farklı farklı yöntemlerle tutulabileceği gösterilmiştir. Ayrıca C++  üzerinde fonksiyonları, yapıları, kütüphaneleri kullanmayı öğretiyor. Verilerin arka planda nasıl tutulduğunu kodlar üzerinden gösteriyor. Ayrıca bazı kısımlarında özgünlük istediği için farklı fikirler üretme yeteneğini geliştirmek istenmiştir. 
Kurgu:
Doktor ve hasta girişi olan bir hastane otomasyonu geliştirilmiştir.
Doktor seçeneği seçildiğinde arkada tutulan doktor kullanıcı adı ve şifre girilmesi istenmektedir. Yanlış giriş yapıldığında bir hak daha tanınır ,eğer 2.defa yanlış giriş yapılırsa otomasyon beş dakika durdurulur ve son bir hak daha tanınır. Tekrardan yanlış giriş yapılırsa sistemden atılır ve baş hekime mail gönderilir.
Doğru giriş yapılırsa doktor menüsü açılır. Burada doktorların karşısına 9 seçenek çıkar. Bunlar : 1. Hasta ekle; 2.Hasta sil; 3. Hasta detayları getir; 4. Ameliyat ekle; 5.Ameliyat sil; 6.Ameliyat detayları getir ;7. Ameliyat ücretini hesapla ; 8. Ana menüye dön; 9. Çıkış şeklindedir. Bu işlevsellikler çift yönlü bağlı liste yapısında tutulur.
Hasta girişi yapılırsa kullanıcıların karşına 6 seçenek çıkar. Bunlar: 1. Hastane doktorlarını yazdır; 2.Tüm hastaları yazdır; 3. Ameliyat hastalarını yazdır; 4. Hastaların öncelik puanları; 5. Ana menüye dön; 6.Çıkış. seçenekleridir. Bu menüdeki veriler doktor seçeneğinde çift yönlü bağlı listede tutulan verilerin, çift dairesele dönüştürülmesiyle oluşturulmuştur. 
3. giriş hastane değerlendirme seçeneğidir ve burada da  hastanedeki hasta sayısı, ameliyat hastaları sayısı hastaların renk kodlarına göre kaç hasta olduğu gibi güncel verileri, tek yönlü dairesel bağlı liste yapısında tutulur.


Veri yapıları ödev-1 otomasyon-2
Ödevin Amacı: Bu ödev tek yönlü bağlı liste kullanım şekillerini öğretmek amaçlanmıştır. Ürün bilgileri arka planda tek yönlü bağlı liste ile tutulmuştur. Ayrıca C++  üzerinde fonksiyonları, yapıları, kütüphaneleri kullanmayı öğretiyor. Verilerin arka planda nasıl tutulduğunu kodlar üzerinden gösteriyor.
Kurgu:
Markete yeni gelen ürünlerin tutulduğu bir otomasyon geliştirilmiştir. 1.Ürün kaydet; 2.Ürün sil; 3. Ürün güncelle; 4. Listede ürün ara; 5. Aranan elemanı tüm özellikleri ile yazdır; 6.Tüm ürünleri yazdır; 7. Tüm ürünlerin fiyatlarını küçükten büyüğe sırala; 8. Listede bulunan tüm elemanların maliyetini hesapla;9-.Listede yer alan tüm ürünlere %10 zam yap; 10. Minimum maliyete sahip ürünü getir; 11. Maksimum maliyete sahip ürünü getir; 12.Girdi olarak alınan ürüne ilişkin aynı maliyetli diğer ürünlerin toplam sayısını bul; 13. Tüm ürünleri dosyaya yazdır; 14. Dosyadan ürünleri oku; 15. Çıkış yap seçeneklerinden oluşan ve bunları tek yönlü bağlı liste yapısında tutan bir otomasyondur. Ürün güncelle seçeneğinde güncellenecek ürün bulunamadığında mevcut ürünler sunulur ve müdürün dosyasına olmayan ürünler yazdırılır.

 

# veri-yap-lar-hastane-otomasyonu
