# Kalkulator triathlonowy

Prosta strona (jeden plik `index.html`) do liczenia czasów w triathlonie i biegu.

## Wygoda
- Wybór poziomu (Początkujący / Średni / Zaawansowany) ustawia przykładowe tempa dopasowane do dystansu.
- Na telefonie czas na mecie jest zawsze widoczny w pasku na dole ekranu.
- Przytrzymanie − / + zmienia wartość coraz szybciej.
- Plan A: zapisz ustawienia i porównuj z nimi kolejne zmiany (różnica czasu na mecie i na każdej dyscyplinie).

## Triathlon
- Dystanse: Super Sprint, Sprint, 1/8 Ironman, Olimpijski, 1/4 Ironman, 1/2 Ironman, Ironman lub własny.
- Tempo pływania (min/100 m), prędkość roweru (km/h, co 0,1), tempo biegu (min/km) oraz czasy stref zmian T1 i T2.
- Tempo można ustawić suwakiem, przyciskami − / + albo wpisać z klawiatury (np. `5:30`, `530`, `32,5`).
- Wynik: czas na mecie, proporcje dyscyplin i zegar wyścigu po każdym etapie.
- Tryb „Mam cel czasowy”: wpisujesz docelowy czas, a kalkulator rozkłada go na tempa
  pływania, roweru i biegu w proporcjach Twoich obecnych temp (T1 i T2 bez zmian).

## Bieg
- Dystanse: 5 km, 10 km, 15 km, półmaraton, maraton lub własny.
- Dwa tryby: tempo → czas na mecie albo docelowy czas → potrzebne tempo.
- Rozkład tempa: równe tempo albo negative / positive split (różnica tempa drugiej połowy w s/km).
- Punkty kontrolne, półmetek i międzyczasy co kilometr.

## Udostępnianie
Przycisk „Udostępnij” tworzy link z zapisanym dystansem, tempami i celem, np.
`?tab=tri&d=half&pl=1:57&rw=29.9&bg=5:09&t1=2:30&t2=1:30&cel=5:30:00`.
Na telefonie otwiera systemowe menu udostępniania, na komputerze kopiuje link.

## Aplikacja na telefonie
Strona działa jak aplikacja: ma własną ikonę i działa bez internetu.
- **iPhone (Safari):** przycisk Udostępnij → „Do ekranu początkowego”.
- **Android (Chrome):** menu ⋮ → „Zainstaluj aplikację” albo „Dodaj do ekranu głównego”.

Pliki: `manifest.webmanifest`, `sw.js` (praca offline), ikony `icon*.png`, `icon.svg`, `apple-touch-icon.png`.
Po zmianie ikon podbij `VERSION` w `sw.js`.

## Publikacja
Strona jest statyczna, nie wymaga budowania. Wystarczy opublikować `index.html`,
np. przez Cloudflare Pages (połączenie z tym repozytorium albo wgranie pliku ręcznie).
