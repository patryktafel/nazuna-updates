# Nazuna

Przeglądarka internetowa na silniku Chromium, stawiająca na prywatność i szybkość. Tworzona solo przez [Tafel](https://github.com/patryktafel).

## Dlaczego Nazuna

- **Prywatność jako domyślne ustawienie.** Wbudowany bloker reklam i skryptów śledzących (bez instalowania rozszerzeń), utrudnianie odcisku przeglądarki (canvas, WebGL, Web Audio), blokowanie ciasteczek podmiotów trzecich, DNS przez HTTPS, ukrywanie lokalnego adresu IP w WebRTC i ostrzeżenia przed znanymi złośliwymi domenami - włączone od razu, bez grzebania w ustawieniach.
- **Szybka i lekka.** Karty w tle same usypiają, żeby nie zjadały RAM-u i baterii.
- **Bez zbędnego balastu.** Zero telemetrii, zero kont, zero "chmury" - dane trzymane lokalnie, na Twoim dysku.
- **Zgodna z Chromium.** Strony i rozszerzenia ze sklepu Chrome działają tak, jak powinny.

## Pobieranie

Najnowsza wersja (Windows): [Releases](https://github.com/patryktafel/nazuna-updates/releases/latest) - instalator `.exe`, aktualizuje się sam w tle.

## Czym jest to repozytorium

To repo jest publiczne, ale **nie zawiera kodu źródłowego przeglądarki** - ten znajduje się w osobnym, prywatnym repozytorium. Jego jedyna rola to hosting wydań (GitHub Releases), z których korzysta wbudowany mechanizm automatycznych aktualizacji (`electron-updater`) w zainstalowanej wersji Nazuny. Każde wydanie zawiera instalator (`.exe`) oraz plik `latest.yml` z metadanymi, które przeglądarka sama sprawdza w tle.
