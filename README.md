# Taller_Grupal_Grupo_2
Taller Grupal de Investigación Estadistica 2025 correspondiente al ramo de ESTADISTICA DESCRIPTIVA_002D

# 📊 Análisis Descriptivo de Datos – Estadística Descriptiva

Este repositorio contiene el desarrollo del **Trabajo de Estadística Descriptiva**, realizado en Google Colab / Jupyter Notebook.  
El objetivo es aplicar los conceptos aprendidos en la asignatura para explorar y analizar un conjunto de datos del mundo real, utilizando **tablas de frecuencia, medidas de tendencia central, percentiles, cuartiles, medidas de dispersión y representaciones gráficas**.

---

## 📂 Archivos incluidos
- `analisis_estadistico.ipynb` → Notebook con el desarrollo del trabajo.
- `README.md` → Documento explicativo con instrucciones de uso.
- Dataset proporcionado por el docente.

---

## ⚙️ Requerimientos

Para ejecutar el proyecto en local es necesario tener instalado **Python 3.8+** y las siguientes librerías:

- [pandas](https://pandas.pydata.org/) → para manipulación de datos.  
- [numpy](https://numpy.org/) → para cálculos numéricos y estadísticos.  
- [matplotlib](https://matplotlib.org/) → para visualización de gráficos básicos.  
- [seaborn](https://seaborn.pydata.org/) → para gráficos estadísticos más estilizados.  

---

## 💻 Instalación de dependencias

Ejecutar los siguientes comandos en la terminal:

```bash
# Crear entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate   # En Linux / Mac
venv\Scripts\activate      # En Windows

# Instalar librerías necesarias
pip install
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
```

---

## Parte I – Introducción y descripción general de los datos

### 1. Caso de estudio
- Breve descripción de la base de datos.
- Origen de los datos y contexto del tema que representan.

### 2. Población y muestra
- Definición de la población de interés.
- Descripción de la muestra utilizada (número de registros, representatividad, limitaciones).

### 3. Clasificación de variables
- Identificación de las variables más relevantes.
- Clasificación en:
  - **Cualitativas**: nominales / ordinales.
  - **Cuantitativas**: discretas / continuas.

---

## Parte II – Análisis univariado

### 4. Tablas de frecuencia
- Tablas de frecuencia absoluta, relativa y acumulada (para variables cualitativas).
- Gráficos asociados (barras, circulares).

### 5. Medidas de posición
- Media, mediana y moda (para variables cuantitativas).
- Percentiles y cuartiles (Q1, Q2, Q3, P90, etc.).
- Breve comentario interpretando qué significan estos valores en el contexto.

### 6. Representaciones gráficas
- Histogramas (para visualizar distribución de variables numéricas).
- Diagramas de caja (boxplots) para mostrar cuartiles y detectar valores atípicos.

---

## Parte III – Análisis de dispersión y conclusiones

### 7. Medidas de dispersión
- Cálculo de:
  - Rango.
  - Varianza.
  - Desviación estándar.
- Interpretación: ¿qué tan dispersos están los datos?

### 8. Síntesis gráfica comparativa
- Seleccionar 2–3 gráficos clave que resuman hallazgos.
- Ejemplo: comparación de una variable numérica segmentada por categorías.

### 9. Conclusiones descriptivas
- Resumen de hallazgos principales:
  - Variables con mayor concentración.
  - Variables con más variabilidad.
  - Patrones o sesgos encontrados.
- Observaciones finales y relevancia de los resultados.
