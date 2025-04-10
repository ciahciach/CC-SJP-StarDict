# 🇵🇱 Słownik Języka Polskiego CC-SJP (Format StarDict)

[![License: CC BY-SA 3.0](https://img.shields.io/badge/License-CC%20BY--SA%203.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/3.0/)

Ten projekt zawiera **Słownik Języka Polskiego CC-SJP**, pierwotnie stworzony przez **[PM Krol](https://github.com/PMKrol/CC-SJP)**, przekonwertowany do formatu **StarDict**.

Konwersja została wykonana w celu umożliwienia korzystania ze słownika w aplikacjach obsługujących format StarDict, w szczególności na czytnikach e-booków (takich jak Kindle, Kobo, PocketBook) z zainstalowanym oprogramowaniem **[KOReader](https://koreader.rocks/)**.

**Ważna uwaga:** Jest to jedynie **konwersja** istniejącego słownika. Cała praca merytoryczna została wykonana przez oryginalnego autora.

## Instalacja (KOReader)

1.  Podłącz czytnik do komputera.
2.  Pobierz pliki słownika z tego repozytorium (możesz sklonować repozytorium lub pobrać pliki pojedynczo). Potrzebujesz wszystkich czterech plików:
    *   `CC-SJP.dict`
    *   `CC-SJP.idx`
    *   `CC-SJP.ifo`
    *   `CC-SJP.syn`
3.  Skopiuj **wszystkie cztery** pliki (`.dict`, `.idx`, `.ifo`, `.syn`) do folderu słowników KOReader na swoim czytniku. Zazwyczaj jest to ścieżka: `koreader/data/dict/`.
4.  Uruchom KOReader. Słownik powinien być teraz dostępny do wyboru i użytku podczas czytania.

*(Dla innych aplikacji obsługujących format StarDict, skopiuj pliki do odpowiedniego katalogu ze słownikami zgodnie z dokumentacją danej aplikacji.)*

## Pliki w repozytorium

Repozytorium zawiera następujące pliki w formacie StarDict:

*   `CC-SJP.dict` - Główny plik słownika z definicjami.
*   `CC-SJP.idx` - Indeks słów dla szybkiego wyszukiwania.
*   `CC-SJP.ifo` - Plik informacyjny słownika (metadane).
*   `CC-SJP.syn` - Plik synonimów (jeśli dotyczy/wygenerowany przez konwersję).

**Uwaga:** Pliki `.dict` i `.syn` są zarządzane za pomocą **Git LFS** ze względu na ich duży rozmiar.

## Źródło i Licencja

*   **Oryginalny projekt słownika:** [CC-SJP na GitHubie](https://github.com/PMKrol/CC-SJP) (Autor: PM Krol)
*   **Licencja:** [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/)
*   **Więcej informacji o CC-SJP:**
    *   [Strona projektu (archiwum)](http://cc-sjp.zabałaganionemiejsce.pl/)
    *   [Komentarz na SwiatCzytnikow.pl](https://swiatczytnikow.pl/slownik-jezyka-polskiego-dla-kindle-nowa-wersja-luty-2023/comment-page-1/#comment-1387094)

## Konwersja

*   Użyte narzędzie: [PyGlossary](https://github.com/ilius/pyglossary)

## Wesprzyj oryginalnego autora

Jeśli uważasz oryginalny słownik CC-SJP za wartościowy, rozważ wsparcie jego autora drobną darowizną:
➡️ [**paypal.me/sanzamoyski**](https://paypal.me/sanzamoyski)

---

Miłego korzystania!
