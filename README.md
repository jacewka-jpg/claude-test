# claude-test

Prosta strona-wizytówka w jednym pliku `index.html`.

## Zawartość

- **Awatar** z inicjałami
- **Imię i nazwisko** oraz stanowisko
- **Krótki opis**
- **Dane kontaktowe**: e-mail (`mailto:`), telefon (`tel:`), strona WWW i lokalizacja

## Cechy

- Czysty HTML + CSS, bez zależności i bez JavaScriptu
- Responsywny układ – karta wyśrodkowana, działa na telefonach i komputerach
- Automatyczny tryb ciemny (`prefers-color-scheme: dark`)
- Kolory zdefiniowane jako zmienne CSS w `:root`, łatwe do zmiany

## Jak uruchomić

Otwórz plik `index.html` w przeglądarce. Możesz też uruchomić lokalny serwer:

```bash
python3 -m http.server 8000
```

i wejść na <http://localhost:8000>.

## Personalizacja

Dane w `index.html` są przykładowe – podmień imię, stanowisko, opis i dane kontaktowe na własne. Kolor akcentu zmienisz w zmiennej `--accent`.
