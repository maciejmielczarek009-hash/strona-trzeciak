# strona-trzeciak

Prototyp strony głównej trzeciak.pl (jeden plik `index.html`, obrazy i fonty osadzone).

- Deploy: Cloudflare Workers (static assets), integracja Git. Każdy push do `main` publikuje stronę.
- Pliki strony leżą w `public/`, konfiguracja w `wrangler.jsonc`. W Cloudflare: build command pusty, deploy command `npx wrangler deploy`, root directory `/`.
- Prototyp ma blokadę indeksowania (`noindex`, `robots.txt`), a formularze jeszcze niczego nie wysyłają.
