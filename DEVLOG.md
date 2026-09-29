# 📋 Gurman Usta QR Menü — Devlog

> Geliştirme günlüğü ve versiyon takibi

---

## Versiyon Geçmişi

| Versiyon | Tarih | Özet |
|----------|-------|------|
| [v1.15](#v115) | 2026-09-30 | Tavuk Döner Ekmek Arası güncellendi, glow efektli pixel kayan tabela eklendi, kart arka planları kırmızı tona geçirildi |
| [v1.14](#v114) | 2026-09-30 | Metin düzeltmeleri, Pepsi Kutu/Şişe yer değişimi, boşluk dengelemesi, sabit WhatsApp butonu kaldırıldı |
| [v1.13](#v113) | 2026-09-30 | Tantuniler ana başlıklara ayrıldı, Et Döner öne alındı, butonlar büyütüldü ve harita simgesi uyarlandı |
| [v1.12](#v112) | 2026-09-30 | İletişim butonları yan yana simgelere dönüştürüldü; Döner, Kebap, Tantuni, Pide etiketleri ve slogan eklendi |
| [v1.11](#v111) | 2026-09-30 | E-posta kaldırıldı; Ara, Instagram, WhatsApp'tan Ulaş ve Haritalar butonları işlev ve marka renklerine göre güncellendi |
| [v1.10](#v110) | 2026-09-30 | WhatsApp & Instagram butonları sadeleştirildi; Adres yerine tam satır Google Haritalar butonu eklendi |
| [v1.09](#v109) | 2026-09-30 | Instagram etiketi eklendi, adres bölümüne Google Haritalar konum butonu entegre edildi |
| [v1.08](#v108) | 2026-09-30 | Visa ve Mastercard resmi SVG logoları ödeme yöntemlerinin en başına eklendi |
| [v1.07](#v107) | 2026-09-30 | VISA kaldırıldı; Pluxee, Sodexo, Ticket Restaurant ve Setcard resmi logoları eklendi |
| [v1.06](#v106) | 2026-09-30 | Gurman özel ürünlerinin etiketleri kaldırıldı, font rengi sarı yapıldı |
| [v1.05](#v105) | 2026-09-29 | CSS sözdizim hatası giderildi, tüm stiller ve render onarıldı |
| [v1.04](#v104) | 2026-09-29 | Hero sadeleştirildi, başlık açıklamaları kaldırıldı, içecek formatları güncellendi |
| [v1.03](#v103) | 2026-09-29 | Menü navigasyon kilidi düzeltildi, tüm metin simgeleri kaldırıldı |
| [v1.02](#v102) | 2026-09-29 | Siyah sınırlı yüksek çözünürlüklü şeffaf logo entegrasyonu |
| [v1.01](#v101) | 2026-09-29 | GitHub CLI Yetkilendirme onayı (Authorize ekranı) |
| [v1.00](#v100) | 2026-09-29 | Tarayıcıda Device Auth ekranı açıldı, v1.00 ana sürümüne ulaşıldı |
| [v0.90](#v090) | 2026-09-29 | GitHub CLI (gh) kurulumu ve Device Login başlatılması |
| [v0.80](#v080) | 2026-09-29 | Terminal üzerinden Git push ve credential manager yapılandırması |
| [v0.70](#v070) | 2026-09-29 | GitHub repo bağlantısı, devlog oluşturma |
| [v0.60](#v060) | 2026-09-29 | Logo ekranı paylaşıldı, tüm düzeltmeler uygulandı |
| [v0.50](#v050) | 2026-09-29 | Menü düzeltmeleri: Pepsi/Yedigün, Meyveli Soda, Günün Çorbası, Gel-Al kaldırma |
| [v0.40](#v040) | 2026-09-29 | Kaynak karşılaştırması: web sitesi + basılı menü doğrulaması |
| [v0.30](#v030) | 2026-09-29 | Menü fotoğrafları paylaşıldı, 41 ürün okundu, QR menü HTML oluşturuldu |
| [v0.20](#v020) | 2026-09-29 | Web sitesi ve Instagram bilgisi paylaşıldı, site analizi yapıldı |
| [v0.10](#v010) | 2026-09-29 | İlk istek: ücretsiz QR menü konsepti, fizibilite tartışması |

---

## v0.10
**📅 2026-09-29 21:57** · İlk İstek

**Prompt:** Çok sevdiğim bir restoran var. Onlar için ücretsiz, sıfır maliyetli ve bakım masrafı olmayan bir QR menü hazırlama hayalim var. Ne kadar mümkün, bağlanacağı internet adresi nasıl olacak.

**Yapılanlar:**
- Projenin fizibilitesi değerlendirildi
- GitHub Pages ile ücretsiz hosting stratejisi önerildi
- Maliyet tablosu oluşturuldu (tümü \$0)
- Restoran adı, menü kategorileri ve tasarım tercihi soruldu

**Dosya Değişiklikleri:** Yok (planlama aşaması)

---

## v0.20
**📅 2026-09-29 21:59** · Restoran Bilgisi

**Prompt:** https://gurmanusta.com/ şu an pek de kullanışlı olmayan bir web siteleri var. Restoran ismi "Gurman Usta" instagram hesapları: https://www.instagram.com/gurmanusta/

**Yapılanlar:**
- `gurmanusta.com` web sitesi analiz edildi (ASP.NET tabanlı, Ogani Template)
- Instagram profili incelendi (130 takipçi, 38 gönderi)
- Web sitesinden çıkarılan bilgiler:
  - E-posta: bilgi@gurmanusta.com
  - Çalışma saati: 11:00-21:00
  - Keywords: Tantuni, Döner, Pide, Lahmacun
- İletişim sayfasında yanlış keywords bulundu (Nallıhan/Sarıyar — template'den kalmış)
- Menü sayfası 500 hatası veriyor
- Menü detayları istendi

**Dosya Değişiklikleri:** Yok (araştırma aşaması)

---

## v0.30
**📅 2026-09-29 22:02** · QR Menü Oluşturma

**Prompt:** Şöyle fotoğraflarını çekmiştim. [2 menü fotoğrafı paylaşıldı]

**Yapılanlar:**
- Basılı menü fotoğraflarından 41 ürün okundu
- 8 kategori tespit edildi: Pideler, Kebaplar, Tantuniler, Tavuklar, Dönerler, Çorba, İçecekler, Gel-Al Paket
- İletişim bilgileri okundu: telefon, WhatsApp, adres (Mustafa Kemal Mah., Çankaya/Ankara)
- Ödeme yöntemleri: VISA, Pluxee/Sodexo, Ticket Restaurant, SetCard
- Fiyat geçerlilik: 26 Ocak 2026
- **index.html** oluşturuldu — tüm özellikler:
  - Mobil uyumlu koyu tema tasarım
  - Yapışkan kategori navigasyonu
  - WhatsApp sipariş butonu (floating)
  - Instagram & iletişim bölümü
  - Scroll animasyonları
  - SEO meta etiketleri
  - Baskı CSS desteği

**Dosya Değişiklikleri:**
- ✅ `index.html` oluşturuldu (yeni)

---

## v0.40
**📅 2026-09-29 22:13** · Kaynak Karşılaştırması

**Prompt:** Ürün kategorilerini hem web sitesi ile hem de basılı menü ile karşılaştırdın mı?

**Yapılanlar:**
- 3 kaynaktan detaylı karşılaştırma yapıldı: web sitesi, basılı menü kapağı, basılı menü içi
- 41 üründen 41'i doğrulandı
- 40 fiyat birebir eşleştirildi
- 1 belirsiz fiyat tespit edildi (Ayran Küçük — 25₺ olarak okundu)
- Web sitesi tutarsızlıkları belgelendi (yanlış keywords, çalışmayan menü sayfası, farklı slogan)
- Karşılaştırma raporu oluşturuldu

**Dosya Değişiklikleri:** Yok (doğrulama aşaması)

---

## v0.50
**📅 2026-09-29 22:17** · Menü Düzeltmeleri

**Prompt:** Küçük ayran 25 lira. M.soda yazan şey meyveli soda, pepsi ve yedigünü PEPSİ / YEDİGÜN olarak yaz ve parantez içerisinde şişe olanlar 60, kutu olan 70 lira olacak. Çorbayı Günün Çorbası yap. QR menüye gel al kısmını dahil etmemeliyiz şimdilik. Ayrıca gurman usta logosunu instagramdan alman lazım.

**Yapılanlar:**
- Ayran (Küçük) 25₺ onaylandı
- Instagram'dan logo alınmaya çalışıldı (erişim kısıtlı)
- Web sitesinden logo.png indirildi (basit yazı logosu)

**Planlanan düzeltmeler (v0.60'ta uygulandı):**
- [ ] M. Soda → Meyveli Soda
- [ ] Pepsi/Yedigün birleştirme
- [ ] Çorba → Günün Çorbası
- [ ] Gel-Al kaldırma
- [ ] Gerçek logo ekleme

**Dosya Değişiklikleri:**
- ⬇️ `logo.png` indirildi (web sitesinden — basit versiyon)

---

## v0.60
**📅 2026-09-29 22:20** · Logo & Tüm Düzeltmeler

**Prompt:** Şöyle bir ekran görüntüsü mevcut. [Instagram logo ekran görüntüsü paylaşıldı]

**Yapılanlar:**
- Instagram logosu alındı (gurman kırmızı + usta beyaz + aşçı şapkası)
- Logo projeye kopyalandı (`logo-gurman.png`)
- Tüm menü düzeltmeleri uygulandı:
  - ✅ Hero bölümü: emoji yerine gerçek logo
  - ✅ Pepsi/Yedigün: 4 satırdan 2 satıra ("Pepsi / Yedigün" Şişe 60₺, Kutu 70₺)
  - ✅ M. Soda → Meyveli Soda
  - ✅ Çorba → Günün Çorbası
  - ✅ "Herhangi bir yemek yanında" notu korundu
  - ✅ Gel-Al Paket bölümü kaldırıldı (HTML + nav)
  - ✅ Tekrar eden slogan kaldırıldı (logoda zaten var)

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (6 düzenleme)
- ✅ `logo-gurman.png` eklendi (yeni)

---

## v0.70
**📅 2026-09-29 22:23** · GitHub & Devlog

**Prompt:** Bir GitHub hesabı açtım, repo da hazır. https://github.com/gurmanusta/qr-menu — Bir devlog tutacaksın ve burada verdiğim tüm promptlar ve yaptığın güncellemeler hakkında notlar tutacaksın. 1.00 olana kadar her prompt versiyonu 0.10 artırır ve 1.00 olduktan sonraki promptlar 0.01 artırarak devam eder.

**Yapılanlar:**
- GitHub repo bağlantısı kuruldu: `gurmanusta/qr-menu`
- Devlog oluşturuldu (bu dosya)
- v0.10'dan v0.70'e kadar tüm promptlar geriye dönük belgelendi
- Versiyon takip sistemi:
  - v0.10 → v1.00: her prompt +0.10
  - v1.00 sonrası: her prompt +0.01
- Git yüklenmesi başlatıldı

**Dosya Değişiklikleri:**
- ✅ `DEVLOG.md` oluşturuldu (yeni)


---

## v0.80
**📅 2026-09-29 22:35** · Terminal ile Yetkilendirme Tercihi

**Prompt:** terminal

**Yapılanlar:**
- Kullanıcı GitHub kimlik doğrulaması için terminal yöntemini seçti
- Git Credential Manager (`manager`) aktif edildi
- `git push -u origin main` komutu tetiklendi

**Dosya Değişiklikleri:** Yok

---

## v0.90
**📅 2026-09-29 22:36** · GUI Bildirimi & GitHub CLI Kurulumu

**Prompt:** bir şey açılmadı

**Yapılanlar:**
- GUI penceresi açılmadığı için takılan arka plan görevi sonlandırıldı
- `winget` üzerinden resmi GitHub CLI (`gh`) kurulumu yapıldı
- Web tabanlı cihaz yetkilendirmesi (`gh auth login --web -h github.com`) başlatıldı
- Tek kullanımlık cihaz kodu (`ACA2-E4DF`) üretildi

**Dosya Değişiklikleri:** Yok

---

## v1.00 🎯
**📅 2026-09-29 22:41** · Cihaz Yetkilendirmesi & v1.00 Ana Sürümü

**Prompt:** devam et

**Yapılanlar:**
- Kullanıcı için GitHub Device Login ekranı (`https://github.com/login/device`) otomatik olarak tarayıcıda açıldı
- `ACA2-E4DF` kodu panoya ve ekrana iletildi
- İlk 10 prompt tamamlanarak **v1.00** kilometre taşına ulaşıldı
- Kural gereği bundan sonraki her prompt versiyonu **+0.01** olarak artacaktır

**Dosya Değişiklikleri:**

---

## v1.01
**📅 2026-09-29 22:46** · GitHub CLI Yetkilendirme Onayı

**Prompt:** [Ekran Görüntüsü — Authorize GitHub CLI sayfası]

**Yapılanlar:**
- Tarayıcıda açılan yetkilendirme ekranı doğrulandı ve "Authorize github" onayı alındı
- GitHub CLI yetkilendirmesi başarıyla tamamlandı (`Logged in as gurmanusta`)
- Git Credential yapılandırması bağlandı (`gh auth setup-git`)
- Kodlar GitHub reposuna başarıyla yüklendi (`git push -u origin main`)
- GitHub Pages otomatik olarak aktifleştirildi (`https://gurmanusta.github.io/qr-menu/`)
- Menü linki için yüksek çözünürlüklü QR Kod üretildi (`qr-code.png`)
- Versiyon artış kuralı uygulandı (+0.01)

**Dosya Değişiklikleri:**
- 📝 `DEVLOG.md` güncellendi (v1.01 eklendi)
- 🖼️ `qr-code.png` oluşturuldu (yüksek çözünürlüklü 600x600 QR menü kodu)

---

## v1.02
**📅 2026-09-29 22:50** · Siyah Sınırlı Şeffaf Logo Entegrasyonu

**Prompt:** bu ekran görüntüsünden logoyu siyah sınırları ile birlikte arka planını kaldırarak elde edip menüde bunu kullan.

**Yapılanlar:**
- Kullanıcının ilettiği kırmızı zeminli logo görseli analiz edildi
- Logoyu koyu temada öne çıkaran siyah sınır (outline/stroke) yapısı modellendi
- Arka plan kırmızı dokusu, gölgeler ve harf içi delikler (g döngüsü, harf araları) şeffaflaştırıldı
- 777x392 yüksek çözünürlüklü, kenarları anti-aliasing ile yumuşatılmış, sıfır kalıntı içeren `logo-gurman.png` üretildi
- Menü sayfasındaki logo bu yeni siyah sınırlı versiyonla güncellendi
- Versiyon artış kuralı uygulandı (+0.01)

**Dosya Değişiklikleri:**
- 🖼️ `logo-gurman.png` güncellendi (siyah sınırlı, şeffaf arka planlı)
- 📝 `DEVLOG.md` güncellendi (v1.02 eklendi)

---

## v1.03
**📅 2026-09-29 23:27** · Navigasyon Kilit Düzeltmesi & Simge Temizliği

**Prompt:** kebaplar seçeneği takılı kalmış, diğer kısımlara tıklanmıyor ve aşağı doğru kaydırılamıyor. düzelt. ayrıca metinlerin yanındaki simgeleri kaldır.

**Yapılanlar:**
- Sayfa kaydırma ve kategori tıklama kilidi tespit edildi:
  - Eski IntersectionObserver içindeki `link.scrollIntoView()` komutunun sayfa dikey kaydırmasını kilitlemesi ve sürekli Kebaplar sekmesine geri sıçratması engellendi.
  - Bağımsız, pencere kaydırmasını asla kilitlemeyen yeni `onScroll` ve `centerNav` JavaScript mantığı yazıldı.
  - Tıklamalar için yapışkan menü yüksekliği hesaba katılarak akıcı kaydırma (`scrollTo`) ve tıklama kilidi önleyici zamanlayıcı eklendi.
- Tüm metin yanındaki simgeler (emojiler) kaldırıldı:
  - Hero bilgi simgeleri (saat, konum) temizlendi
  - Kategori sekme emojileri kaldırıldı (sadece şık tipografi)
  - Tüm bölüm başlıklarının yanındaki kutulu emoji ikonları kaldırıldı; yerine zarif kırmızı dikey çizgi stili uygulandı
  - "Özel" rozetindeki yıldız simgesi kaldırıldı
  - İletişim kartı ve ödeme yöntemlerindeki tüm simgeler temizlendi
- Versiyon artış kuralı uygulandı (+0.01)

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (CSS, HTML ve JS baştan düzenlendi)
- 📝 `DEVLOG.md` güncellendi (v1.03 eklendi)

---

## v1.04
**📅 2026-09-29 23:40** · Hero & Başlık Sadeleştirmesi & İçecek İsim Formatı

**Prompt:** Şişe ve Kutu açıklamalarını pepsi / yedigün yazılarının yanına parantez içerisinde al. ayran büyük - küçük kısımlarını da Büyük Ayran - Küçük Ayran olarak yaz, logonun altındaki döner - kebap tantuni pide etiketlerini kaldır. saat ve yer imlecini de kaldır, fiyat açıklamasını da Fiyat Güncelleme Tarihi: 26 Ocak 2026 olarak güncelle. başlıkların altındaki açıklamaları sil (fırıntan taze, geleneksel lezzetler gibi)

**Yapılanlar:**
- İçecekler bölümünde format güncellemeleri yapıldı:
  - `Pepsi / Yedigün (Şişe)` ve `Pepsi / Yedigün (Kutu)` formatına geçildi (ayrı alt açıklama satırları kaldırıldı)
  - `Ayran (Büyük/Küçük)` yerine `Büyük Ayran` ve `Küçük Ayran` yazıldı
- Hero (karşılama) bölümü sadeleştirildi:
  - Logonun altındaki `Döner`, `Kebap`, `Tantuni`, `Pide` hap etiketleri kaldırıldı
  - Saat (`11:00 – 21:00`) ve konum bilgisi (`Çankaya / Ankara`) kaldırıldı
  - Fiyat geçerlilik metni `Fiyat Güncelleme Tarihi: 26 Ocak 2026` olarak güncellendi
- Tüm kategori başlıklarının altındaki açıklama paragrafları silindi (`fırından taze geleneksel lezzetler`, `közde pişen enfes kebaplar`, `mersin usulü tantuni çeşitleri`, `100gr porsiyon`, `günün sıcak çorbası`, `soğuk içecekler`)
- Versiyon artış kuralı uygulandı (+0.01)

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Hero, başlıklar ve içecekler düzenlendi)
- 📝 `DEVLOG.md` güncellendi (v1.04 eklendi)

---

## v1.05
**📅 2026-09-29 23:47** · CSS Kural Onarımı & Render Doğrulaması

**Prompt:** e bozdun tüm uygulamayı.

**Yapılanlar:**
- Sayfa derleme ve render hatası tespit edildi:
  - Hero bölümü düzenlenirken CSS `<style>` bloğundaki eski `.hero-tagline` kuralının kapatma süslü parantezi (`}`) eksik kalmıştı.
  - Bu tek sözdizim hatası yüzünden tarayıcı, stil dosyasının geri kalanını (kategori çubuğu, kart tasarımları, koyu tema, renkler) yok sayarak sayfayı ham/stilsiz metin olarak render etmekteydi.
- CSS kuralı temizlendi, parantez eşleşmeleri programatik olarak doğrulandı (0 hata).
- Headless tarayıcı motoruyla sayfa render edilerek dark tema, kart düzeni, yapışkan çubuk ve butonların eksiksiz çalıştığı görüntülendi.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (CSS kapatma parantezi onarıldı)
- 📝 `DEVLOG.md` güncellendi (v1.05 eklendi)

---

## v1.06
**📅 2026-09-30 00:05** · Gurman Özel Ürünler Tasarım Güncellemesi

**Prompt:** gurman yaprak şiş ve gurman kapalı pide'nin yanındaki özel etiketini iptal et ve font rengini sarı yap

**Yapılanlar:**
- "Gurman Kapalı Pide" ve "Gurman Yaprak Şiş" ürünlerinin yanındaki `<span class="item-badge popular">Özel</span>` etiketleri kaldırıldı.
- Her iki ürünün başlıklarına `.item-name.special` sınıfı eklendi ve CSS'te font rengi restoranın tema altın sarısı rengine (`var(--gold): #f5c518`) bağlandı.
- Menüdeki tüm ürünlerde etiket kalabalığı tamamen temizlenmiş, restoran spesiyalleri ise zarif sarı font vurgusuyla öne çıkarılmış oldu.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (`special` stili tanımlandı, etiketler kaldırıldı, sarı renk uygulandı)
- 📝 `DEVLOG.md` güncellendi (v1.06 eklendi)

---

## v1.07
**📅 2026-09-30 00:25** · Ödeme Yöntemleri & Resmi Yemek Kartı Logoları

**Prompt:** visa etiketini kaldır, pluxee, sodexo, ticket, setcard için resmi logoları bul ve ekle

**Yapılanlar:**
- `VISA` etiketi ödeme yöntemleri bölümünden tamamen kaldırıldı.
- Resmi kurumsal kaynaklardan 4 adet resmi yemek kartı logosu temin edildi:
  - **Pluxee:** Resmi Wikimedia Commons / Pluxee kurumsal vektörel SVG logosu (`logo-pluxee.svg`)
  - **Sodexo:** Resmi kurumsal kırmızı yıldız kıvrımlı SVG logosu (`logo-sodexo.svg`)
  - **Ticket Restaurant:** Edenred Türkiye resmi kurumsal kimlik sayfasından doğrudan alınan yüksek çözünürlüklü şeffaf PNG logosu (`logo-ticket.png`)
  - **Setcard:** Setcard Türkiye resmi sunucusundan doğrudan temin edilen vektörel SVG logosu (`logo-setcard.svg`)
- CSS ile modern, temiz beyaz kartçıklar (`.payment-badge`) tasarlandı; logoların koyu tema üzerinde bozulmadan, resmi kurumsal renkleriyle parlaması sağlandı.
- Hover efektleri ve responsive grid düzeni eklendi (tüm mobil ekranlara mükemmel uyum).
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- ➕ `logo-pluxee.svg` (yeni logo dosyası)
- ➕ `logo-sodexo.svg` (yeni logo dosyası)
- ➕ `logo-ticket.png` (yeni logo dosyası)
- ➕ `logo-setcard.svg` (yeni logo dosyası)
- 📝 `index.html` güncellendi (VISA kaldırıldı, 4 resmi logo kartı eklendi)
- 📝 `DEVLOG.md` güncellendi (v1.07 eklendi)

---

## v1.08
**📅 2026-09-30 00:41** · Visa ve Mastercard Logolarının Başa Eklenmesi

**Prompt:** Visa ve mastercard logolarını da en başa ekle

**Yapılanlar:**
- Ödeme yöntemleri bölümünün en başına Visa ve Mastercard logoları eklendi.
- Wikimedia Commons kaynaklı resmi vektörel logolar projeye dahil edildi:
  - **Visa:** Resmi modern koyu mavi vektörel SVG logosu (`logo-visa.svg`)
  - **Mastercard:** Resmi 2019 ikonik kırmızı-turuncu kesişen daireler vektörel SVG logosu (`logo-mastercard.svg`)
- Kart sırası: `[Visa, Mastercard, Pluxee, Sodexo, Ticket Restaurant, Setcard]` olarak güncellendi.
- Tüm logolar beyaz, gölgeli ve mikro etkileşimli kartçıklar içinde yüksek çözünürlükte ve dengeli ölçekte görüntülendi.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- ➕ `logo-visa.svg` (yeni logo dosyası)
- ➕ `logo-mastercard.svg` (yeni logo dosyası)
- 📝 `index.html` güncellendi (Visa ve Mastercard logoları başa eklendi)
- 📝 `DEVLOG.md` güncellendi (v1.08 eklendi)

---

## v1.09
**📅 2026-09-30 00:48** · Instagram Etiketi & Google Haritalar Konum Butonu

**Prompt:** @gurmanusta yanına parantez içerisinde Instagram yaz, adres satırına adresi sola koyarak sağ tarafa google haritalar konum linkini de ekle: https://maps.app.goo.gl/oQUd12XBmLGFH4aa6

**Yapılanlar:**
- Instagram bağlantısı `@gurmanusta (Instagram)` olarak güncellendi (WhatsApp bağlantısı ile aynı parantezli standarda getirildi).
- Adres alanı responsive iki sütunlu düzene geçirildi:
  - Sol tarafta açık adres bilgisi sola hizalı olarak korundu.
  - Sağ tarafa `Google Haritalar` bağlantı butonu (`https://maps.app.goo.gl/oQUd12XBmLGFH4aa6`) yerleştirildi.
- CSS ile modern, tıklandığında Google Haritalar'a yönlendiren şık buton (`.map-btn`) tasarlandı ve mobil uyumu sağlandı.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Instagram metni ve adres/harita düzeni)
- 📝 `DEVLOG.md` güncellendi (v1.09 eklendi)

---

## v1.10
**📅 2026-09-30 00:53** · Buton Sadeleştirmesi & Tam Satır Google Haritalar Entegrasyonu

**Prompt:** whatsapp ve instagram butonlarındaki kullanıcı adı ve telefonu sil, tıklayınca işlevler çalışsın. adres yerine google haritalar butonunu da mail gibi tüm satırı kaplayacak buton yap

**Yapılanlar:**
- WhatsApp ve Instagram butonlarındaki metin kalabalığı (telefon numarası ve kullanıcı adı) temizlendi:
  - Buton metinleri doğrudan `WhatsApp` ve `Instagram` olarak sadeleştirildi.
  - Tıklanma işlevleri (`href="https://wa.me/905309225975"` ve `href="https://www.instagram.com/gurmanusta/"`) eksiksiz korunarak çalışmaya devam etti.
- Eski adres metin bloğu tamamen kaldırılarak yerine e-posta gibi tüm satırı kaplayan `.contact-link.maps` sınıfında tam genişlikli `Google Haritalar` butonu eklendi.
- Buton tıklandığında doğrudan Google Haritalar üzerindeki restorana yönlendirilmesi sağlandı (`https://maps.app.goo.gl/oQUd12XBmLGFH4aa6`).
- Tüm iletişim butonları (Telefon, WhatsApp, Instagram, E-posta, Google Haritalar) tek tip, modern ve minimalist bir liste görünümüne kavuştu.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (CSS `.contact-link.maps` eklendi, butonlar sadeleştirildi, adres bloğu tam satır harita butonuna dönüştürüldü)
- 📝 `DEVLOG.md` güncellendi (v1.10 eklendi)

---

## v1.11
**📅 2026-09-30 01:00** · İletişim Butonları Optimizasyonu, Sıralama & Renk Revizyonu

**Prompt:** bilgi@gurmanusta.com butonunu kaldır, diğer butonların logo renklerini işlevine göre seç, gerekiyorsa değiştir. WhatsApp butonunu WhatsApp'tan Ulaş olarak güncelle, whatsapp ile instagram butonlarının yerini değiştir. en üstteki telefon numarasını da Ara olarak güncelle. tıklayınca numarayı çevirecek ceptelefonunda zaten.

**Yapılanlar:**
- `bilgi@gurmanusta.com` e-posta butonu kaldırıldı ve kullanılmayan CSS stilleri temizlendi.
- Telefon numarası butonu doğrudan `Ara` olarak güncellendi, `href="tel:+903122194999"` işlevi korunarak cep telefonlarında doğrudan arama ekranını açması sağlandı.
- Buton renkleri marka ve işlevlerine göre özelleştirildi:
  - **Ara:** Arama işlevini yansıtan canlı mavi ton (`#60a5fa`)
  - **Instagram:** Resmi Instagram degradeli mor-pembe ton (`#e1306c`)
  - **WhatsApp'tan Ulaş:** Resmi WhatsApp yeşili (`#25d366`)
  - **Google Haritalar:** Resmi Google Maps kırmızısı (`#ea4335`)
- WhatsApp ile Instagram butonlarının sırası değiştirildi (Instagram 2. sıraya, WhatsApp'tan Ulaş 3. sıraya alındı).
- WhatsApp butonu metni `WhatsApp'tan Ulaş` olarak güncellendi.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (E-posta kaldırıldı, buton metinleri, renkleri ve sıralamaları düzenlendi)
- 📝 `DEVLOG.md` güncellendi (v1.11 eklendi)

---

## v1.12
**📅 2026-09-30 01:08** · İletişim Simge Butonları, Hero Etiketleri & Slogan Eklemesi

**Prompt:** iletişim kısmındaki butonları simgeye çevir, yan yana koy. en üstteki logonun altına da DÖNER KEBAP TANTUNİ ve PİDE etiketlerini geri getir, en alt satırda, gurman usta 2026 yazısının yanına sloganı ekle: İyi lezzetlerin Yeni Adresi

**Yapılanlar:**
- İletişim butonları metinsiz, yuvarlak SVG simge butonlarına dönüştürüldü ve yan yana tek sıra halinde (`gap: 16px`) ortalandı:
  - 📞 **Ara:** Telefon ahizesi simgesi (mavi buton)
  - 📸 **Instagram:** Instagram kamera glifi simgesi (degrade mor-pembe buton)
  - 💬 **WhatsApp:** WhatsApp mesaj balonu simgesi (yeşil buton)
  - 📍 **Google Haritalar:** Harita konum pini simgesi (kırmızı buton)
  - Hover efektleri ve dokunmatik mobil ergonomisi optimize edildi.
- En üstteki logonun altına `DÖNER`, `KEBAP`, `TANTUNİ` ve `PİDE` hap etiketleri (`.hero-categories`, `.hero-cat`) geri getirildi.
- En alt satırdaki telif metni güncellenerek slogan eklendi: `© 2026 Gurman Usta — İyi lezzetlerin Yeni Adresi`.
- Versiyon artış kuralı uygulandı (+0.01).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Simge butonları, hero etiketleri ve footer sloganı eklendi)
- 📝 `DEVLOG.md` güncellendi (v1.12 eklendi)

---

## v1.13
**📅 2026-09-30 01:20** · Tantuni & Döner Yeniden Yapılandırması ve İletişim Butonları Güncellemesi

**Prompt:** Tantuniler üst başlığını iptal et ve Et Tantuni ve Tavuk Tantuni başlıklarını ana başlık yap, et döner'i tavuk dönerin üzerine çıkar, iletişim butonlarını biraz büyüt, whatsapp ile google haritalar yer değiştir, google haritalar simgesi diğer buton tasarımları ile uyumlu olsun.

**Yapılanlar:**
- `Tantuniler` çatı başlığı iptal edildi; `Et Tantuni` ve `Tavuk Tantuni` bağımsız birer ana bölüm (`<section id="et-tantuni">`, `<section id="tavuk-tantuni">`) ve yapışkan navigasyon sekmesi haline getirildi.
- `Et Döner` (`#et-doner`) bölümü, menü akışında ve navigasyon çubuğunda `Tavuk Döner`in (`#tavuk-doner`) üzerine taşındı.
- İletişim butonlarının boyutları genişletilerek dokunmatik ergonomisi artırıldı (50px ➔ 56px, simge boyutları 22px ➔ 26px).
- İletişim butonlarında WhatsApp ile Google Haritalar'ın sırası yer değiştirildi (Yeni sıralama: Ara ➔ Instagram ➔ Google Haritalar ➔ WhatsApp).
- Google Haritalar simgesi, diğer butonlarla (Instagram, WhatsApp, Ara) aynı tasarım diline sahip resmi Google Maps vektörel amblemiyle güncellendi.
- Tüm 37 menü ürünü, fiyatlar ve spesiyal sarı vurguları eksiksiz korundu.
- Versiyon kuralı uygulandı (+0.01 ➔ v1.13).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Bölüm hiyerarşisi, döner sıralaması, büyütülmüş butonlar ve Maps ikonu)
- 📝 `DEVLOG.md` güncellendi (v1.13 eklendi)

---

## v1.14
**📅 2026-09-30 01:30** · Metin Düzenlemeleri, Boşluk Dengesi, Kutu/Şişe Sıralaması ve Sabit Buton Kaldırılması

**Prompt:** "Herhangi bir yemek yanında" yazısını "Herhangi bir yemek siparişi yanında" olarak güncelle. Pepsi / Yedigün (Kutu)'yu Pepsi / Yedigün (Şişe) ile yer değiştir. "Pilav & salata ile" yazılarını "Pilav & Salata" olarak güncelle. ekran görüntüsünde gösterdiğim kısımda, fiyat güncelleme tarihi yazısının altındaki boşluğu, fiyat güncelleme tarihi yazısının üstündeki kadar yap. ayrıca en aşağıdaki 2026 gurman usta footer'ı da fazla aşağıda, iletişim kartının hemen altına çek, sağ taraftaki sabit whatsapp logosunu da kaldır.

**Yapılanlar:**
- "Yemek Yanında Çorba" açıklamasındaki "Herhangi bir yemek yanında" ifadesi "Herhangi bir yemek siparişi yanında" olarak güncellendi.
- İçecekler menüsünde "Pepsi / Yedigün (Kutu)" öne alındı, "Pepsi / Yedigün (Şişe)" arkasına alındı.
- Döner servislerindeki (Et Döner Servis ve Servis Tavuk Döner) "100gr • Pilav & salata ile" açıklamaları "100gr • Pilav & Salata" olarak revize edildi.
- Hero bölümündeki fiyat güncelleme tarihi metninin altındaki boşluk (`padding-bottom: 14px`), metnin üzerindeki boşluk (`margin-top: 14px`) ile eşitlenerek tam simetri sağlandı.
- Sağ alt köşede sabit duran WhatsApp butonu (`.fab-whatsapp`) ve nabız animasyonları tamamen kaldırıldı (kullanıcılar iletişim kartındaki büyütülmüş yeşil WhatsApp simgesini kullanmaktadır).
- Menü konteynerinin altındaki 120px'lik boşluk sıfırlandı; telif ve web sitesi footer'ı iletişim kartının hemen altına çekilerek sayfa dengelendi.
- Versiyon kuralı uygulandı (+0.01 ➔ v1.14).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Metinler, kutu/şişe sırası, hero boşluğu, footer konumu, fab-whatsapp kaldırıldı)
- 📝 `DEVLOG.md` güncellendi (v1.14 eklendi)

---

## v1.15
**📅 2026-09-30 01:42** · Tavuk Döner Ekmek Arası, Glow Efektli Pixel Kayan Tabela ve Kırmızı Kart Arka Planı

**Prompt:** sadece "Tavuk Döner" yazan seçeneği Tavuk Döner Ekmek Arası olarak güncelle. ayrıca DÖNER KEBAP TANTUNİ PİDE etiketlerini tek bir pixel kayan yazı animasyonuna çevir ve DÖNER - TANTUNİ - KÖFTE - LAHMACUN - PİDE - ÇORBA seçenekleri sonsuz bir şekilde kaymaya devam etsin. mümkünse glow efektli bir pixel tabela tasarımını deneyelim. ayrıca seçeneklerin mavi tonlu arka planını, aynı tonun kırmızı versiyonuna güncelle.

**Yapılanlar:**
- Tavuk Döner kategorisindeki yalnızca "Tavuk Döner" isimli ürün, Et Döner ile tutarlı olarak `"Tavuk Döner Ekmek Arası"` olarak güncellendi.
- Hero bölümündeki statik Döner/Kebap/Tantuni/Pide hap etiketleri kaldırılarak yerine nostaljik ve modern **Glow Efektli Pixel Kayan Tabela** (`.pixel-marquee`) entegre edildi:
  - **Tipografi:** Google Silkscreen pixel fontu kullanıldı.
  - **İçerik:** `DÖNER - TANTUNİ - KÖFTE - LAHMACUN - PİDE - ÇORBA - ` sonsuz akıcı marquee animasyonu oluşturuldu.
  - **Tabela Kasası:** 4px dot-matrix LED ızgara arka planı, 2px neon kırmızı çerçeve, iç gölge ve neon parlama (glow) efekti uygulandı. Kenar geçişleri için yumuşak karartma maskeleri eklendi.
- Menü seçeneklerinin (`.menu-item`) ve iletişim kartının (`.contact-card`) lacivert/mavi tonlu arka planı, aynı koyuluk ve derinlikteki asil kırmızı/bordo tonu gradyanına (`rgba(96, 20, 36, 0.5)` / `rgba(62, 16, 28, 0.5)`) dönüştürüldü; sınır çizgileri ve hover efektleri kırmızı aksanla uyarlandı.
- Versiyon kuralı uygulandı (+0.01 ➔ v1.15).

**Dosya Değişiklikleri:**
- 📝 `index.html` güncellendi (Silkscreen font, pixel tabela, kırmızı kart gradyanı, Tavuk Döner Ekmek Arası)
- 📝 `DEVLOG.md` güncellendi (v1.15 eklendi)

---

## 📁 Proje Dosya Yapısı

```
gurman-qr/
├── index.html          # Ana QR menü sayfası (tek dosya, minimalist & profesyonel tasarım)
├── logo-gurman.png     # Siyah sınırlı şeffaf Gurman Usta logosu
├── logo-visa.svg       # Resmi Visa vektörel logosu
├── logo-mastercard.svg # Resmi Mastercard vektörel logosu
├── logo-pluxee.svg     # Resmi Pluxee vektörel logosu
├── logo-sodexo.svg     # Resmi Sodexo vektörel logosu
├── logo-ticket.png     # Resmi Ticket Restaurant (Edenred) logosu
├── logo-setcard.svg    # Resmi Setcard vektörel logosu
├── qr-code.png         # Canlı menüye yönlendiren QR Kod görseli
└── DEVLOG.md           # Bu devlog dosyası
```

---

## 📊 Mevcut Durum (v1.15)

| Özellik | Durum |
|---------|-------|
| Menü HTML | ✅ Kusursuz çalışan koyu tema & kırmızı tonlu kartlı modern menü |
| CSS Stilleri | 🌟 Sözdizimi %100 doğrulandı, tüm kartlar ve efektler aktif |
| Hero Bölümü | 🌟 Şeffaf logo + Glow Efektli Pixel Kayan Tabela + Fiyat Tarihi |
| Pixel Kayan Tabela | 🌟 Silkscreen LED neon glow efektli, sonsuz döngü (DÖNER - TANTUNİ - KÖFTE - LAHMACUN - PİDE - ÇORBA) |
| Seçenek Arka Planları | 🌟 Aynı tonun kırmızı/bordo versiyonuna güncellendi (asli kebap/ızgara kimliği) |
| Başlıklar & Hiyerarşi | 🌟 Et Tantuni ve Tavuk Tantuni bağımsız ana başlık; Et Döner önde |
| İçecekler | ✅ Pepsi / Yedigün (Kutu / Şişe sıralaması), Büyük/Küçük Ayran |
| Spesiyaller | 🌟 Gurman Kapalı Pide ve Yaprak Şiş altın sarısı vurgulu |
| İletişim Simge Butonları | 🌟 Büyütülmüş (56px) 4 simge: Ara, Instagram, Google Haritalar, WhatsApp |
| Ödeme Logoları | 🌟 Visa, Mastercard, Pluxee, Sodexo, Ticket Restaurant, Setcard |
| Footer & Slogan | 🌟 İletişim kartının hemen altında `© 2026 Gurman Usta — İyi lezzetlerin Yeni Adresi` |
| Navigasyon & Scroll | 🚀 8 menü kategorisi + İletişim, akıcı kaydırma ve ortalama |
| Logo | 🌟 Siyah sınırlı, şeffaf, yüksek çözünürlüklü |
| Menü doğrulaması | ✅ 41/41 ürün incelendi, Gel-Al hariç 37 aktif ürün |
| Gel-Al kaldırma | ✅ |
| GitHub CLI (gh) | ✅ Kuruldu ve Giriş Yapıldı |
| GitHub Repo Push | ✅ Yüklendi (`gurmanusta/qr-menu`) |
| GitHub Pages | 🚀 **CANLI YAYINDA:** `https://gurmanusta.github.io/qr-menu/` |
| QR Kod Görseli | ✅ Üretildi (`qr-code.png`) |
| Toplam ürün | 37 (Gel-Al hariç) |
| Toplam kategori | 8 menü kategorisi (Pideler, Kebaplar, Et Tantuni, Tavuk Tantuni, Et Döner, Tavuk Döner, Çorba, İçecekler) |
| Versiyon Kuralı | Bundan sonraki her prompt +0.01 artacak |
