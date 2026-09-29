# 📋 Gurman Usta QR Menü — Devlog

> Geliştirme günlüğü ve versiyon takibi

---

## Versiyon Geçmişi

| Versiyon | Tarih | Özet |
|----------|-------|------|
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

## 📁 Proje Dosya Yapısı

```
gurman-qr/
├── index.html          # Ana QR menü sayfası (tek dosya, responsive)
├── logo-gurman.png     # Gurman Usta logosu (Instagram'dan)
├── qr-code.png         # Canlı menüye yönlendiren QR Kod görseli
└── DEVLOG.md           # Bu devlog dosyası
```

---

## 📊 Mevcut Durum (v1.01)

| Özellik | Durum |
|---------|-------|
| Menü HTML | ✅ Tamamlandı |
| Gerçek logo | ✅ Eklendi |
| Menü doğrulaması | ✅ 41/41 ürün incelendi, Gel-Al çıkarıldı |
| Gel-Al kaldırma | ✅ |
| GitHub CLI (gh) | ✅ Kuruldu ve Giriş Yapıldı |
| GitHub Repo Push | ✅ Yüklendi (`gurmanusta/qr-menu`) |
| GitHub Pages | 🚀 **CANLI YAYINDA:** `https://gurmanusta.github.io/qr-menu/` |
| QR Kod Görseli | ✅ Üretildi (`qr-code.png`) |
| Toplam ürün | 39 (Gel-Al hariç) |
| Toplam kategori | 7 |
| Versiyon Kuralı | Bundan sonraki her prompt +0.01 artacak |
