# Project Overview

Ten projekt to statyczna strona internetowa **Fazy Księżyca**, zbudowana w czystym **HTML i CSS** jako strona pokazowa (showcase). Celem strony jest zaprezentowanie podstawowej struktury HTML, prostego layoutu oraz czytelnej prezentacji treści edukacyjnych. Strona nie korzysta z danych w czasie rzeczywistym – skupia się na wyglądzie, semantyce i organizacji treści.

Główne cele projektu:

* Ćwiczenie podstawowej, semantycznej struktury HTML.
* Stworzenie przejrzystej strony informacyjnej o fazach Księżyca.
* Zastosowanie prostych stylów CSS (kolory, typografia, układ).
* Przygotowanie bazy, którą można później rozbudować o JavaScript (np. aktualna faza Księżyca).

Projekt składa się z jednego pliku: **index.html**.

---

## HTML Structure Decisions

Strona rozpoczyna się standardową deklaracją dokumentu i podstawową sekcją `<head>`:

```html
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Fazy Księżyca</title>
</head>
```

### Główne sekcje strony

**Nagłówek (header)**
Zawiera tytuł strony i krótkie wprowadzenie. Pełni funkcję sekcji „hero”, która jasno komunikuje temat strony.

**Sekcja główna (main)**
W tej części znajdują się:

* opis czym są fazy Księżyca,
* lista głównych faz (Nów, Pierwsza kwadra, Pełnia, Ostatnia kwadra),
* krótkie ciekawostki astronomiczne.

Treść została podzielona za pomocą nagłówków `<h2>` i list `<ul>`, co poprawia czytelność i hierarchię informacji.

**Stopka (footer)**
Zawiera prostą informację o autorze strony.

Struktura HTML jest prosta i czytelna, ale w przyszłości może zostać jeszcze bardziej ustrukturyzowana przy użyciu dodatkowych elementów semantycznych, takich jak `<section>` czy `<article>`.

---

## CSS Strategy

Style zostały umieszczone bezpośrednio w pliku HTML w sekcji `<style>`. Najważniejsze decyzje stylistyczne:

* Użycie systemowej czcionki dla czytelności.
* Jasne tło strony z kontrastującymi sekcjami.
* Wyśrodkowany nagłówek i karta z treścią główną.
* Delikatne cienie i zaokrąglenia, aby strona wyglądała nowocześnie.

Przykładowe decyzje projektowe:

* Sekcja główna ma maksymalną szerokość, aby tekst nie był zbyt rozciągnięty na dużych ekranach.
* Kolory zostały dobrane tak, aby nawiązywały do spokojnego, „kosmicznego” klimatu.

W przyszłości style mogą zostać przeniesione do osobnego pliku **style.css**.

---

## Tool Usage

Podczas pracy nad projektem wykorzystano:

* **Edytor kodu** – do pisania i edycji pliku `index.html`.
* **Przeglądarkę internetową** – do testowania wyglądu strony.
* **Narzędzia deweloperskie przeglądarki** – do sprawdzania układu i drobnych poprawek stylów.
* **Asystenta AI** – do pomocy przy strukturze strony, treści opisowej oraz organizacji kodu.

---

## Challenges & Solutions

**1. Czytelna prezentacja treści edukacyjnej**
Wyzwanie: uniknięcie „ściany tekstu”.
Rozwiązanie: podział treści na krótkie akapity, listy punktowane i nagłówki.

**2. Prostota i estetyka**
Wyzwanie: stworzenie estetycznej strony bez zaawansowanych technologii.
Rozwiązanie: użycie podstawowych właściwości CSS (padding, margin, box-shadow, border-radius).

**3. Dobór kolorów**
Wyzwanie: zachowanie czytelności przy jednoczesnym klimacie astronomicznym.
Rozwiązanie: jasne tło i ciemniejszy nagłówek, bez agresywnych kontrastów.

---

## Academic / Technical Sources

* **MDN Web Docs** – dokumentacja HTML i CSS.
* Materiały edukacyjne dotyczące astronomii (fazy Księżyca).
* Ogólne poradniki web‑designu dotyczące czytelności i hierarchii treści.

---

## Future Improvements

Planowane ulepszenia projektu:

* Dodanie JavaScript do wyświetlania **aktualnej fazy Księżyca**.
* Rozszerzenie strony o ilustracje lub animacje cyklu księżycowego.
* Zastosowanie bardziej semantycznej struktury HTML.
* Wersja responsywna dla urządzeń mobilnych.
* Przeniesienie stylów do zewnętrznego pliku CSS.

Po tych zmianach strona może stać się nie tylko projektem pokazowym, ale także prostą aplikacją edukacyjną.
