# KLIMATIK Głogów

Strona wizytówka firmy KLIMATIK — klimatyzacja, pompy ciepła, rekuperacja.

Cała strona to jeden plik: `index.html` (bez builda, bez zależności).

## Formularz kontaktowy

W `index.html` jest stała `FORM_ENDPOINT` (pusta domyślnie). Gdy jest pusta, formularz
po walidacji przygotowuje wiadomość SMS i pokazuje przycisk „Zadzwoń”. Aby wysyłać
zgłoszenia mailem, wpisz adres endpointu (np. Formspree, Web3Forms lub własne API przyjmujące JSON).

## Publikacja (GitHub Pages)

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.
