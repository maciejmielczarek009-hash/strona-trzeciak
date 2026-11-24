# strona-trzeciak

Prototyp strony głównej trzeciak.pl (jeden plik `index.html`, obrazy i fonty osadzone).

- Deploy: Cloudflare Pages, integracja Git. Każdy push do `main` publikuje stronę.
- Ustawienia w Cloudflare: framework preset `None`, build command pusty, output directory `/`.
- Prototyp ma blokadę indeksowania (`noindex`, `robots.txt`), a formularze jeszcze niczego nie wysyłają.
