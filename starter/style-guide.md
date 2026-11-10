# Style-guide – Cestovka Svetobežník

## Zadanie
Podľa `text.txt` vytvor vlastné `index.html` a `assets/css/style.css`. Štruktúru stránky aj názvy tried vymysli sám. 

Musíš použiť:
- [ ] sémantické HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] CSS premenné v `:root` (farby z tabuľky nižšie)
- [ ] Google Fonts cez `@import` (nadpisy: Poppins, text: Merriweather)
- [ ] **flexbox** aj **grid**
- [ ] mobile first: základ je pre mobil, ďalej len `@media (min-width: ...)`
- [ ] BEM názvy tried (napr. `hlavicka__logo`)
- [ ] `:hover` na odkazoch a tlačidlách
- [ ] žiadny JavaScript

## Farby
| Premenná | Hodnota | Použitie |
|---|---|---|
| `--ocean` | `#087e78` | svieža tyrkysová – úvodná sekcia, štatistiky a panely destinácií |
| `--hlbka` | `#123b3a` | tmavá zelená – text a pätička |
| `--piesok` | `#f3faf7` | jemná mätová biela – pozadie stránky |
| `--koral` | `#f5b544` | slnečná žltá – akcenty a tlačidlá |
| `--biela-priesvit` | `hsla(0, 0%, 100%, 0.78)` | priesvitná biela – text na tmavom pozadí |

## Fonty

- Nadpisy a logo: **Poppins**
- Text: **Merriweather**

## Breakpointy
| Zariadenie | Šírka | Rozloženie |
|---|---|---|
| Mobil | do 599px (základ) | všetko pod sebou |
| Tablet | od 600px | štatistiky vedľa seba (flex), pätička v 2 stĺpcoch |
| Desktop | od 900px | destinácie v riadkoch: panel + text, každá druhá obrátene (`row-reverse`), pätička `2fr 1fr 1fr` |

## Odsadenia
- Bočné odsadenie sekcií: `5%` (na desktope môže byť viac, napr. `8%` alebo `10%`)
- Vertikálne odsadenie sekcií: `3rem` až `5rem`
