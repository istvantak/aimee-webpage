# Aimee - Responsive Weboldal

Modern, responsive weboldal az Aimee termékhez, amely teljes mértékben reszponzív és minden eszközön kiválóan néz ki.

## Jellemzők

- **Teljesen reszponzív design** - Működik mobiltelefonon, tableten és asztali gépen
- **Modern UI/UX** - Letisztult, professzionális megjelenés
- **Smooth animációk** - Lágy átmenetek és scroll effektek
- **Mobil menü** - Hamburger menü kis képernyőkön
- **Interaktív elemek** - Form validáció, hover effektek
- **Optimalizált teljesítmény** - Gyors betöltési idők

## Struktúra

```
aimee/
│
├── index.html          # Fő HTML fájl
├── styles.css          # Stíluslapok
├── script.js           # JavaScript funkcionalitás
└── README.md           # Dokumentáció
```

## Szekciók

### 1. Navigáció
- Sticky navigation bar
- Responsive mobil menü
- Smooth scroll a szekciókhoz
- Aktív link jelzés

### 2. Hero szekció
- Figyelemfelkeltő címsor
- Call-to-action gombok
- Illusztráció/placeholder kép

### 3. Funkciók (Features)
- 6 funkció kártya grid layoutban
- Ikonok és leírások
- Hover animációk

### 4. Rólunk (About)
- Két hasábos elrendezés
- Cég bemutató
- Statisztikák lista

### 5. Árazás (Pricing)
- 3 árazási csomag
- Kiemelt "Népszerű" csomag
- Összehasonlító lista

### 6. Kapcsolat (Contact)
- Működő kapcsolati űrlap
- Form validáció
- Kapcsolati információk

### 7. Lábléc (Footer)
- Több hasábos elrendezés
- Linkek és információk
- Social media ikonok

## Technológiák

- **HTML5** - Szemantikus markup
- **CSS3** - Modern styling, Grid & Flexbox
- **Vanilla JavaScript** - Nincs függőség külső könyvtáraktól
- **Google Fonts** - Inter font család

## Responsive Breakpointok

- **Desktop**: > 968px
- **Tablet**: 768px - 968px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## Funkciók

### JavaScript funkciók:
- Mobil menü toggle
- Smooth scroll navigáció
- Form validáció és beküldés
- Notification rendszer
- Intersection Observer animációk
- Aktív link kijelölés scroll alapján
- Parallax effekt a hero szekcióban
- Fade-in animációk
- Navbar scroll effekt

### CSS funkciók:
- CSS Grid és Flexbox layout
- CSS Custom Properties (változók)
- Responsive design media queries
- Hover és transition effektek
- Box shadow és gradientek
- Modern animációk

## Telepítés és Használat

1. Egyszerűen nyisd meg az `index.html` fájlt egy böngészőben
2. Nincs szükség build folyamatra vagy függőségek telepítésére
3. Működik minden modern böngészőben

## Böngésző támogatás

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Testreszabás

### Színek módosítása:
A `styles.css` fájl elején találhatók a CSS változók:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... további változók */
}
```

### Tartalom módosítása:
Az `index.html` fájlban módosíthatod a szövegeket, képeket és linkeket.

### Funkciók bővítése:
A `script.js` fájlban adhatsz hozzá további JavaScript funkcionalitást.

## Tervek a jövőre

- [ ] Blog szekció
- [ ] Többnyelvűség támogatás
- [ ] Dark mode
- [ ] További animációk
- [ ] Backend integráció az űrlaphoz
- [ ] Newsletter feliratkozás
- [ ] Képgaléria

## Licenc

Ez a projekt az Aimee tulajdona.

## Kapcsolat

Ha kérdésed van a projekttel kapcsolatban:
- Email: info@aimee.hu
- Telefon: +36 1 234 5678

---

**Verzió:** 1.0.0
**Utolsó frissítés:** 2024
**Készítette:** Aimee fejlesztői csapat
