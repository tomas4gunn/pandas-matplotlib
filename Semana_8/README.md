# Semana 8: Segmentación de clientes con K-Means

**Materia:** Aprendizaje Automático (Centro Politécnico Superior Malvinas Argentinas)
**Alumno:** Tomás Roa Gunn

## Qué hay en esta carpeta
- `Datos/dataset_segmentacion_clientes.csv`: dataset entregado en el campus (700 clientes).
- `Notebooks/Semana_8_Segmentacion_Clientes_KMeans_Roa_Tomas.ipynb`: análisis completo.

## Resumen
- Variables usadas (escaladas): frecuencia de compra, ticket promedio, tiempo en el sitio, sensibilidad a descuentos y tasa de devoluciones. Se excluyeron `noise_gauss` y `noise_uniform` (sin correlación con el resto).
- Se compararon k = 2 a 6 con método del codo y coeficiente de silueta.
- **Resultado:** 6 segmentos, que son tres perfiles de compra (ticket de ~90, ~180 y ~450 USD) divididos por devoluciones y sensibilidad a descuentos. El notebook describe el perfil de cada uno.

## Cómo reproducirlo
Python 3 con `pandas`, `numpy`, `matplotlib`, `seaborn` y `scikit-learn`. Abrir el notebook y ejecutar todas las celdas (semilla fija: 42).
