# Quiz — Zjazd 1 cz. 2 — Wprowadzenie do analizy danych

## Instrukcja
- 5 pytań, jednokrotny wybór
- Czas: 5 minut
- 2 pytania powtórkowe (cz. 1), 3 pytania nowe (cz. 2)

---

### Pytanie 1 (powtórka cz. 1)
Jaka jest prawidłowa kolejność kroków w Git?

A) commit → add → push
B) push → commit → add
C) add → commit → push
D) add → push → commit

---

### Pytanie 2 (powtórka cz. 1)
Co powinno znaleźć się w pliku `.gitignore`?

A) Pliki z kodem źródłowym
B) README.md
C) Katalog `.venv/` i pliki `__pycache__/`
D) Pliki requirements.txt

---

### Pytanie 3
Co zwraca metoda `df.describe()` w Pandas?

A) Listę kolumn w DataFrame
B) Podstawowe statystyki opisowe (średnia, min, max, kwartyle)
C) Pierwsze 5 wierszy danych
D) Typy danych w każdej kolumnie

---

### Pytanie 4
Jaka jest prawidłowa kolejność kroków w pipeline analitycznym?

A) Wizualizacja → Dane → Analiza → Pytanie → Decyzja
B) Pytanie → Dane → Analiza → Wizualizacja → Decyzja
C) Dane → Pytanie → Wizualizacja → Analiza → Decyzja
D) Analiza → Dane → Pytanie → Decyzja → Wizualizacja

---

### Pytanie 5
Dlaczego NumPy jest szybszy od list Pythona?

A) Bo jest napisany w Javie
B) Bo używa ciągłych bloków pamięci i zoptymalizowanych instrukcji procesora
C) Bo kompresuje dane
D) Bo działa tylko na małych zbiorach danych

---

## Odpowiedzi

| Pytanie | Odpowiedź | Wyjaśnienie |
|---------|-----------|-------------|
| 1 | C | add (staging) → commit (migawka) → push (wypchnij na GitHub). |
| 2 | C | .venv/ i __pycache__/ to pliki lokalne, nie powinny trafić do repo. |
| 3 | B | describe() zwraca count, mean, std, min, 25%, 50%, 75%, max. |
| 4 | B | Zaczynamy od pytania biznesowego, kończymy decyzją. |
| 5 | B | NumPy przechowuje dane w ciągłej pamięci i korzysta z operacji wektorowych (SIMD). |
