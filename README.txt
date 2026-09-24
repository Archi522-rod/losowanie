MASZYNA LOTTO - aplikacja na telefon (PWA)

Zawartosc: index.html, manifest.webmanifest, sw.js, folder icons/.
Wszystkie pliki musza trafic do tego samego folderu na serwerze (HTTPS).

OPCJA A: Netlify Drop (najszybciej, bez konta git)
1. Wejdz na app.netlify.com/drop i zaloguj sie.
2. Przeciagnij rozpakowany folder z plikami na strone.
3. Dostaniesz adres https://....netlify.app.

OPCJA B: GitHub Pages
1. Utworz repozytorium (public) i wgraj wszystkie pliki na glowna galaz.
2. Settings > Pages > Deploy from a branch > main / (root).
3. Adres: https://TWOJA-NAZWA.github.io/NAZWA-REPO/

INSTALACJA NA TELEFONIE
- Android (Chrome): otworz adres, menu ⋮ > "Zainstaluj aplikacje" (lub "Dodaj do ekranu glownego").
- iPhone (Safari): otworz adres, Udostepnij > "Dodaj do ekranu poczatkowego".
Po pierwszym otwarciu aplikacja dziala tez bez internetu.

AKTUALIZACJA: po podmianie plikow zmien w sw.js numer w const CACHE='lotto-v1' (np. na v2),
inaczej telefon moze pokazywac stara wersje.
