# Uzdevuma formulējums — Apģērbu internetveikala mājaslapa (HTML & CSS)

## Uzdevuma mērķis  
Šī uzdevuma mērķis ir izveidot strukturētas un vizuāli sakārtotas apģērbu internetveikala lapas, izmantojot **HTML** un **CSS**.  

## Uzdevuma apraksts  
Izmantojot nodrošinātos mājaslapas maketus, nepieciešams izveidot lapas apģērba internetveikalam, kas pēc iespējas precīzāk atbilst dotajiem izkārtojumiem un struktūrai. Kopā nepieciešams izstrādāt divas lapas - galvenā lapa un preču piedāvājuma lapa.

## Tehniskās prasības  
### HTML:
Jāizmanto semantiskie tagi, piemēram:
- `<header>`
- `<nav>`
- `<main>`
- `<section>`
- `<footer>`

Jābūt:
- Loģiskai virsrakstu hierarhijai (`<h1>`, `<h2>`, `<h3>`)  
- Sakārtotam un salasāmam kodam
- Iespējai pāriet no sākuma lapas uz preču piedāvājumu lapu un otrādāk

### CSS:
Jānodrošina:
- Vienoti fonti un teksta izmēri;
- Jāizmanto sniegtā krāsu palete - https://coolors.co/553a41-3a6ea5-e6e8e6-bb7e8c-191919. Ja nepieciešams, drīkst pievienot vienu citu krāsu. Nav obligāti jāizmanto visas, bet tikai tās, kas ir dotas.
- Tekstam jābūt labi salasāmam uz fona
- Teksta fonts **nedrīkst** būt *Times New Roman*
- Izmantoti izkārtojuma paņēmieni (piemēram, flex/flexbox, grid);
- Izmantoti vismaz divi vizuālās interaktivitātes paņēmieni (:hover, transition, transform, krāsas).

## Struktūras prasības
Mājaslapa sastāv no divām sadaļām - **galvenā lapa (landing page)**, kā arī **preču piedāvājumu lapa**

### Galvenajā lapā jābūt šādām sadaļām:
1. **Galvene (Header)**  
   - Logo vai internetveikala nosaukums  
   - Navigācijas izvēlne (piemēram: Galvenā lapa, preču piedāvājums)

2. **Galvenais attēls - "Hero section"**  
   - Liels attēls vai vizuāls bloks - pārredzams elements, kurš "aicina" lietotāju internetveikalā 

3. **Preces uz atlaidi**
   - Saraksts ar precēm, kurām pašlaik ir atlaide.
   - Jābūt redzamiem:
      - Preces attēls
      - Preces nosaukums
      - Nosvītrota iepriekšējā cena
      - Cena ar atlaidi

4. **Jaunākās preces**
   - Saraksts ar jaunām precēm.
   - Jābūt redzamiem:
      - Preces attēls
      - Preces nosaukums
      - Nosvītrota iepriekšējā cena
      - Cena ar atlaidi

5. **Kājene (Footer)**
   - Adrese
   - Tālruņa numurs
   - E-pasts
   - Autortiesību teksts vai internetveikala nosaukums

### Preču piedāvājuma lapā jābūt šādām sadaļām:
1. **Galvene (Header)**  
   - Logo vai internetveikala nosaukums  
   - Navigācijas izvēlne (piemēram: Galvenā lapa, preču piedāvājums)

2. **Meklēšana un filtrācija**
   - Meklēšanas josla virs preču saraksta
   - Filtrācija blakus meklēšanas joslai
   - Meklēšanas joslai un filtrācijas pogām **nav** jābūt funkcionālām

3. **Saraksts ar precēm**
   - Nepieciešamas vismaz 16 preces
   - Jābūt redzamiem:
      - Preces attēls
      - Preces nosaukums
      - Nosvītrota iepriekšējā cena
      - Cena ar atlaidi

4. **Kājene (Footer)**
   - Adrese
   - Tālruņa numurs
   - E-pasts
   - Autortiesību teksts vai internetveikala nosaukums

## Iesniegšanas prasības  
Projektu nepieciešams ievietot Github repozitorijā, pievienojot šādus failus:
- `index.html`  
- `store.html`
- CSS stila faili (piemēram `style.css` vai `main.css`)  
- Attēli, ja tiek saglabāti mapē

Projektam jābūt pieejamam un apskatāmam ar Github Pages.