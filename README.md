# Orto

App per gestire un orto: mappa delle aiuole, colture, registro delle attività e cose da fare.
Pensata per il telefono, in italiano, funziona anche offline.

👉 Apri l'app: https://mavresfil.github.io/orto-app/

## Cosa fa
- Mappa dell'orto disegnabile (aiuole di forme diverse, vialetti, alberi, esposizione)
- Colture, registro e cose da fare, con avvisi di rotazione e stagione
- Catalogo delle colture per la zona di Bologna, guide e lavori del mese
- Meteo, gradi giorno, ore di sole e bilancio dell'acqua per aiuola
- Arcade: simulatore dell'orto negli anni, con stima del raccolto
- Più orti e più persone, sincronizzati tra i telefoni

## Come è fatta
HTML, CSS e JavaScript senza framework né build; PWA installabile.
Dati nel browser e sincronizzazione con Supabase. Meteo: [Open-Meteo.com](https://open-meteo.com/) (CC BY 4.0).

## Provarla in locale
```
python -m http.server 8000
```
poi apri http://localhost:8000/
