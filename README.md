# Proyecto-Final-ADTD---F1-Dashboard
## Análisis de Datos de Fórmula 1

**Curso:** Análisis de Datos y Toma de Decisiones para Computación  
**Profesor:** Javier Sánchez Galán  
**Grupo:** 1IL-133 | I Semestre 2026  
**Universidad:** Universidad Tecnológica de Panamá

---

## Integrantes
- Esquivel, Kevin
- Simmons, Abigail
- Solis, Luis
- Villarreal, Sergio

---

## Descripción del proyecto
Análisis de datos de extremo a extremo sobre una base de datos relacional
de Fórmula 1 con 12 tablas e información histórica de 1950 a 2025,
generada con Mockaroo. Se ejecutaron etapas de ingesta, limpieza,
análisis exploratorio, consultas SQL, clustering K-means y dashboard
público, todo en Databricks Free Edition, todo el proceso está documentado en 6 notebooks.

---

## Estructura de notebooks

- 01_ingesta_datos : Carga de los 12 CSVs al Volume y registro como tablas Delta
- 02_limpieza_datos : Verificación de nulos, duplicados, tipos y rangos numéricos
- 03_analisis_exploratorio : Estadísticas descriptivas, distribuciones y rankings de escuderías
- 04_analisis_sql : 6 consultas SQL sobre rendimiento de pilotos, patrocinio y circuitos
- 05_analitica_avanzada : Clustering K-means (k=3) de las 21 escuderías
- 06_preparacion_dashboard : Tablas resumen para el dashboard público

