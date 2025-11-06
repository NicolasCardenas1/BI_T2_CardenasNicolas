**Objetivo:** Analizar y modelar patrones sísmicos en Chile (2012–2025) aplicando tres técnicas de ML —regresión, clasificación y clustering— para responder hipótesis de BI; se usa el dataset seismic_data.csv (CSN/Chile), con variables *Latitude, Longitude, Depth, Magnitude* y una etiqueta derivada zona_sismica. 
**Ejecución:** abrir `BI_T2_CardenasNicolas.ipynb` y ejecutar *Run All*; si faltan dependencias, 
**Opción A (recomendada):** en la primera celda correr `%pip install -r requirements.txt`; **Opción B:** crear venv y usar `pip install -r requirements.txt` (en **CMD**: `.\.venv\Scripts\activate.bat`); 
**Opción C (opcional):** crear entorno con Conda usando `environment.yml` si se incluye. 
**Dependencias y versión de Python:** ver `requirements.txt` (pandas 2.3.3, numpy 2.3.4, matplotlib 3.10.7, seaborn 0.13.2, scikit-learn 1.7.2, nbformat 5.10.4, ipykernel 7.1.0, jupyter 1.1.1); probado en **Python 3.12.10**. 
El notebook guarda figuras en `figuras/` y fija semillas (`random_state=42`) para reproducibilidad.
