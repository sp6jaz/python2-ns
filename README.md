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
zjazd-03-cz1/   ← zjazd 3, część 1 (NumPy)
...
skrypt/          ← skrypt do samodzielnej nauki
```

Zajęcia odbywają się **co drugi zjazd** (zjazdy nieparzyste). Każdy zjazd obejmuje wykład + laboratorium w dwóch częściach. Materiały pojawiają się **zjazd po zjeździe** zgodnie z harmonogramem.

## Harmonogram — studia niestacjonarne (5 spotkań, co drugi zjazd)

| Zjazd | Temat |
|-------|-------|
| Zjazd 1 cz. 1 | Warsztat pracy analityka — Git, Markdown, VS Code |
| Zjazd 1 cz. 2 | Wprowadzenie do analizy danych — pipeline, Jupyter |
| Zjazd 3 cz. 1 | NumPy — podstawy |
| Zjazd 3 cz. 2 | NumPy — zaawansowane |
| Zjazd 5 cz. 1 | Pandas — intro, Series, DataFrame |
| Zjazd 5 cz. 2 | Pandas — selekcja, filtrowanie, czyszczenie |
| Zjazd 7 cz. 1 | Pandas — łączenie, agregacja + Matplotlib |
| Zjazd 7 cz. 2 | Seaborn, dashboardy + statystyka opisowa |
| Zjazd 9 cz. 1 | Statystyka — testy hipotez + zaawansowane biblioteki |
| Zjazd 9 cz. 2 | LLM i AI w analizie danych + podsumowanie |

### Logika kursu

| Zjazd | Rola w kursie | Co umiesz po tym bloku |
|-------|---------------|------------------------|
| 1 | Warsztat + Panorama | Git, VS Code, venv, pipeline od pytania do decyzji |
| 3 | Fundament | NumPy — szybkie obliczenia na tablicach danych |
| 5 | Rdzeń kursu | Pandas — od wczytania danych po filtrowanie i czyszczenie |
| 7 | Rdzeń + Wizualizacja | Agregacja, wykresy, dashboardy, statystyka opisowa |
| 9 | Statystyka + AI | Testy hipotez, scikit-learn, LLM, podsumowanie semestru |

## Szybki start

```bash
# 1. Zainstaluj narzędzia (szczegóły w materiałach zjazd-01-cz1)
# Python: python.org | uv: astral.sh/uv | VS Code: code.visualstudio.com | Git: git-scm.com

# 2. Sklonuj to repo
git clone https://github.com/sp6jaz/python2-ns.git
cd python2-ns

# 3. Utwórz środowisko
uv venv
.venv\Scripts\Activate.ps1

# 4. Zainstaluj pakiety
uv pip install numpy pandas matplotlib seaborn scipy jupyter ipykernel
```

## Kontakt

- Moodle: [link do kursu]
- GitHub prowadzącego: [sp6jaz](https://github.com/sp6jaz)
