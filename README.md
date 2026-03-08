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
zjazd-02-cz1/   ← zjazd 2, część 1
...
skrypt/          ← skrypt do samodzielnej nauki
```

Każdy zjazd obejmuje wykład + laboratorium. Materiały pojawiają się **zjazd po zjeździe** zgodnie z harmonogramem.

## Harmonogram — studia niestacjonarne (zjazdy)

| Zjazd | Temat |
|-------|-------|
| Zjazd 1 cz. 1 | Warsztat pracy analityka — Git, Markdown, VS Code |
| Zjazd 1 cz. 2 | Wprowadzenie do analizy danych — pipeline, Jupyter |
| Zjazd 2 cz. 1 | NumPy — podstawy |
| Zjazd 2 cz. 2 | NumPy — zaawansowane |
| Zjazd 3 cz. 1 | Pandas — Series i DataFrame |
| Zjazd 3 cz. 2 | Pandas — selekcja i filtrowanie |
| Zjazd 4 cz. 1 | Pandas — czyszczenie danych |
| Zjazd 4 cz. 2 | Pandas — łączenie i agregacja |
| Zjazd 5 cz. 1 | Matplotlib — podstawy |
| Zjazd 5 cz. 2 | Matplotlib + Seaborn — zaawansowane |
| Zjazd 6 cz. 1 | Statystyka opisowa |
| Zjazd 6 cz. 2 | Statystyka — rozkłady i testy |
| Zjazd 7 cz. 1 | Zaawansowane biblioteki |
| Zjazd 7 cz. 2 | LLM i AI w analizie danych |
| Zjazd 8 | Podsumowanie i prezentacje |

### Logika kursu

| Zjazd | Rola w kursie | Co umiesz po tym bloku |
|-------|---------------|------------------------|
| 1 | Warsztat + Panorama | Git, VS Code, venv, pipeline od pytania do decyzji |
| 2 | Fundament | NumPy — szybkie obliczenia na tablicach danych |
| 3 | Rdzeń kursu | Pandas — wczytanie danych, selekcja i filtrowanie |
| 4 | Rdzeń kursu | Pandas — czyszczenie, łączenie i agregacja |
| 5 | Wizualizacja | Matplotlib + Seaborn — wykresy i dashboardy |
| 6 | Statystyka | Statystyka opisowa + testy hipotez |
| 7 | Rozszerzenia + AI | scikit-learn, Plotly, LLM i API modeli |
| 8 | Zamknięcie | Prezentacje mini-projektów, podsumowanie semestru |

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
