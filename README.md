# Kalkulator triathlonowy

Prosta strona (jeden plik `index.html`) do liczenia czasów w triathlonie i biegu.

## Triathlon
- Dystanse: Super Sprint, Sprint, Olimpijski, 1/4 Ironman, 1/2 Ironman, Ironman lub własny.
- Tempo pływania (min/100 m), prędkość roweru (km/h, co 0,1), tempo biegu (min/km) oraz czasy stref zmian T1 i T2.
- Tempo można ustawić suwakiem, przyciskami − / + albo wpisać z klawiatury (np. `5:30`, `530`, `32,5`).
- Wynik: czas na mecie, proporcje dyscyplin i zegar wyścigu po każdym etapie.

## Bieg
- Dystanse: 5 km, 10 km, 15 km, półmaraton, maraton lub własny.
- Dwa tryby: tempo → czas na mecie albo docelowy czas → potrzebne tempo.
- Punkty kontrolne i międzyczasy co kilometr.

## Aplikacja na telefonie
Strona działa jak aplikacja: ma własną ikonę i działa bez internetu.
- **iPhone (Safari):** przycisk Udostępnij → „Do ekranu początkowego”.
- **Android (Chrome):** menu ⋮ → „Zainstaluj aplikację” albo „Dodaj do ekranu głównego”.

Pliki: `manifest.webmanifest`, `sw.js` (praca offline), ikony `icon*.png`, `icon.svg`, `apple-touch-icon.png`.
Po zmianie ikon podbij `VERSION` w `sw.js`.

## Publikacja
Strona jest statyczna, nie wymaga budowania. Wystarczy opublikować `index.html`,
np. przez Cloudflare Pages (połączenie z tym repozytorium albo wgranie pliku ręcznie).
