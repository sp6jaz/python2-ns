# Programowanie w języku Python II — studia niestacjonarne

**Politechnika Opolska, WEAiI**
**Kierunek:** Analityka danych w biznesie, semestr 2
**Prowadzący:** dr hab. inż. Jarosław Zygarlicki

## O kursie

Kurs uczy praktycznego wykorzystania Pythona w analizie danych biznesowych. Poznasz profesjonalne narzędzia i biblioteki używane w branży.

## Narzędzia

| Narzędzie | Do czego |
|-----------|----------|
| Python 3.10+ | język programowania |
| uv | menedżer pakietów (szybszy od pip) |
| VS Code | edytor + Jupyter + Git |
| Git + GitHub | kontrola wersji, portfolio |

## Struktura materiałów

```
zjazd-01-cz1/   ← zjazd 1, część 1 (warsztat pracy)
zjazd-01-cz2/   ← zjazd 1, część 2 (pipeline analityczny)
zjazd-03-cz1/   ← zjazd 3, część 1
...
skrypt/          ← skrypt do samodzielnej nauki
```

Zajęcia odbywają się **co drugi zjazd** (zjazdy nieparzyste). Każdy zjazd obejmuje wykład + laboratorium w dwóch częściach. Materiały pojawiają się **zjazd po zjeździe** zgodnie z harmonogramem.

## Harmonogram — studia niestacjonarne (zjazdy)

| Zjazd | Temat |
|-------|-------|
| Zjazd 1 cz. 1 | Warsztat pracy analityka — Git, Markdown, VS Code |
| Zjazd 1 cz. 2 | Wprowadzenie do analizy danych — pipeline, Jupyter |
| Zjazd 3 cz. 1 | NumPy — podstawy |
| Zjazd 3 cz. 2 | NumPy — zaawansowane |
| Zjazd 5 cz. 1 | Pandas — Series i DataFrame |
| Zjazd 5 cz. 2 | Pandas — selekcja i filtrowanie |
| Zjazd 7 cz. 1 | Pandas — czyszczenie danych |
| Zjazd 7 cz. 2 | Pandas — łączenie i agregacja |
| Zjazd 9 cz. 1 | Matplotlib — podstawy |
| Zjazd 9 cz. 2 | Matplotlib + Seaborn — zaawansowane |
| Zjazd 11 cz. 1 | Statystyka opisowa |
| Zjazd 11 cz. 2 | Statystyka — rozkłady i testy |
| Zjazd 13 cz. 1 | Zaawansowane biblioteki |
| Zjazd 13 cz. 2 | LLM i AI w analizie danych |
| Zjazd 15 | Podsumowanie i prezentacje |

### Logika kursu

| Zjazd | Rola w kursie | Co umiesz po tym bloku |
|-------|---------------|------------------------|
| 1 | Warsztat + Panorama | Git, VS Code, venv, pipeline od pytania do decyzji |
| 3 | Fundament | NumPy — szybkie obliczenia na tablicach danych |
| 5 | Rdzeń kursu | Pandas — wczytanie danych, selekcja i filtrowanie |
| 7 | Rdzeń kursu | Pandas — czyszczenie, łączenie i agregacja |
| 9 | Wizualizacja | Matplotlib + Seaborn — wykresy i dashboardy |
| 11 | Statystyka | Statystyka opisowa + testy hipotez |
| 13 | Rozszerzenia + AI | scikit-learn, Plotly, LLM i API modeli |
| 15 | Zamknięcie | Prezentacje mini-projektów, podsumowanie semestru |

## Szybki start

```bash
# 1. Zainstaluj narzędzia (szczegóły w materiałach zjazd-01-cz1)
# Python: python.org | uv: astral.sh/uv | VS Code: code.visualstudio.com | Git: git-scm.com

# 2. Sklonuj to repo
git clone https://github.com/sp6jaz/python2-ns.git
cd python2-ns

# 3. Utwórz środowisko
uv venv
source .venv/bin/activate       # Linux/macOS
# .venv\Scripts\Activate.ps1    # Windows

# 4. Zainstaluj pakiety
uv pip install numpy pandas matplotlib seaborn scipy jupyter ipykernel
```

## Kontakt

- Moodle: [link do kursu]
- GitHub prowadzącego: [sp6jaz](https://github.com/sp6jaz)
