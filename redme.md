# Dokumentacja Projektu HTML/CSS

Ten plik krótko opisuje 3 największe gwiazdozbiory.
Poniżej znajdują się szczegóły dotyczące wykorzystanych narzędzi oraz planów na przyszłość.

## Wykorzystane narzędzia

W projekcie używamy standardowych narzędzi. Głównym edytorem kodu jest
[Visual Studio Code](https://code.visualstudio.com/), który wspiera naszą pracę dzięki
rozszerzeniom takim jak Live Server.

Kod źródłowy jest wersjonowany przy użyciu Git, co pozwala na bezpieczne
wprowadzanie zmian i tworzenie na osobnych gałęziach.

## Plany rozwoju (To-Do List)

Poniżej znajduje się lista funkcjonalności, które planujemy wdrożyć w przyszłości.
Więcej informacji o składni Markdown można znaleźć w [oficjalnym przewocniku](https://www.markdownguide.org/).

- [x] Stworzenie struktury HTML (nav, main, footer)
- [x] Dodanie stylów CSS i tła
- [ ] Implementacja formularza kontaktowego
- [ ] Dopisanie komentarzy do trudniejszych fragmentów kodu


Przez niedopatrzenie nie wygenerowałem pliku log_album_1 przed mergem. Gdybym wygenerował ten plik przed użyciem --no-ff, historia byłaby płaska w scalaniu typu Fast-Forward. Użycie --no-ff w log_album_2 wymusiło stworzenie merge commit, co widać w logach jako rozwidlenie i ponowne złączenie linii grafu.

Użyłem polecenia git commit --amend. Pozwala ono na modyfikację ostatniego commita bez tworzenia nowego wpisu w historii. Zmiany z pliku html zostały dodane do poprzedniego commita. Zmienił się identyfikator commita, co oznacza, że git nadpisał tamtą wersję.