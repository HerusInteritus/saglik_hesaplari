# Vücut ve Sağlık Ölçüm Paneli

Statik, sunucusuz, GitHub Pages uyumlu sağlık ve vücut kompozisyonu hesaplama paneli.

## İçerik

- BKİ, BKİ Prime, ideal kilo ve düzeltilmiş kilo
- BMR, TDEE, hedef kalori, makro, su ve lif hesabı
- US Navy, RFM, FFMI, yağ/yağsız kütle ve vücut yüzey alanı
- Bel-boy, bel-kalça, omuz-bel, BRI, ABSI ve koniklik indeksi
- Tansiyon, MAP, nabız basıncı ve antrenman nabız bölgeleri
- Glukoz, HbA1c, HOMA-IR, lipid oranları, eGFR, FIB-4, APRI
- Lokal ölçüm geçmişi ve SVG trend grafiği

## Yayınlama

1. GitHub hesabında yeni bir repository oluştur.
2. Bu klasördeki dosyaları repository köküne yükle:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Repository ayarlarından **Pages** bölümünü aç.
4. Source olarak `main` branch ve root klasörünü seç.
5. GitHub Pages linki oluşunca site çalışır.

## Not

Veriler sunucuya gitmez. Tarayıcının `localStorage` alanında saklanır. Tarayıcı verisi temizlenirse kayıtlar da silinir.
