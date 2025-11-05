# BI_T2 — Sismos en Chile (2012–2025)

**Objetivo:** Analizar el dataset de sismicidad en Chile usando **regresión**, **clasificación** y **clustering** para contrastar hipótesis de BI. Se incluyen EDA con **correlación**, métricas de evaluación (MAE, RMSE, R²; accuracy, precisión, recall, F1, matriz de confusión; silhouette y método del codo) y discusión de resultados.

**Dataset:** `seismic_data.csv` (fuente: CSN — Centro Sismológico Nacional). Variables típicas: fecha/hora, latitud, longitud, profundidad, magnitud (ajustar si difiere).
Licencia/diccionario: citar la fuente del CSN y condiciones de uso.

**Ejecución:**
```bash
python --version
# Python 3.10+ recomendado
pip install -r requirements.txt
jupyter notebook BI_T2_CardenasNicolas.ipynb
```

**Dependencias:** ver `requirements.txt`. Semillas fijadas con `random_state=42` cuando aplica.