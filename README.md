# Leantime – Polish language (pl-PL)

Nieoficjalne polskie tłumaczenie systemu **Leantime** (testowane na wersji 3.5.12).

## Status
- ✔ większość interfejsu przetłumaczona
- ⚠ możliwe pojedyncze angielskie fallbacki (brakujące klucze)
- 🧪 aktywnie rozwijane

## Instalacja
1. Skopiuj plik `pl-PL.ini` do: app/Language/pl-PL.ini
2. Ustaw język:
- w panelu użytkownika **lub**
- w `.env`:
  ```
  LEAN_LANGUAGE=pl-PL
  ```
3. Wyczyść cache aplikacji oraz PHP OPCache

## Uwagi techniczne
- Plik używa komentarzy `;` (zgodne z parserem PHP `parse_ini_file`)


## Contribution
Pull requesty mile widziane – szczególnie:
- brakujące stringi
- korekty językowe
- spójność terminologii

---

## English
Unofficial Polish translation for Leantime 3.5.x.
