# Predicción de Ventas Globales de Videojuegos

Proyecto final de Ciencias de Datos usando metodología CRISP-DM.

**Problema:** Regresión para predecir `global_sales_million` (ventas globales en millones de USD) a partir de características del juego, plataforma, género, publisher y tendencias anuales.

**Dataset:** Video Game Sales & Metacritic Intelligence 1980–26

    - 50,000 registros × 35 variables (más 4 tablas auxiliares con 71 columnas post-merge).
    - src: https://www.kaggle.com/datasets/meruvakodandasuraj/video-game-sales-and-metacritic-intelligence-198026

## 👥 EQUIPO

| Nombre Completo       | Código  | Rol            | Correo Electrónico       |
|-----------------------|---------|----------------|--------------------------|
| Dilan Mauricio Lemos       | 202359416 | [Colaborador] | [dilan.lemos@correounivalle.edu.co]|
| Jaime Andrés Noreña        | 202359523  | [Colaborador]  | [jaime.norena@correounivalle.edu.co]|
| Diego Fernando Lenis        | 202359540  | [Colaborador]  | [lenis.diego@correounivalled.edu.co]|
| Juan José Restrepo Ávalo    | 202359517  | [Colaborador]  | [juan.restrepo.avalo@correounivalle.edu.co]|



**Modelos comparados:**
- Random Forest Regressor
- MLP Regressor (red neuronal)
- Gradient Boosting Regressor

**Mejor modelo:** Gradient Boosting (R² ≈ 0.70 en test)

**Entregables:**
- `gamess.ipynb` — Notebook reproducible con todo el pipeline CRISP-DM
- `datasets/` — Datasets originales (games.csv + tablas auxiliares)
- Artículo en PDF
- Presentación oral 
