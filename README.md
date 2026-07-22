<p align="center">
  <img src="https://raw.githubusercontent.com/lektuarium/lektuarium/main/profile/logo_lektuarium_pl_rect.jpg" alt="Lektuarium Logo" width="400" />
</p>

<h1 align="center">Witaj w organizacji Lektuarium</h1>

<p align="center">
  <b>Tworzę otwarty ekosystem dla miłośników książek, czytelników, bibliotekarzy i bibliofilów.</b><br>
  Lektuarium to nowoczesna platforma do cyfrowego katalogowania zbiorów, recenzowania oraz wymiany książek i myśli.
</p>

<p align="center">
  <a href="https://lektuarium.pl"><b>Wiedza i Serwis (lektuarium.pl)</b></a> •
  <a href="#jak-możesz-pomóc-dołącz-do-projektu"><b>Dołącz do projektu</b></a> •
  <a href="#nasz-stack-technologiczny"><b>Stack Technologiczny</b></a> •
  <a href="#kontakt-i-społeczność"><b>Kontakt</b></a>
</p>

---

## Moja Misja

Chcę dać czytelnikom pełną kontrolę nad ich domowymi bibliotekami, ułatwić odkrywanie nowych lektur oraz stworzyć przestrzeń do nawiązywania wartościowych relacji w oparciu o wspólne pasje czytelnicze. Belferstwo i komercyjny chaos zastępuję nowoczesnym designem, otwartością danych i dbałością o prywatność oraz doświadczenie użytkownika.

---

## Jak zacząć korzystać z Lektuarium?

* **Odwiedź serwis:** Zarejestruj się na [Lektuarium.pl](https://lektuarium.pl) i zacznij prowadzić cyfrowy spis własnych zbiorów.
* **Uruchom własną instancję:** Cały kod źródłowy systemu jest dostępny open-source. Możesz postawić lokalną wersję deweloperską przy użyciu Docker Compose:
  ```bash
  git clone https://github.com/lektuarium/lektuarium.pl.git
  cd lektuarium.pl
  docker-compose up --build
  ```
  Aplikacja frontendowa będzie dostępna pod `http://localhost:3000`, a API Django pod `http://localhost:8000`.

---

## Jak możesz pomóc? Dołącz do projektu!

Lektuarium rozwija się dzięki zaangażowaniu społeczności. Niezależnie od tego, czy programujesz, pracujesz w bibliotece, projektujesz interfejsy, czy po prostu kochasz książki – masz realny wpływ na kształt platformy.

### 1. Dla Bibliotekarzy i Bibliotekarek
Wiedza bibliotekoznawcza jest kluczowa dla jakości danych w Lektuarium. Jak możesz pomóc?
* **Standaryzacja danych bibliograficznych:** Pomoc przy weryfikacji i porządkowaniu haseł wzorcowych, klasyfikacji dziedzinowej (UKD/UDC) oraz poprawności opisów wydań.
* **Metadane i standardy:** Doradztwo w zakresie integracji ze standardami bibliotecznymi (MARC21, Dublin Core, NUKAT/KHW) oraz obsługi unikalnych wydań i białych kruków.
* **Kuratela treści i rekomendacje:** Tworzenie kanonów czytelniczych, zestawień tematycznych oraz merytoryczna weryfikacja bazy autorów i dzieł.

### 2. Dla Programistów (Backend & Frontend)
* **Wybierz zgłoszenie:** Przejrzyj zakładkę [Issues](https://github.com/lektuarium/lektuarium.pl/issues) i poszukaj zadań oznaczonych etykietą `good first issue` lub `help wanted`.
* **Rozwijaj funkcje:** Pomóż mi budować wyszukiwarkę książek, moduły wymiany, integracje z zewnętrznymi bazami danych (np. ISBNdb, Google Books) oraz optymalizować algorytmy.
* **Dbaj o jakość:** Pisz testy jednostkowe i integracyjne oraz pomagaj w automatyzacji CI/CD.

### 3. Dla Designerów UI/UX
* Twórz nowoczesny, dostępny (a11y) i przejrzysty interfejs użytkownika.
* Projektuj przemyślane układy stron, czytelny system wizualny oraz funkcjonalności ułatwiające przeglądanie obszernych katalogów.

### 4. Dla Testerów i Czytelników
* **Testuj i zgłaszaj błędy:** Znalazłeś usterkę lub coś działa nieintuicyjnie? Otwórz [New Issue](https://github.com/lektuarium/lektuarium.pl/issues/new) – każdy detal ma znaczenie.
* **Proponuj nowe funkcjonalności:** Masz pomysł na usprawnienie cyfrowej biblioteki? Podziel się nim w zgłoszeniach.

---

## Stack Technologiczny

Stawiam na nowoczesne, wydajne i sprawdzone rozwiązania:

| Warstwa | Technologie |
|---|---|
| **Frontend** | Next.js 16 (React 19), TypeScript, Tailwind CSS 4, Vitest, Playwright |
| **Backend** | Django 5.2+, Python 3.12, PostGIS, Celery, Redis, Meilisearch |
| **DevOps & CI/CD** | Docker, Nginx, GitHub Actions, Watchtower, Honeybadger |

---

## Kontakt i Społeczność

* **Strona główna:** [lektuarium.pl](https://lektuarium.pl)
* **Kontakt e-mail:** [info@lektuarium.pl](mailto:info@lektuarium.pl)
* **GitHub Organization:** [@lektuarium](https://github.com/lektuarium)

Stwórzmy razem najlepsze miejsce w sieci dla książek i czytelników!
