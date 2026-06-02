# Predicción de Ventas Globales de Videojuegos

Proyecto final de Ciencias de Datos usando metodología CRISP-DM.

**Problema:** Regresión para predecir `global_sales_million` (ventas globales en millones de USD) a partir de características del juego, plataforma, género, publisher y tendencias anuales.

**Dataset:** 50,000 registros × 35 variables (más 4 tablas auxiliares con 71 columnas post-merge).

**Modelos comparados:**
- Random Forest Regressor
- MLP Regressor (red neuronal)
- Gradient Boosting Regressor

**Mejor modelo:** Gradient Boosting (R² ≈ 0.70 en test)

**Entregables:**
- `gamess.ipynb` — Notebook reproducible con todo el pipeline CRISP-DM
- `datasets/` — Datasets originales (games.csv + tablas auxiliares)
- Artículo en PDF (pendiente)
- Presentación oral (pendiente)
