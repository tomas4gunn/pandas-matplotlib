# Semana 6 — ¿Llega a playoffs? (NFL)

Predicción de qué equipos de la NFL llegan a playoffs usando solo los primeros 9 partidos de la temporada regular. Se comparan regresión logística, árbol de decisión y KNN.

## Estructura
- `Datos/nfl_games.csv`: resultados de todos los partidos de la NFL (fuente: [nflverse/nfldata](https://github.com/nflverse/nfldata), `games.csv`).
- `Notebooks/Semana6_NFL_Playoffs_Roa_Tomas.ipynb`: análisis completo, con salidas.

## Resumen
- Una fila por equipo y temporada (2002–2025). Etiqueta: jugó o no playoffs.
- Entrenamiento 2002–2018, prueba 2019–2025 (separación por tiempo).
- Los tres modelos aciertan ~81 % (línea base: 57 %). El factor decisivo es el porcentaje de victorias.

## Cómo correrlo
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Notebooks/Semana6_NFL_Playoffs_Roa_Tomas.ipynb
```
