# TRAPER — podgląd strony turystycznej

Nowa propozycja strony biura podróży TRAPER w Rzeszowie, oparta na obecnych zdjęciach, logo i treściach z traper.com.pl.

## Podgląd

https://trapcio.github.io/traper-preview/

Strona jest automatycznie publikowana przez GitHub Pages z katalogu `dist` po zmianach na branchu `main`.

## Pliki

- `dist/index.html` — dokument startowy
- `dist/styles.css` — wygląd i układ responsywny
- `dist/app.js` — interfejs, filtrowanie i programy wycieczek
- `dist/content.js` — treści dziewięciu ofert
- `dist/assets/` — lokalne logo i zdjęcia
- `SOURCE_NOTES.md` — źródła treści

## Uruchomienie lokalne

```sh
python -m http.server 8000 --directory dist
```

Otwórz http://localhost:8000. Projekt nie wymaga instalacji zależności ani budowania. Do hostingu statycznego służy katalog `dist`.

Formularz otwiera aplikację pocztową z przygotowanym zapytaniem. Nie wysyła wiadomości automatycznie i nie dokonuje rezerwacji.
