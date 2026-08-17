# SFC 2026 — Topluluk Veri Paketleri

[Super Football Chairman 2026](https://github.com/hkonya) için topluluk tarafından
hazırlanan futbol veri paketleri. Oyun bu depodan paketleri indirip yeni kariyer
kurulumunda kullanır.

## İçerik

**2026-27 sezonu · 12 ülke · 2.161 kulüp · 37.597 oyuncu · 60 lig (her ülkede 5 kademe)**

| Ülke | Kulüp | Oyuncu | Ligler |
|---|---|---|---|
| 🇮🇹 İtalya | 280 | 5.114 | Serie A → Eccellenza |
| 🇪🇸 İspanya | 262 | 3.914 | LaLiga → Tercera |
| 🇩🇪 Almanya | 237 | 3.953 | Bundesliga → Oberliga |
| 🇸🇪 İsveç | 232 | 3.088 | Allsvenskan → Division 3 |
| 🇫🇷 Fransa | 186 | 2.473 | Ligue 1 → National 3 |
| 🇵🇹 Portekiz | 172 | 3.271 | Primeira Liga → Distrital |
| 🇳🇱 Hollanda | 148 | 2.265 | Eredivisie → Vierde Divisie |
| 🇹🇷 Türkiye | 145 | 3.717 | Süper Lig → PGL |
| 🇭🇷 Hırvatistan | 138 | 2.661 | HNL → Četvrta NL |
| 🇬🇷 Yunanistan | 130 | 2.054 | Super League → EPS B |
| 🏴󠁧󠁢󠁥󠁮󠁧󠁿 İngiltere | 116 | 3.035 | Premier League → National League |
| 🇧🇪 Belçika | 115 | 2.052 | Pro League → National 3 |

Gerçekte tek lig olmayan kademeler (İtalya Serie D 9 grup, Almanya
Regionalliga 5 bölge, Türkiye 2. ve 3. Lig...) tek bir **havuz** olarak
tutulur. Oyun her yeni kariyerde havuzdan kendi lig boyutu kadar kulüp
seçer — böylece hiçbir kulüp devre dışı kalmaz ve her kurulum farklı bir
dünya üretir.

İlk dört kademede tam kadro, beşinci kademede gerçek kulüp isimleri (oyuncular oyun tarafından üretilir).

Her oyuncuda ad, doğum tarihi, uyruk, mevki, forma numarası, boy, ayak,
piyasa değeri, sözleşme bitişi ve oyun için hesaplanmış güç/potansiyel
değerleri bulunur. Kulüplerde stadyum, kapasite, kuruluş yılı, renkler ve
teknik ekip yer alır.

## Dosyalar

- `index.json` — paket katalogu. Oyun önce bunu okur.
- `world-2026-27-core.json.gz` — **tek indirmelik dünya paketi** (2,9 MB).
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
