# # Cobertura de Museos en México: Análisis Geoespacial

Investigación exploratoria de datos geoespaciales enfocada en evaluar la distribución de museos a lo largo de los estados de México, identificar regiones con menor presencia cultural y aportar evidencia cartográfica para priorizar nuevas sedes[cite: 4, 5].

## Líneas de indagación
- **Estructuración espacial:** Construcción de `GeoDataFrame` a partir de geometrías estatales en GeoJSON y registros georreferenciados de museos (`EPSG:4326`)[cite: 4, 5].
- **Evaluación de cobertura territorial:** Contraste entre la delimitación estatal y la ubicación de museos para ubicar zonas con menor disponibilidad[cite: 4, 5].
- **Visualización cartográfica:** Generación de mapas claros orientados a la interpretación rápida de brechas y prioridades de expansión[cite: 4, 5].

## Stack y librerías
- **Entorno:** Python y Google Colab[cite: 4, 5].
- **Librerías:**
  - `pandas`: tratamiento de datos tabulares[cite: 5].
  - `geopandas`: procesamiento de geometrías, CRS (`EPSG:4326`) y análisis geoespacial[cite: 5].
  - `matplotlib` (`matplotlib.pyplot`): representación visual y composición de mapas[cite: 5].
