# UZB ROYALE 🇺🇿

O'zbekiston manzaralaridan ilhomlangan original, brauzerda ishlaydigan 3D survival-arena prototipi. Bu ilk **pre-alpha**: bitta o'yinchi, bot-challengerlar, xarita va belgilash (tag) mexanikasi bilan ishlaydigan sinov versiyasi.

## Ishga tushirish

Loyiha build talab qilmaydi. GitHub Pages orqali joylashtirilgach, sahifani Chrome yoki boshqa zamonaviy brauzerda ochish mumkin. Three.js kutubxonasi internet orqali CDN'dan olinadi.

### GitHub Pages'ni bir marta yoqish
1. Repository'da **Settings → Pages** bo'limini oching.
2. **Build and deployment → Source** ostidan **GitHub Actions** ni tanlang.
3. **Actions** bo'limiga o'tib, **Deploy UZB ROYALE to GitHub Pages** workflow'ini qayta ishga tushiring (yoki keyingi commitni kuting).
4. Muvaffaqiyatli deploy'dan keyin URL'ni Actions natijasidan oching. Kutiladigan manzil: `https://bekiuz.github.io/uzb-royale/`.

Har safar `main` branch'ga o'zgarish kiritilganda deploy workflow qayta ishlaydi.

## Boshqaruv

### Kompyuter
- **W A S D** — yurish
- **Sichqoncha** — kamerani burish
- **Chap tugma** — yaqin va ko'rinadigan raqibni belgilash (arkada tag mexanikasi)
- **Shift** — tezroq yurish
- **Space** — sakrash
- **R** — skan: raqiblarni minimapda vaqtincha ko'rsatish
- **F** — yaqin signal kristali yoki tibbiy to'plamni olish
- **M** — katta xaritani ochish/yopish
- **Esc** — pauza

### Telefon
- Chap joystick — harakat
- Ekranning o'ng tomonini surish — kamera
- Tugmalar — raqibni belgilash, sakrash, skan, o'lja olish va egilish
- Telefonni gorizontal holatda ishlatish tavsiya etiladi.

## Dastlabki prototipda bor
- 3D muhit: shahar, mahalla, aerodrom, sanoat hududi, paxtazor, cho'l, tog'lar va qal'a.
- Uchinchi shaxs kamerasi, qahramon harakati va oddiy bot-challengerlar.
- Yaqin masofali belgilash mexanikasi, signal kristallari, tibbiy to'plamlar.
- Sog'liq/himoya, minimap, skan va qisqaruvchi zona.
- Grafik darajasi, FPS chegarasi, sezgirlik va ovoz sozlamalari.
- Joriy render FPS hisoblagichi; sozlamalar brauzer xotirasida saqlanadi.

## Hozircha yo'q
- Internet orqali multiplayer va akkauntlar.
- Haqiqiy server ping'i. Server bo'lmagani uchun HUD'da **OFFLINE** ko'rsatiladi.
- Yakuniy darajadagi 3D qahramonlar, transportlar, animatsiyalar, to'liq ovoz dizayni va ishlab chiqarishga tayyor anti-cheat.

Keyingi bosqich: xarita to'qnashuvlarini yaxshilash, hududlarni boyitish, animatsiya va transport, optimallashtirish; keyin alohida multiplayer arxitekturasi.

## Texnologiya
- HTML/CSS/JavaScript
- Three.js (CDN orqali)
- GitHub Pages

Xarita va personajlar prototip uchun kod yordamida yaratiladi; boshqa o'yinlarning tayyor xaritalari, logotiplari yoki kiyim resurslari ishlatilmaydi.
