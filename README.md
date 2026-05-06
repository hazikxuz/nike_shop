# Projekt - kópia internetového obchodu Nike.com

## Stack

* Frontend:
    + Next.js
    + Typescript
    + Tailwind
* Backend
    + Golang - knižnice GIN a Gorm
    + PostgreSQL

## Implementovaná funkcionalita

### Hlavná stránka

Boli vytvorené vlastné zoznamy s nekonečným scrollovaním aj bez neho. Pomocou generík je možné
vytvárať zoznamy z rôznych typov prvkov a komponentov.

![](readme_files/main1.gif)

### Katalóg oblečenia

* Filtre podľa typu oblečenia
* Triedenie podľa ceny vzostupne/zostupne a podľa noviniek
* Vyhľadávanie podľa názvu

![](readme_files/cloth.gif)

### Stránka produktu

* Fotografie oblečenia
* Dostupné farebné varianty oblečenia
* Možnosť pridať oblečenie do obľúbených alebo do košíka

![](readme_files/single-cloth.gif)

### Košík

* Možnosť odstrániť oblečenie z aktuálneho košíka
* Možnosť zaplatiť aktuálny košík
* Možnosť zobraziť predchádzajúce zaplatené objednávky

![](readme_files/basket.gif)

### Obľúbené oblečenie

![](readme_files/favorite.gif)

### Autorizácia, registrácia a autentifikácia

Autentifikácia je implementovaná pomocou JWT tokenu.

![](readme_files/auth.gif)

### Responzivita pre rôzne typy zariadení

![](readme_files/adaptive.gif)