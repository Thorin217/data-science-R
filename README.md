# Análisis de Datos de Bitcoin

Este proyecto analiza un conjunto de datos históricos de Bitcoin para explorar tendencias, distribuciones y relaciones entre variables clave, utilizando herramientas de Python. Se divide en cuatro pasos principales: carga, limpieza, análisis exploratorio (EDA), y visualización de resultados.

## **Conjunto de Datos**
- **Nombre del archivo**: `Bitcoin_Historical_Data.csv`
- **Descripción**: Contiene datos históricos del mercado de Bitcoin, incluyendo:
  - Fecha (`Date`)
  - Precio ajustado al cierre (`Adj Close`)
  - Precio de cierre (`Close`)
  - Precio más alto del día (`High`)
  - Precio más bajo del día (`Low`)
  - Precio de apertura (`Open`)
  - Volumen de transacciones (`Volume`)

## **Estructura del Proyecto**
### **1. Carga del Archivo**
El archivo se carga y se exploran las primeras filas para verificar su estructura. Esto incluye:
- Identificación de columnas relevantes.
- Inspección inicial (`head()`, `info()`).

### **2. Limpieza y Transformación**
Se realiza una limpieza básica para garantizar que los datos sean utilizables:
- Conversión de la columna `Date` a formato `datetime`.
- Eliminación de valores nulos y duplicados (si existen).
- Verificación de tipos de datos.

### **3. Análisis Exploratorio de Datos (EDA)**
Se investigan las características clave del conjunto de datos:
- Resumen estadístico (`describe()`).
- Cálculo de correlaciones entre variables numéricas (`Adj Close`, `Volume`, etc.).
- Identificación de patrones y posibles problemas (valores extremos, faltantes).

### **4. Visualización de Resultados**
Gráficos detallados para comunicar hallazgos:
- **Histograma**: Distribución del precio ajustado al cierre (`Adj Close`).
- **Gráfico de líneas**: Tendencia del precio ajustado (`Adj Close`) a lo largo del tiempo.
- **Gráfico de barras**: Comparación del volumen de transacciones.
- **Gráfico de líneas**: Comparación de precios máximos (`High`) y mínimos (`Low`).

## **Instrucciones de Uso**
1. **Clona este repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio
