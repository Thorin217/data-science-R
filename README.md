# **Análisis de Datos de Bitcoin**

Este proyecto tiene como objetivo analizar datos históricos del mercado de Bitcoin para identificar tendencias, distribuciones y relaciones entre variables clave, utilizando herramientas de Python. El análisis se divide en cuatro etapas principales: carga de datos, limpieza, análisis exploratorio (EDA) y visualización.

## **Descripción del Conjunto de Datos**
- **Nombre del archivo**: `Bitcoin_Historical_Data.csv`  
- **Contenido**: Registra información histórica sobre el comportamiento del mercado de Bitcoin, incluyendo:
  - Fecha (`Date`)
  - Precio ajustado de cierre (`Adj Close`)
  - Precio de cierre (`Close`)
  - Precio máximo del día (`High`)
  - Precio mínimo del día (`Low`)
  - Precio de apertura (`Open`)
  - Volumen de transacciones (`Volume`)

## **Estructura del Proyecto**
### **1. Carga de Datos**
Se importa el archivo CSV y se exploran sus primeras filas para entender la estructura del dataset. Este paso incluye:
- Identificación de las columnas importantes.
- Exploración inicial con funciones como `head()` e `info()`.

### **2. Limpieza y Preparación**
Se realiza una limpieza básica para asegurar que los datos sean válidos y analizables:
- Conversión de la columna `Date` al formato `datetime`.
- Eliminación de valores nulos o duplicados.
- Revisión y corrección de tipos de datos.

### **3. Análisis Exploratorio (EDA)**
Se extraen conocimientos clave a través del análisis exploratorio:
- Estadísticas descriptivas usando `describe()`.
- Análisis de correlación entre variables numéricas como `Adj Close` y `Volume`.
- Identificación de tendencias, valores atípicos y datos faltantes.

### **4. Visualización de Resultados**
Se generan distintos gráficos para representar visualmente los hallazgos:
- **Histograma**: Muestra la distribución del precio ajustado de cierre (`Adj Close`).
- **Gráfico de líneas**: Representa la evolución del precio ajustado a lo largo del tiempo.
- **Gráfico de barras**: Compara los volúmenes de transacciones.
- **Gráfico de líneas**: Compara los precios máximos (`High`) y mínimos (`Low`) por día.

## **Cómo Usarlo**
1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/Thorin217/data-science-R.git
   cd tu-repositorio
   ```
