# 2025-05-13-mobile-first

# 📱 Mobile First, Layout och Designprinciper för Mobil

[Länk till presentationen](https://docs.google.com/presentation/d/1nNOzoS2S4aNIo5QllxxaGnpEq4QqyPtrgG7iCwEKQ2E/edit?usp=sharing)

## Vad betyder Mobile First?

"Mobile First" är en metod där man designar och bygger sin webbplats för **mobilen först**, och sedan anpassar den för större skärmar med hjälp av **media queries**. Eftersom många besökare surfar via mobilen är det smart att börja där användarna faktiskt är.

> Istället för att skala ner en komplex desktop-sida till mobil – börja enkelt och skala upp!

## Mobile First i praktiken

- Designa med fokus på **det viktigaste först** – innehåll och funktion.
- Använd `@media (min-width: ...)` i CSS för att ändra layout på större skärmar.
- Optimera för **laddningstid** och **användbarhet** redan från början.

## Layout – Mobil vs Desktop

| Mobil                           | Desktop                         |
|----------------------------------|----------------------------------|
| En kolumn – allt staplas         | Flera kolumner                   |
| Större text och klickytor        | Mindre marginaler, fler val     |
| Dold meny (hamburger)            | Synlig meny                     |
| Fokus på snabbhet och enkelhet   | Mer information på samma yta    |

## Designprinciper för Mobil

- 📐 **Tydlig hierarki** – det viktigaste överst
- 👆 **Stora klickytor** – minst 48x48 px
- 🔤 **Läsbar text** – använd minst 16px textstorlek
- ⚡ **Prestanda** – ladda inte onödiga bilder
- ☁️ **Touchvänlig design** – undvik hover-effekter
- 🧭 **Enkel navigation** – gärna genom hamburgermeny eller bottenmeny

## Bra att tänka på

- Använd `meta viewport`:
  ```html
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
# 🧪 Övning 1: Skapa en responsiv webbsida
Koda upp en responsiv webbida utifrån er designskiss som ni skapade i Figma under lektionen. Börja med mobilvy - använd sedan media queries för desktop vyn. 

# 🧪 Övning 2: Skapa en responsiv profilsida – Mobile First

Bygg en enkel profilsida som fungerar bra på mobil **och** anpassas för större skärmar med media queries.

## 🎯 Mål
- Tillämpa Mobile First-principen
- Skapa grundläggande layout för mobilskärm
- Använda media queries för att anpassa designen för desktop

## 🧩 Innehåll som ska finnas med
- En **profilbild**
- Ditt **namn** och en **kort beskrivning**
- En **kontaktsektion** eller lista med **intressen**
- En **meny** högst upp med länkar (det räcker att de ser ut som länkar)

## ✅ Krav
- Sidan ska vara **mobile first**:
  - Allt staplat vertikalt
  - Anpassad för liten skärm
- Du ska använda `meta viewport` i `<head>`
- En **media query** för `min-width: 768px`:
  - Menyn visas horisontellt (rad istället för kolumn)
  - Profilbild och beskrivning ligger bredvid varandra
  - Layouten blir luftigare – större marginaler och text

## 💡 Tips
- Du får använda t.ex. `inline-block`, `float`, `text-align`, `width: %` osv.
- Inga krav på Flexbox eller Grid – du får lösa layouten på det sätt du kan just nu
- Tänk på **tydlig visuell hierarki**, **läsbar text**, **klickvänliga ytor**

## 📦 Extra (frivilligt)
- Lägg till en knapp eller länk till "Skicka meddelande"
- Lägg in ikoner med emoji eller t.ex. från [Font Awesome](https://fontawesome.com/)
