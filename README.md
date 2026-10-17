## 🛡️ Siber Güvenlik ve Oltalama (Phishing) Farkındalık Rehberi

Bu simülasyon, kullanıcıların en sık karşılaştığı sosyal mühendislik taktiklerini anlamaları ve dijital dünyada daha bilinçli hareket etmeleri amacıyla geliştirilmiştir. Gerçek durumlarda saldırganların sıklıkla kullandığı temel yöntemler şunlardır:

### 1. URL ve Adres Çubuğu Analizi (Red Flags)
Bir web sitesine giriş yapmadan önce tarayıcının adres çubuğunu (URL) kontrol etmek önem taşır:
* **Protokol Kontrolü:** Güvenli siteler `https://` ile başlar. Ancak günümüzde saldırganlar da ücretsiz SSL sertifikaları alarak sahte sitelerinde `https` kullanabilmektedir, bu yüzden sadece kilit simgesine güvenilmemelidir.
* **Tehlikeli Yerel Protokoller:** Tarayıcı çubuğunda `file://`, `data://` veya `http://` gibi ibareler ve domain kısmında anlamsız karakter dizileri görüyorsanız o sayfa yerel olarak çalıştırılan veya güvenli olmayan bir sahte sayfadır.
* **Alt Domain (Subdomain) Oyunu:** Saldırganlar gerçek alan adını gizlemek için adresleri karmaşıklaştırabilir. Örneğin; `giris.guvenlik-kontrolu.com.orneksite.com` adresinde asıl site `orneksite.com`'dur, başındaki kısımlar sadece illüzyondur.

### 2. Typosquatting (Benzer ve Taklit Domainler)
Saldırganlar, kullanıcıların gözünden kaçabilecek harf oyunlarıyla resmi sitelerin birebir kopyalarını (klonlarını) oluştururlar:
* **Karakter Değişiklikleri:** `google.com` yerine `go0gle.com` (sıfırla), `rnicrosoft.com` (m ve i harfi yerine rn) gibi göz yanıltıcı alan adları satın alırlar.
* **Üst Düzey Alan Adı (TLD) Oyunları:** `.com` yerine `.co`, `.cm`, `.net` veya kuruma ait olmayan farklı ülke uzantılarını kullanarak kullanıcıları yanıltırlar.

### 3. E-posta Bağlantılarına Neden Körü Körüne Güvenilmemelidir?
E-postalarda gelen "Şifrenizi sıfırlayın", "Hesabınız askıya alındı", "Acil güvenlik doğrulaması gerekiyor" gibi aciliyet belirten mesajlar klasik bir oltalama (phishing) tuzağıdır:
* **Görnen ile Gerçek Farklıdır:** E-posta üzerindeki buton veya metin `https://www.google.com` yazıyor olabilir, ancak arkasındaki gerçek yönlendirme linki zararlı bir siteye çıkabilir. (Bağlantıların üzerine tıklandığında sol altta çıkan önizleme adresine mutlaka bakılmalıdır).
* **Aciliyet Psikolojisi:** Saldırganlar kurbanın mantıklı düşünmesini engellemek için panik ve aciliyet duygusu yaratırlar. Kurumlar e-posta yoluyla şifre güncelleme veya doğrudan giriş yapma bağlantısı göndermezler; her zaman resmi tarayıcı üzerinden doğrudan ilgili siteye gidilmelidir.