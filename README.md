# SFC 2026 — Topluluk Veri Paketleri

[Super Football Chairman 2026](https://github.com/hkonya) için topluluk tarafından
hazırlanan futbol veri paketleri. Oyun bu depodan paketleri indirip yeni kariyer
kurulumunda kullanır.

## İçerik

**2026-27 sezonu · 20 ülke · 3.619 kulüp · 61.231 oyuncu · 100 lig (her ülkede 5 kademe)**

| Ülke | Kulüp | Oyuncu | Ligler |
|---|---|---|---|
| 🇳🇴 Norveç | 357 | 4.274 | Eliteserien → 4. divisjon |
| 🇦🇹 Avusturya | 293 | 5.687 | Bundesliga → Gebietsliga |
| 🇮🇹 İtalya | 280 | 5.364 | Serie A → Eccellenza |
| 🇪🇸 İspanya | 262 | 4.111 | LaLiga → Tercera |
| 🇩🇪 Almanya | 237 | 3.999 | Bundesliga → Oberliga |
| 🇸🇪 İsveç | 232 | 3.103 | Allsvenskan → Division 3 |
| 🇨🇿 Çekya | 190 | 3.526 | Chance Liga → Krajský přebor |
| 🇫🇷 Fransa | 186 | 2.547 | Ligue 1 → National 3 |
| 🇵🇱 Polonya | 180 | 3.554 | Ekstraklasa → IV liga |
| 🇵🇹 Portekiz | 172 | 3.397 | Primeira Liga → Distrital |
| 🇨🇭 İsviçre | 158 | 2.312 | Super League → 2. Liga Interregional |
| 🇳🇱 Hollanda | 148 | 2.404 | Eredivisie → Vierde Divisie |
| 🇹🇷 Türkiye | 145 | 3.961 | Süper Lig → PGL |
| 🇭🇷 Hırvatistan | 138 | 2.638 | HNL → Četvrta NL |
| 🇬🇷 Yunanistan | 130 | 2.145 | Super League → EPS B |
| 🏴󠁧󠁢󠁥󠁮󠁧󠁿 İngiltere | 116 | 3.141 | Premier League → National League |
| 🇧🇪 Belçika | 115 | 2.118 | Pro League → National 3 |
| 🇺🇦 Ukrayna | 99 | 1.531 | Premier Liha → Oblast ligleri |
| 🏴󠁧󠁢󠁳󠁣󠁴󠁿 İskoçya | 93 | 1.050 | Premiership → Highland/Lowland |
| 🇩🇰 Danimarka | 88 | 1.285 | Superliga → Danmarksserien |

Her ülke paketinde ayrıca **kulüpsüz futbolcular** bulunur
(`free_agents.json`, toplam 440 oyuncu). Oyun bunları serbest transfer
havuzunun bir kısmına yerleştirir, kalanını kendisi üretir — böylece gerçek
isimler görünürken havuzun yaş/mevki/kalite dengesi korunur.

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
- `world-2026-27-core.json.gz` — **tek indirmelik dünya paketi** (5,2 MB).
  20 ülkenin tamamı.
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
