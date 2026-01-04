# 🚀 GitHub Pages Deployment Guide

## 📁 Dosyalar Hazır!

Aşağıdaki dosyalar GitHub'a yüklenecek:
- ✅ `index.html` - Ana uygulama
- ✅ `manifest.json` - PWA ayarları
- ✅ `service-worker.js` - Offline çalışma
- ✅ `icon.svg` - App ikonu

---

## 🎯 ADIM ADIM TALİMAT

### 1️⃣ GitHub Hesabı Aç

1. https://github.com adresine git
2. **Sign Up** butonuna tıkla
3. Email, şifre belirle
4. Email'ini doğrula

---

### 2️⃣ Yeni Repository Oluştur

1. GitHub'a giriş yap
2. Sağ üstte **+** butonuna tıkla
3. **New repository** seç
4. Repository ayarları:
   ```
   Repository name: gta-minimap
   Description: GTA V style GPS navigation app
   ✅ Public (seçili olsun)
   ❌ Add README (boş bırak)
   ```
5. **Create repository** butonuna tıkla

---

### 3️⃣ Dosyaları Yükle

**Yöntem A: Web Arayüzü (Kolay)**

1. Yeni oluşan sayfada **uploading an existing file** linkine tıkla
2. Şu dosyaları sürükle-bırak:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `icon.svg`
3. En altta **Commit changes** butonuna tıkla

**Yöntem B: Git ile (Terminal)**

```bash
# 1. Klasöre git
cd C:\Users\erdem\OneDrive\Masaüstü\GTA_V_MAP

# 2. Git başlat
git init

# 3. Dosyaları ekle
git add index.html manifest.json service-worker.js icon.svg

# 4. Commit
git commit -m "Initial commit - GTA MiniMap PWA"

# 5. GitHub'a bağlan (KULLANICI_ADIN ile değiştir)
git remote add origin https://github.com/KULLANICI_ADIN/gta-minimap.git

# 6. Push
git branch -M main
git push -u origin main
```

---

### 4️⃣ GitHub Pages Aktif Et

1. Repository sayfasında **Settings** sekmesine git
2. Sol menüden **Pages** seç
3. **Source** bölümünde:
   ```
   Branch: main
   Folder: / (root)
   ```
4. **Save** butonuna tıkla
5. 2-3 dakika bekle
6. Sayfa yenilendiğinde üstte link göreceksin:
   ```
   Your site is live at https://KULLANICI_ADIN.github.io/gta-minimap/
   ```

---

### 5️⃣ Test Et!

1. Yukarıdaki linki kopyala
2. Telefon/Bilgisayarda aç
3. Konum izni ver
4. ✅ Çalışıyor mu kontrol et

---

### 6️⃣ PWA Olarak Kur (Mobil)

**Android (Chrome):**
1. Siteyi aç
2. Chrome menü (⋮) → **Install app** veya **Add to Home screen**
3. Kutulan simgeye tıkla
4. App gibi çalışıyor! 🎉

**iOS (Safari):**
1. Siteyi aç
2. Paylaş butonu (□↑) → **Add to Home Screen**
3. İsim gir → **Add**
4. Ana ekranda simge çıktı! 🎉

---

### 7️⃣ APK Oluştur (PWABuilder)

1. https://www.pwabuilder.com adresine git
2. GitHub Pages URL'ini gir:
   ```
   https://KULLANICI_ADIN.github.io/gta-minimap/
   ```
3. **Start** butonuna tıkla
4. Analiz bitince **Package for stores** seç
5. **Android** seç
6. **Generate** tıkla
7. APK dosyasını indir!
8. Telefona at, yükle, kullan! 📱

---

## ⚠️ Önemli Notlar

### Icon Problemi

GitHub Pages'de icon.svg çalışmayabilir. Bunun için PNG icon gerekli:

**Çözüm 1: Online SVG to PNG**
1. https://svgtopng.com adresine git
2. `icon.svg` dosyasını yükle
3. 192x192 ve 512x512 boyutlarında indir
4. `icon-192.png` ve `icon-512.png` olarak kaydet
5. GitHub'a yükle

**Çözüm 2: Ben hazır icon vereyim**
- Basit yeşil-sarı navigation icon kullan
- Canva'da tasarla

### HTTPS Zorunlu

- GitHub Pages otomatik HTTPS kullanır ✅
- GPS için HTTPS şart
- Sorun yok!

### Güncelleme Yapmak

Dosyada değişiklik yaptın mı?

```bash
# Değişiklikleri GitHub'a gönder
git add .
git commit -m "Updated features"
git push
```

2-3 dakika sonra site güncellenecek!

---

## 🎯 Özet - Ne Yapacaksın?

1. ✅ GitHub hesabı aç
2. ✅ `gta-minimap` repository oluştur
3. ✅ 4 dosyayı yükle (index.html, manifest.json, service-worker.js, icon.svg)
4. ✅ Settings → Pages → Aktif et
5. ✅ Link'i aç ve test et
6. ✅ PWABuilder ile APK oluştur

---

## 💡 Yardım Lazımsa

**Git kurulu değilse:**
- https://git-scm.com/downloads
- İndir, kur, cmd'de `git --version` ile test et

**Icon sorunuysa:**
- icon.svg yerine basit PNG kullan
- 512x512 px, siyah zemin, yeşil ok

**Pages çalışmıyorsa:**
- Settings → Pages → Source'u kontrol et
- 5 dakika bekle
- Actions sekmesinde hata var mı bak

---

## 🚀 Şimdi Başla!

Hazırsan GitHub.com'a git ve başla! 

Takıldığın yerde bana sor! 💪
