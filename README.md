# ANTENNA OPTIMIZER RF V10

Plataforma en Python para simular y optimizar la ubicación y orientación de antenas 4G/5G en entornos urbanos mediante modelado radioeléctrico, datos geográficos y el algoritmo PSO.

## Autores

- Jeisson Estiven Cortés Anotnio - 2225004

## Objetivo

Encontrar configuraciones de antenas que mejoren la cobertura, el SINR y el throughput estimado, considerando el terreno, la propagación de la señal y la distribución de los puntos de demanda.

## Tecnologías y métodos

- **Simulación RF:** modelos de propagación, potencia recibida, interferencia, SINR y throughput.
- **Optimización:** Particle Swarm Optimization (PSO) para buscar ubicaciones y orientaciones de antenas.
- **Machine Learning:** Regresión Lineal y Random Forest para estimar el throughput.
- **Análisis no supervisado:** PCA y t-SNE para explorar y visualizar los datos RF.
- **Visualización geográfica:** mapas RF y entorno urbano 3D con datos de terreno y OpenStreetMap.

## Datos utilizados

El dataset RF se genera dinámicamente durante las iteraciones del PSO. Incluye variables como distancia al centro, altitud, pérdida de trayecto, potencia recibida, interferencia, SINR y throughput estimado.

## Ejecución

El proyecto incluye un notebook para Google Colab:

1. Abrir `AntennaOptimizerRF_v10_Colab.ipynb` en Google Colab.
2. Configurar la ciudad y los parámetros de antenas y PSO.
3. Ejecutar las celdas en orden para generar la simulación y sus resultados.

## Resultados

La ejecución puede generar mapas RF interactivos, una visualización 3D, gráficas de convergencia, análisis de Machine Learning, archivos CSV, una base de datos SQLite y un resumen ejecutivo.
