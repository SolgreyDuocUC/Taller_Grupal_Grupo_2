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
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install openpyxl
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
    
| Variables Relevantes| Clasificación |
|----------|-------------|
| **GENERO** | Cualitativa nominal |
| **EDAD** | Cuantitativa continua |
| **RANGO EDAD** | Cualitativa ordinal |
| **AÑO INGRESO** | Cuantitativa discreta |
| **SEMESTRE INGRESO** | Cualitativa ordinal |
| **NOMBRE CARRERA** | Cualitativa nominal |
| **MODALIDAD** | Cualitativa nominal |
| **JORNADA** | Cualitativa nominal |
| **NIVEL DE ESTUDIO CARRERA** | Cualitativa ordinal |
| **NIVEL CARRERA** | Cualitativa ordinal |
| **AREA CONOCIMIENTO** | Cualitativa nominal |
| **DURACION PLAN DE ESTUDIO (SEM)** | Cuantitativa discreta |
| **DURACION TOTAL CARRERA (SEM)** | Cuantitativa discreta |
| **VALOR MATRICULA (PESOS)** | Cuantitativa continua |
---

## Parte II – Análisis univariado

### 4. Tablas de frecuencia
- Tablas de frecuencia absoluta, relativa y acumulada (para variables cualitativas).
- Gráficos asociados (barras, circulares).

### 5. Medidas de posición
- Media, mediana y moda (para variables cuantitativas).
- Percentiles y cuartiles (Q1, Q2, Q3, P90, etc.).
- Breve comentario interpretando qué significan estos valores en el contexto.

**Se seleccionaron las siguientes variables numéricas:**
- Edad
- Duración total de la carrera (semestres)
- Valor matrícula (pesos)
- Valor arancel (pesos)

**Medidas utilizadas**
- **Media:** Promedio de los valores
- **Mediana:** Valor central de la distribución
- **Moda:** Valor más frecuente
- **Cuartiles:** Segmentos del 25% (Q1, Q2, Q3)
- **Percentiles:** Posición relativa (por ejemplo, P90)

**Tabla con los valores**

| Variable | Media | Mediana | Moda | Q1 | Q3 | P90 |
|----------|-------|---------|------|----|----|-----|
| **Edad (años)** | 24 | 23 | 22 | 20 | 28 | 32 |
| **Duración total carrera (SEM)** | 9 | 10 | 10 | 8 | 12 | 12 |
| **Valor matrícula (pesos)** | 365.000 | 290.000 | 469.000 | 261.000 | 469.000 | 469.000 |
| **Valor arancel (pesos)** | 2.450.000 | 2.670.000 | 2.670.000 | 1.748.000 | 2.920.000 | 3.527.000 |

**Comentario interpretativo**
- La edad promedio de los estudiantes es de 24 años, con una mediana de 23, lo que indica una ligera concentración en edades jóvenes.
- La duración más común de la carreras es de 10 semestres, lo que coincide con la mediana y la moda.
- El valor de matrícula más frecuente es de $469.000, aunque la mediana es más baja, lo que sugiere que algunas carreras más económicas bajan el promedio.
- El valor del arancel muestra una amplia dispersión, con un P90 de más de $3.500.000, lo que indica que el 10% de las carreras más costosas superan ese monto.

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
