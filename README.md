# 📊 Análisis de Datos y Web Scraping con Python: PEC 3

## 📚 Contenidos

1. [Introducción](#introducción)
2. [apartado 4: Anonimización de Datos](#apartado-4-anonimización-de-datos)
   - Presentación y generación del dataset
   - Importación del dataset
   - Proceso de anonimización
3. [apartado 5: Web Scraping y Representación Gráfica](#apartado-5-web-scraping-y-representación-gráfica)
   - Extracción de citas de Marilyn Monroe
   - Análisis de autores más citados
   - Distribución de citas por etiquetas
   - Análisis de sentimientos de citas
4. [apartado 6: Acceso a Datos Abiertos del INE](#apartado-6-acceso-a-datos-abiertos-del-ine)
   - Descarga de datos de viviendas turísticas
   - Representación de datos estadísticos
   - Análisis de datos adicionales

---

## 📝 Introducción

Este repositorio contiene la resolución de la PEC 3, donde se abordan diversos temas de análisis de datos y web scraping usando Python. Se trabajan técnicas como:

- **Anonimización de datos sensibles**
- **Extracción de información web con `BeautifulSoup` y `requests`**
- **Visualización de datos con `matplotlib`**
- **Análisis de datos abiertos mediante la API del INE**

---

## 🛡️ apartado 4: Anonimización de Datos

### 📄 Descripción

Se trabaja con un conjunto de datos de pacientes con diabetes tipo II, utilizando técnicas de anonimización para garantizar la privacidad de los datos.

### 🔧 Tecnologías utilizadas

- `pandas` para la manipulación de datos.
- Técnicas de supresión y generalización para cumplir con el criterio K-anonimidad.

### 📂 Archivos requeridos

- `dataset_diabetes.csv` (datos originales)
- `dataset_anonimizado.csv` (resultado del proceso)

---

## 🌐 apartado 5: Web Scraping y Representación Gráfica

### 📄 Descripción

En este apartado se extraen citas de la web `quotes.toscrape.com` y se representan gráficamente.

### 📊 Contenidos

1. **Extracción de citas de Marilyn Monroe:**  
   - Uso de `requests` y `BeautifulSoup` para navegar y extraer citas.

2. **Análisis de autores más citados:**  
   - Visualización de la cantidad de citas por autor en un gráfico de barras.

3. **Distribución de etiquetas populares:**  
   - Representación gráfica de etiquetas como `love`, `inspirational`, etc.

4. **Análisis de sentimiento:**  
   - Aplicación de `TextBlob` para clasificar las citas en positivas, negativas o neutras.

### 🔧 Tecnologías utilizadas

- `requests` y `BeautifulSoup` para el scraping.
- `matplotlib` y `pandas` para análisis y visualización de datos.
- `TextBlob` para análisis de sentimiento.

---

## 🏡 apartado 6: Acceso a Datos Abiertos del INE

### 📄 Descripción

Se accede a la API del Instituto Nacional de Estadística (INE) para analizar datos sobre viviendas turísticas en España.

### 📊 Contenidos

1. **Descarga de datos:**  
   - Extracción de información a nivel nacional, autonómico y provincial.

2. **Representación de datos:**  
   - Análisis de la evolución de viviendas turísticas en la comunidad autónoma y provincia.

3. **Exploración de datos adicionales:**  
   - Representación de otros datos estadísticos de interés.

### 🔧 Tecnologías utilizadas

- `requests` para acceder a la API del INE.
- `pandas` para procesamiento de datos.
- `matplotlib` para la visualización.

---

## ⚙️ Instalación y Requisitos

Para ejecutar los scripts de este repositorio, se deben instalar las siguientes dependencias:

```bash
pip install pandas requests beautifulsoup4 matplotlib textblob
