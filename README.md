# UZB ROYALE 🇺🇿

O'zbekiston manzaralaridan ilhomlangan original, brauzerda ishlaydigan 3D battle-royale prototipi. Bu hali ilk **pre-alpha**: bitta o'yinchi va oddiy botlar bilan o'yin mexanikasini tekshirish uchun.

## Ishga tushirish

Loyiha build talab qilmaydi. GitHub Pages orqali joylashtirilgach, sahifani Chrome yoki boshqa zamonaviy brauzerda ochish mumkin. Three.js kutubxonasi internet orqali CDN'dan olinadi.

### GitHub Pages'ni bir marta yoqish
1. Repository'da **Settings → Pages** bo'limini oching.
2. **Build and deployment → Source** ostidan **GitHub Actions** ni tanlang.
3. **Actions** bo'limiga o'tib, **Deploy UZB ROYALE to GitHub Pages** workflow'ining muvaffaqiyatli tugashini kuting.
4. Sayt odatda `https://bekiuz.github.io/uzb-royale/` manzilida ochiladi. URL'ni Actions deploy natijasidan tekshiring.

Har safar `main` branch'ga o'zgarish kiritilganda deploy workflow qayta ishlaydi.

## Boshqaruv

### Kompyuter
- **W A S D** — yurish
- **Sichqoncha** — kamerani burish va nishonga olish
- **Chap tugma** — o'yinda otish mexanikasi
- **Shift** — tezroq yurish
- **Space** — sakrash
- **R** — qayta zaryadlash
- **F** — yaqin o'ljani olish
- **M** — katta xaritani ochish/yopish
- **Esc** — pauza

### Telefon
- Chap joystick — harakat
- Ekranning o'ng tomonini surish — kamera
- Tugmalar — otish, sakrash, o'ljani olish, egilish va qayta zaryadlash
- Telefonni gorizontal holatda ishlatish tavsiya etiladi.

## Dastlabki prototipda bor
- 3D muhit: shahar, mahalla, aerodrom, sanoat hududi, paxtazor, cho'l, tog'lar va qal'a.
- Uchinchi shaxs kamerasi va qahramon harakati.
- Oddiy botlar va o'yin ichidagi otish mexanikasi.
- O'lja olish, sog'liq/himoya, minimap va qisqaruvchi zona.
- Grafik darajasi, FPS chegarasi, sezgirlik va ovoz sozlamalari.
- Joriy render FPS hisoblagichi; sozlamalar brauzer xotirasida saqlanadi.

## Hozircha yo'q
- Internet orqali multiplayer va akkauntlar.
- Haqiqiy server ping'i. Server bo'lmagani uchun HUD'da **OFFLINE** ko'rsatiladi.
- Yakuniy darajadagi 3D personaj, transport modellar, animatsiyalar, haqiqiy qurol modellari, ovoz dizayni va ishlab chiqarishga tayyor anti-cheat.

Keyingi bosqich: xarita to'qnashuvlarini yaxshilash, hududlarni boyitish, animatsiya/transport, optimallashtirish va undan keyin multiplayer arxitekturasi.

## Texnologiya
- HTML/CSS/JavaScript
- Three.js (CDN orqali)
- GitHub Pages

Barcha xarita va qahramonlar prototip uchun dasturiy ravishda yaratiladi. Uchinchi tomon o'yinlarining tayyor xaritalari, logotiplari yoki skinlari ishlatilmaydi.
