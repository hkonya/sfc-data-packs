# SFC 2026 — Topluluk Veri Paketleri

[Super Football Chairman 2026](https://github.com/hkonya) için topluluk tarafından
hazırlanan futbol veri paketleri. Oyun bu depodan paketleri indirip yeni kariyer
kurulumunda kullanır.

## İçerik

**2026-27 sezonu · 12 ülke · 688 kulüp · 18.236 oyuncu**

| Ülke | Kulüp | Oyuncu | Ligler |
|---|---|---|---|
| 🇹🇷 Türkiye | 145 | 3.717 | Süper Lig, 1. Lig, 2. Lig (2 grup), 3. Lig (3 grup), PGL |
| 🏴󠁧󠁢󠁥󠁮󠁧󠁿 İngiltere | 116 | 3.035 | Premier League, Championship, League One/Two, National League |
| 🇮🇹 İtalya | 60 | 1.769 | Serie A, Serie B, Serie C |
| 🇩🇪 Almanya | 56 | 1.605 | Bundesliga, 2. Bundesliga, 3. Liga |
| 🇪🇸 İspanya | 62 | 1.495 | LaLiga, LaLiga 2, Primera RFEF |
| 🇫🇷 Fransa | 54 | 1.367 | Ligue 1, Ligue 2, National |
| 🇵🇹 Portekiz | 36 | 1.028 | Primeira Liga, Liga Portugal 2 |
| 🇳🇱 Hollanda | 38 | 975 | Eredivisie, Eerste Divisie |
| 🇧🇪 Belçika | 33 | 915 | Pro League, Challenger Pro League |
| 🇬🇷 Yunanistan | 30 | 809 | Super League, Super League 2 |
| 🇸🇪 İsveç | 32 | 808 | Allsvenskan, Superettan |
| 🇭🇷 Hırvatistan | 26 | 713 | HNL, Prva NL |

Her oyuncuda ad, doğum tarihi, uyruk, mevki, forma numarası, boy, ayak,
piyasa değeri, sözleşme bitişi ve oyun için hesaplanmış güç/potansiyel
değerleri bulunur. Kulüplerde stadyum, kapasite, kuruluş yılı, renkler ve
teknik ekip yer alır.

## Dosyalar

- `index.json` — paket katalogu. Oyun önce bunu okur.
- `world-2026-27-core.json.gz` — **tek indirmelik dünya paketi** (1,5 MB).
  12 ülkenin tamamı.
- `<ülke>-2026-27-core.json.gz` — tek ülke paketleri (isteğe bağlı kullanım).
- Görsel katmanı → [Releases](../../releases) altında `<ülke>-2026-27-images.tar`.
  **Opsiyoneldir**, oyun görselsiz de tam çalışır.

## Veri hakkında

Veriler herkese açık kaynaklardan (kulüplerin resmi siteleri, federasyon
kayıtları, Wikipedia, açık futbol veritabanları) 2026-27 sezonu için
derlenmiştir. Bulunamayan alanlar uydurulmaz, boş bırakılır.

Bu depo **topluluk içeriğidir**; oyunun kendisiyle birlikte dağıtılmaz ve
oyun bu paketler olmadan da eksiksiz çalışır (kendi üretilmiş dünyasıyla).

Bir içeriğin hak sahibiyseniz ve kaldırılmasını istiyorsanız
[issue açın](../../issues), talep üzerine kaldırılır.

## Katkı

Eksik veri, hatalı kayıt veya yeni ülke önerisi için issue açabilir ya da
pull request gönderebilirsiniz.

---

© 2026 · Veriler ilgili hak sahiplerine aittir.
