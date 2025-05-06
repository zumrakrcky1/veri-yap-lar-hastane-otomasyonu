

 

T.C
SAKARYA ÜNİVERSİTESİ
BİLİŞİM SİSTEMLERİ MÜHENDİSLİĞİ


VERİ YAPILARI 1. ÖDEV 1. OTOMASYON RAPORU



Berfin Zümra Karacakaya
B23120008



DR. ÖĞR. ÜYESİ FATMA AKALIN

 
Veri yapıları ödev-1 otomasyon-1
Ödevin Amacı: Bu ödev bağlı listelerin kullanım şekillerini öğretmek amaçlanmıştır. Mesela doktor menüsü çift yönlü bağlı liste ile oluşturulmuş olup buradaki veriler çift yönlü dairesel bağlı listeye aktarılarak hasta menüsü oluşturulmuştur. Bu şekilde verilerin arka planda dizi yolu haricinde farklı farklı yöntemlerle tutulabileceği gösterilmiştir. Ayrıca C++  üzerinde fonksiyonları, yapıları, kütüphaneleri kullanmayı öğretiyor. Verilerin arka planda nasıl tutulduğunu kodlar üzerinden gösteriyor. Ayrıca bazı kısımlarında özgünlük istediği için farklı fikirler üretme yeteneğini geliştirmek istenmiştir. 
Kurgu:
Doktor ve hasta girişi olan bir hastane otomasyonu geliştirilmiştir.
Doktor seçeneği seçildiğinde arkada tutulan doktor kullanıcı adı ve şifre girilmesi istenmektedir. Yanlış giriş yapıldığında bir hak daha tanınır ,eğer 2.defa yanlış giriş yapılırsa otomasyon beş dakika durdurulur ve son bir hak daha tanınır. Tekrardan yanlış giriş yapılırsa sistemden atılır ve baş hekime mail gönderilir.
Doğru giriş yapılırsa doktor menüsü açılır. Burada doktorların karşısına 9 seçenek çıkar. Bunlar : 1. Hasta ekle; 2.Hasta sil; 3. Hasta detayları getir; 4. Ameliyat ekle; 5.Ameliyat sil; 6.Ameliyat detayları getir ;7. Ameliyat ücretini hesapla ; 8. Ana menüye dön; 9. Çıkış şeklindedir. Bu işlevsellikler çift yönlü bağlı liste yapısında tutulur.
Hasta girişi yapılırsa kullanıcıların karşına 6 seçenek çıkar. Bunlar: 1. Hastane doktorlarını yazdır; 2.Tüm hastaları yazdır; 3. Ameliyat hastalarını yazdır; 4. Hastaların öncelik puanları; 5. Ana menüye dön; 6.Çıkış. seçenekleridir. Bu menüdeki veriler doktor seçeneğinde çift yönlü bağlı listede tutulan verilerin, çift dairesele dönüştürülmesiyle oluşturulmuştur. 
3. giriş hastane değerlendirme seçeneğidir ve burada da  hastanedeki hasta sayısı, ameliyat hastaları sayısı hastaların renk kodlarına göre kaç hasta olduğu gibi güncel verileri, tek yönlü dairesel bağlı liste yapısında tutulur.
 

# veri-yap-lar-hastane-otomasyonu
