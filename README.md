# Proyecto: Análisis y Predicción de Ventas – Reckitt

![Logo Reckitt](https://upload.wikimedia.org/wikipedia/en/thumb/b/b8/Reckitt_logo.svg/419px-Reckitt_logo.svg.png?20231213060844) 

---

## Tabla de Contenido
1. [Introducción](#introducción-del-proyecto)  
2. [Limpieza y Transformación de Datos](#limpieza-y-transformación-de-datos)  
3. [Análisis Exploratorio de Datos (EDA) y Visualizaciones](#análisis-exploratorio-de-datos-eda-y-visualizaciones)  
4. [Segmentación de Productos o Regiones con Clustering](#segmentación-de-productos-o-regiones-con-clustering)  
5. [Análisis de Datos con SQL en SQLite](#análisis-de-datos-con-sql-en-sqlite)  
6. [Creación de un Dashboard en Power BI](#creación-de-un-dashboard-en-power-bi)  
7. [Predicción de Ventas con Machine Learning](#predicción-de-ventas-con-machine-learning)  
8. [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)  

---

## Introducción del Proyecto
**Contexto:**  
Optimizar decisiones estratégicas a partir de los datos de ventas de Reckitt.  

**Relevancia:**  
- Identificar tendencias de ventas.  
- Reconocer segmentos clave de clientes y productos.  
- Predecir ventas futuras para una planificación más eficiente.  

**Herramientas utilizadas:**  
- **Python:** Pandas, Seaborn, Matplotlib, Scikit-learn, statsmodels  
- **SQL:** SQL Server / SQLite  
- **Visualización:** Power BI  

---

## Limpieza y Transformación de Datos
**Objetivos:**  
- Cargar los datos desde archivos CSV/Excel.  
- Manejar valores nulos, duplicados e inconsistencias.  
- Normalizar formatos de fechas y categorías.  

---

## Análisis Exploratorio de Datos (EDA) y Visualizaciones
**Objetivos:**  
- Analizar la distribución de ventas.  
- Identificar tendencias, patrones y outliers.  
- Generar gráficos explicativos y comparativos.  

---

## Segmentación de Productos o Regiones con Clustering
**Objetivos:**  
- Aplicar **K-Means** para segmentar productos o regiones.  
- Determinar el número óptimo de clusters mediante el **método del codo**.  
- Interpretar patrones de rendimiento y comportamiento del mercado.  

---

## Análisis de Datos con SQL en SQLite
**Objetivos:**  
- Integrar los datos de ventas y dimensiones en una base de datos SQLite.  
- Ejecutar consultas clave para insights sobre ventas por categoría, segmento y productos.  
- Visualizar resultados para facilitar la interpretación.  

---

## Creación de un Dashboard en Power BI
- Dashboard interactivo para explorar ventas por categoría, producto y región.  
- Visualización de tendencias y comparaciones históricas.  

---

## Predicción de Ventas con Machine Learning
**Objetivos:**  
- Selección y justificación del modelo predictivo (ARIMA para series temporales).  
- Validación del modelo con datos históricos.  
- Generación de predicciones futuras de ventas.  

---

## Conclusiones y Recomendaciones
**Hallazgos clave:**  
- Una región domina el volumen de ventas totales.  
- Productos como Vanish y Lysol muestran mejor rendimiento.  
- Segmentación por clustering permitió identificar grupos de productos con características similares.  
- Tendencias mensuales muestran patrones estacionales útiles para ajustar producción e inventario.  

**Predicciones:**  
- **Vanish:** ventas relativamente constantes, ligeramente por debajo de valores históricos.  
- **Lysol:** ventas estables pero menores en magnitud.  
- Permiten anticipar inventario y ajustar estrategias comerciales.  

**Impacto en la estrategia empresarial:**  
- Enfoque de recursos en regiones y productos de alto desempeño.  
- Optimización de planificación de inventario y campañas de promoción.  
- Proyección confiable de demanda mediante modelos de regresión y series de tiempo.  

**Recomendaciones:**  
- Reforzar acciones comerciales en regiones de alto potencial.  
- Utilizar clusters de productos para campañas segmentadas.  
- Optimizar logística según patrones de demanda proyectados.  

**Futuras mejoras:**  
- Integrar variables externas como competencia, tendencias de mercado o indicadores socioeconómicos.  
- Mapear datos regionales con zonas geográficas para estrategias logísticas y de marketing.  
- Implementar dashboards interactivos en tiempo real.  
- Evaluar modelos avanzados de machine learning para mejorar precisión en predicciones y segmentación.  
