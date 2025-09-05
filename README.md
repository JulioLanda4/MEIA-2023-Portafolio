# MEIA 2023 — Portafolio de Proyectos en Inteligencia Artificial

Este repositorio reúne los materiales, ejercicios y proyectos desarrollados durante el **Macro Entrenamiento en Inteligencia Artificial 2023 (MEIA 2023)**.  
El objetivo es mostrar, de manera organizada y reproducible, el aprendizaje adquirido en ciencia de datos, machine learning y análisis aplicado.

## 📂 Estructura

```bash
MEIA-2023-Portafolio/
├── data/             # datasets
├── notebooks/        # notebooks Jupyter
├── reportes/          # resultados exportados
├── requirements.txt
└── README.md
```


## 📘 Contenido del portafolio

### 🔹 Reto 1: Detección de Anomalías en Datos de Alta Dimensión
- Reducción de dimensionalidad con PCA, t-SNE y UMAP.
- Detección de anomalías usando KMeans, KNN, LOF e Isolation Forest.
- Optimización de hiperparámetros con algoritmos genéticos (DEAP).

### 🔹 Reto 2: Análisis de Contaminantes Atmosféricos
- Exploración de datos horarios de contaminantes en 2022.
- Tratamiento de datos faltantes y visualización temporal.
- Comparación entre estaciones y parámetros de calidad del aire.

### 🔹 Reto 3: Uso de Codones (Bioinformática)
- Análisis de frecuencias de codones en datos genómicos.
- Aplicación de reducción de dimensionalidad para agrupar organismos.
- Discusión sobre patrones biológicos encontrados.

### 🔹 Exploración Geográfica de Ciudades de México
- Uso de coordenadas y distancias entre ciudades.
- Visualizaciones espaciales con Python.
- Aplicaciones de clustering geográfico.

### 🔹 Proyecto Final: Anomalías de SO₂ en CDMX (2008 vs 2011)
- Ingesta y limpieza de dos datasets horarios de SO₂.
- Ingeniería de características diarias (promedio y p95 por estación).
- Reducción de dimensionalidad (PCA, t-SNE, UMAP).
- Detección de anomalías con múltiples métodos y comité.
- Exportación de ranking de días anómalos y reportes.
- Propuesta de extensiones: optimización evolutiva, dashboard interactivo.

## ⚙️ Reproducibilidad

1. Crear entorno virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # En Windows: .venv\Scripts\activate
   pip install -r requirements.txt
