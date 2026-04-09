# MoldaStore 🛍️

Magazin online de modă cu suflet moldovenesc. Site static HTML/CSS/JS, gata de publicat pe GitHub Pages.

## Structura fișierelor

```
moldastore/
├── index.html              ← Pagina principală
├── css/
│   ├── base.css            ← Reset, variabile CSS, stiluri globale, butoane
│   ├── components.css      ← Componente UI (nav, coș, search, toast, footer etc.)
│   ├── layout.css          ← Secțiuni de pagină (hero, categorii, lookbook, promo)
│   └── animations.css      ← Keyframes și scroll reveal
├── js/
│   ├── data.js             ← Array cu produse
│   ├── cart.js             ← Logica coșului de cumpărături
│   ├── ui.js               ← Produse, filtrare, search, toast, newsletter
│   └── main.js             ← Init, cursor personalizat, efecte scroll
└── README.md
```

## Funcționalități

- ✅ Hero animat cu panou vizual
- ✅ Bandă marquee animată
- ✅ Grid categorii cu hover effects
- ✅ Grid produse cu filtrare (Femei / Bărbați / Unisex)
- ✅ Coș funcțional (adaugă, modifică cantitate, șterge)
- ✅ Drawer coș lateral animat
- ✅ Modal căutare cu sugestii
- ✅ Lookbook 6 imagini
- ✅ Testimoniale clienți
- ✅ Newsletter cu validare email
- ✅ Cursor personalizat cu inel
- ✅ Bara de progres scroll
- ✅ Animații reveal la scroll
- ✅ Buton back-to-top
- ✅ Toast notifications

## Publicare pe GitHub Pages

1. Creează un repository nou pe GitHub (ex: `moldastore`)
2. Încarcă toate fișierele păstrând structura de foldere
3. Mergi la **Settings → Pages**
4. Selectează branch-ul `main` și folderul `/ (root)`
5. Click **Save** — site-ul va fi live la `https://username.github.io/moldastore`

## Tehnologii

- HTML5 semantic
- CSS3 (variabile, grid, flexbox, animații)
- JavaScript vanilla (ES6+)
- Google Fonts: Playfair Display + DM Sans

## Culori

| Variabilă           | Hex       | Utilizare            |
|---------------------|-----------|----------------------|
| `--cream`           | `#F5F0E8` | Fundal principal     |
| `--charcoal`        | `#1C1C1C` | Text, butoane        |
| `--terracotta`      | `#C4633A` | Accent, CTA          |
| `--warm-gray`       | `#8A8276` | Text secundar        |
| `--gold`            | `#B8965A` | Stele, tag-uri       |
