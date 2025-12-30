# 🚗 Análisis de Precios y Rentabilidad de Seguros de Autos
## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar una base de datos de seguros de automóviles para identificar patrones relevantes en los precios, zonas geográficas y características de los vehículos, con el fin de evaluar la rentabilidad actual y proponer ajustes estratégicos en los precios.

El análisis combina consultas SQL desde Python, limpieza de datos, análisis exploratorio y visualización mediante Looker Studio, simulando un escenario real de análisis para toma de decisiones comerciales.

---

## 🎯 Objetivos

Conectarse a una base de datos mediante Python y ejecutar consultas SQL.
Limpiar y transformar los datos para su correcto análisis.

Analizar la relación entre:
- Precio del seguro
- Año del vehículo
- Ubicación geográfica
- Tipo de cobertura

Identificar zonas y segmentos con precios poco rentables.

Presentar insights claros a través de un dashboard interactivo.

---

## 🧰 Herramientas Utilizadas

- Python (pandas, sqlite3 / connector)
- SQL (consultas analíticas)
- Jupyter Notebook
- Looker Studio (visualización de datos)
- GitHub (documentación y control de versiones)

---

## 📂 Fuente de Datos

- Base de datos relacional que contiene información relacionada con:
- Vehículos asegurados
- Precios de seguros
- Ubicación geográfica
- Características del automóvil

---

## 📌 Los datos fueron consultados directamente desde la base de datos utilizando SQL desde Python.

🧹 Limpieza y Transformación de Datos

Las principales tareas realizadas fueron:
- Conexión a la base de datos y creación de cursor SQL
- Normalización de columnas
- Revisión de valores atípicos en precios
- Conversión de tipos de datos
- Preparación de tablas para análisis y visualización

---

## 🔍 Análisis Exploratorio (EDA)

Algunos análisis realizados:
- Distribución de precios de seguros
- Comparación de precios por año del vehículo
- Análisis geográfico (especial énfasis en CDMX)
- Identificación de segmentos con precios poco competitivos
- Evaluación de rentabilidad por tipo de seguro

---

## 📊 KPIs Analizados

- Precio promedio del seguro
- Precio por zona geográfica
- Precio por año del vehículo
- Variación de precios entre regiones
- Segmentos con mayor y menor rentabilidad

---

## 📈 Dashboard en Looker Studio

El dashboard incluye:
- KPIs generales
- Comparación de precios por región
- Análisis por año del vehículo
- Visualizaciones geográficas
- Apoyo visual para toma de decisiones

🔗 Link al dashboard (Looker Studio):
https://lookerstudio.google.com/reporting/6cac230d-d6c9-4433-9f93-c59916dd6e65

---

## 🧠 Insights Destacados

Algunas regiones presentan precios poco competitivos frente a otras zonas.

El año del vehículo no siempre influye proporcionalmente en el precio del seguro.

La CDMX concentra una alta variabilidad de precios.

Existen oportunidades para ajustar tarifas sin afectar la cobertura ofrecida.

---

## 📝 Conclusiones

El análisis sugiere que es necesario reajustar las cantidades cobradas en ciertos segmentos y regiones para mejorar la rentabilidad, ya que algunos precios se mantienen constantes independientemente de variables clave como el año del vehículo o la zona geográfica.

Estos ajustes permitirían una estrategia de precios más justa, competitiva y alineada con el riesgo real.

---

## 📁 Estructura del Proyecto
📦 nombre-proyecto
 ┣ 📂 data
 ┣ 📂 notebooks
 ┣ 📂 sql
 ┣ 📂 dashboards
 ┣ 📂 docs
 ┗ 📄 README.md

 ---

## 👤 Autor

**Bryan Hernandez Solis**
Data Analyst Jr
Python | SQL | Looker Studio | Excel