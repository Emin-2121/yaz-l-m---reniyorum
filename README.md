# 🥷 3D RUNNER: Global Leaderboard & Roguelite Edition

**3D Runner**, WebGL tabanlı **Three.js** kütüphanesi ve modern web teknolojileri kullanılarak geliştirilmiş; procedural engel yönetimi, dinamik gökyüzü efektleri, küresel liderlik tablosu, karakter mağazası ve kapsamlı başarım sistemine sahip 3D sonsuz koşu (endless runner) oyunudur.

---

## 🎮 Oynanış ve Kontroller

Karakterinizi 3 şeritli pist üzerinde kontrol ederek dinamik engellerden kaçının, altınları toplayın ve yeteneklerinizi geliştirin.

| Tuş / Eylem | İşlev |
| :--- | :--- |
| **A / Sol Ok** (veya Sola Kaydır) | Sola Şerit Değiştir |
| **D / Sağ Ok** (veya Sağa Kaydır) | Sağa Şerit Değiştir |
| **SPACE (Boşluk)** (veya Yukarı Kaydır) | Zıpla |
| **Sol Mouse Tıkı / Ekrana Dokunma** | Ateş Et (Cooldown: 0.25s) |

---

## 🌟 Öne Çıkan Özellikler

### 🛒 1. Karakter Mağazası & Seviye Geliştirme (Shop & Upgrades)
Toplanan altınlarla yeni karakterlerin kilidini açabilir ve mevcut karakterlerinizi 3. seviyeye kadar yükseltebilirsiniz:
* 🤖 **Cyber Bot:** Dengeli başlangıç karakteri (Maksimum Can: 3, Hız: 1.05x).
* 🥷 **Gölge Ninjası:** Çevik refleksler ve yüksek hareket hızı (Maksimum Can: 3, Hız: 1.15x).
* ⚔️ **Ağır Şövalye:** Yüksek can kapasitesi ve zırh (Maksimum Can: 4, Hız: 0.95x).

### 🏆 2. Küresel Sıralama (Leaderboard) & Sosyal Giriş
* **Google Play & Facebook Profil Bağlantısı:** Oyuncu adınızı kaydederek profilinizi kişiselleştirin.
* **Küresel Sıralama Tablosu:** Dünya genelindeki en iyi skorları ve anlık sıranızı takip edin.
* **Tek Tıkla Skor Paylaşımı:** Elde ettiğiniz rekor skoru panoya kopyalayarak sosyal medyada paylaşın.

### 🎴 3. Rogue-Lite Güçlendirme Kartları
Belirli skor barajları aşıldığında oyun duraklar ve koşunuza yön verecek 3 karttan birini seçme şansı sunulur:
* ⚡ **Delici Ok:** Mermiler engellerin içinden geçerek arkasındaki hedefleri de yok eder.
* 💥 **Alan Patlaması:** Vurulan engel geniş bir yarıçapta patlayarak etrafındaki tuzakları temizler.
* ❤️ **Can Doldur:** Eksilen can havuzunuzu anında maksimuma tamamlar.

### ⚡ 4. Dinamik Oyun İçi Mekanikler
* **Kıl Payı Teğet Geçme (Near-Miss):** Engellere çarpmadan çok yakınından geçildiğinde ekstra **+100 Skor** ve anlık bildirim tetiklenir.
* **Dinamik Tuzaklar:** Şeritler arasında sağa-sola hareket eden testereler, uçan dronelar, çift şeritli barikatlar ve sivri taşlar.
* **4 Farklı Atmosfer Teması:** Derin Kozmoz (🌌), Kızıl Gezegen (🔴), Zümrüt Gece (🟢) ve Altın Ufuk (🌅) seçenekleri arasında anlık geçiş.

---

## 🛠️ Kullanılan Teknolojiler

* **Three.js (r128):** 3D sahne grafiği, perspektif kamera, gölgelendirme ve geometri optimizasyonları.
* **Web Audio API:** Harici dosya yüklemeden tarayıcı üzerinden matematiksel osilatörlerle dinamik ses sentezi.
* **HTML5 & CSS3:** Modern Glassmorphism (buzlu cam) arayüz tasarımı ve neon HUD panelleri.
* **LocalStorage API:** Skorların, altın bakiyesinin, açılan karakterlerin ve başarımların yerel hafızada kalıcı olarak saklanması.

---

## 🚀 Kurulum ve Çalıştırma

Projeyi çalıştırmak için herhangi bir ek sunucu veya kurulum gerekmez:

1. Bu depoyu klonlayın veya indirin:
   ```bash
   git clone [https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git](https://github.com/KULLANICI_ADINIZ/REPO_ADINIZ.git)