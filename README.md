# SFC 2026 — Topluluk Veri Paketleri

[Super Football Chairman 2026](https://github.com/hkonya) için topluluk tarafından
hazırlanan futbol veri paketleri. Oyun bu depodan paketleri indirip yeni kariyer
kurulumunda kullanır.

## İçerik

**2026-27 sezonu · 12 ülke · 1.111 kulüp · 24.268 oyuncu · 60 lig (her ülkede 5 kademe)**

| Ülke | Kulüp | Oyuncu | Ligler |
|---|---|---|---|
| 🇹🇷 Türkiye | 145 | 3.717 | Süper Lig → PGL (5 kademe) |
| 🏴󠁧󠁢󠁥󠁮󠁧󠁿 İngiltere | 116 | 3.035 | Premier League → National League |
| 🇮🇹 İtalya | 96 | 2.231 | Serie A → Eccellenza |
| 🇩🇪 Almanya | 92 | 2.078 | Bundesliga → Oberliga |
| 🇪🇸 İspanya | 98 | 1.887 | LaLiga → Tercera Federación |
| 🇫🇷 Fransa | 84 | 1.735 | Ligue 1 → National 3 |
| 🇵🇹 Portekiz | 87 | 1.979 | Primeira Liga → Distrital |
| 🇳🇱 Hollanda | 90 | 1.836 | Eredivisie → Vierde Divisie |
| 🇧🇪 Belçika | 81 | 1.649 | Pro League → National 3 |
| 🇬🇷 Yunanistan | 74 | 1.010 | Super League → EPS B |
| 🇸🇪 İsveç | 74 | 1.489 | Allsvenskan → Division 3 |
| 🇭🇷 Hırvatistan | 74 | 1.622 | HNL → Četvrta NL |

İlk dört kademede tam kadro, beşinci kademede gerçek kulüp isimleri (oyuncular oyun tarafından üretilir).

Her oyuncuda ad, doğum tarihi, uyruk, mevki, forma numarası, boy, ayak,
piyasa değeri, sözleşme bitişi ve oyun için hesaplanmış güç/potansiyel
değerleri bulunur. Kulüplerde stadyum, kapasite, kuruluş yılı, renkler ve
teknik ekip yer alır.

## Dosyalar

- `index.json` — paket katalogu. Oyun önce bunu okur.
- `world-2026-27-core.json.gz` — **tek indirmelik dünya paketi** (1,9 MB).
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
