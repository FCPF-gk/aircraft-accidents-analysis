# ✈️ Análisis de Accidentes Aéreos

## 📊 Descripción del proyecto

Proyecto de análisis y visualización de datos desarrollado con **Power BI**, utilizando un modelo relacional y medidas **DAX** para analizar información relacionada con accidentes aéreos.

El objetivo es transformar los datos disponibles en información visual que permita identificar patrones relacionados con **compañías aéreas, aeronaves, motores, pasajeros, ubicación y evolución temporal de los accidentes**.

El proyecto fue desarrollado como parte de mi formación en **Data Analytics**, aplicando conceptos de modelado de datos, análisis exploratorio, visualización y generación de indicadores.

---

## 🎯 Objetivos del análisis

El dashboard fue diseñado para responder diferentes preguntas relacionadas con los accidentes aéreos:

* ¿Qué compañías presentan mayor cantidad de accidentes?
* ¿Qué modelos de aeronaves están involucrados con mayor frecuencia?
* ¿Qué modelos de motor aparecen con mayor frecuencia?
* ¿Cómo se distribuyen los accidentes geográficamente?
* ¿Qué cantidad de pasajeros sobrevivieron?
* ¿Qué compañías presentan mejores porcentajes de supervivencia?
* ¿Qué años presentan mayor cantidad de accidentes?
* ¿Qué meses concentran mayor cantidad de accidentes?
* ¿Existe un patrón estacional en la ocurrencia de accidentes?

---

## 🗂️ Modelo de datos

El proyecto utiliza un **modelo relacional** compuesto por las siguientes tablas:

* **Tabla_Accidente**
* **Tabla_Aerolinea**
* **Tabla_Avion**
* **Tabla_Modelo_Motor**
* **Tabla_Pasajeros**
* **Tabla_Vuelo**
* **Calendario**
* **Medidas**

La separación de la información en diferentes entidades permite relacionar los accidentes con las características de las aeronaves, aerolíneas, vuelos, motores y pasajeros.

La tabla **Calendario** se utiliza para facilitar el análisis temporal y la tabla **Medidas** centraliza las medidas DAX utilizadas en el dashboard.

---

## 📈 Dashboard

El informe está organizado en diferentes secciones de análisis.

### 1. Análisis General de Accidentes

Permite obtener una visión general de los accidentes mediante:

* Cantidad total de accidentes.
* Distribución geográfica.
* Evolución de los accidentes a lo largo del tiempo.
* Distribución por continente.
* Filtros temporales para explorar diferentes períodos.

### 2. Compañías y Supervivencia

Esta sección analiza la relación entre las compañías aéreas y los accidentes, incorporando información relacionada con la supervivencia de los pasajeros.

Incluye:

* Compañía con mayor cantidad de accidentes.
* Accidentes por compañía.
* Distribución geográfica.
* Indicadores relacionados con supervivencia.
* Comparación entre compañías.

### 3. Modelos Técnicos Asociados a Accidentes

Esta sección se enfoca en las características técnicas de las aeronaves involucradas.

Se analizan:

* Modelos de aeronaves.
* Modelos de motores.
* Cantidad de accidentes asociados a cada modelo.
* Filtros por período y ubicación.

### 4. Análisis Temporal y Estacional

Se analiza la evolución temporal de los accidentes y su distribución a lo largo del año.

Incluye:

* Accidentes por año.
* Accidentes por mes.
* Mes con mayor cantidad de accidentes.
* Distribución por estación.
* Filtros temporales.

---

## 🧮 Medidas DAX

Se desarrollaron medidas para obtener indicadores y resultados utilizados en las visualizaciones del informe.

Entre ellas se encuentran medidas relacionadas con:

* Cantidad de accidentes.
* Aerolínea con mayor cantidad de accidentes.
* Modelo de avión más frecuente.
* Mes con mayor cantidad de accidentes.
* Indicadores de supervivencia.

El uso de medidas permite que los resultados respondan dinámicamente a los filtros aplicados en el dashboard.

---

## 🛠️ Tecnologías utilizadas

* **Power BI** — modelado de datos, visualización y desarrollo del dashboard.
* **DAX (Data Analysis Expressions)** — creación de medidas e indicadores.
* **SQL** — consulta y análisis de datos relacionales.
* **Modelo relacional** — organización y relación de las diferentes entidades.

---

## 🔎 Habilidades aplicadas

Este proyecto permitió aplicar conocimientos de:

* Modelado de datos.
* Análisis exploratorio de datos.
* Consultas y manipulación de datos.
* Creación de medidas DAX.
* Análisis temporal.
* Análisis de indicadores.
* Diseño de dashboards interactivos.
* Visualización de información.
* Traducción de preguntas de análisis en indicadores y visualizaciones.

---

## 📁 Estructura del proyecto

```text
aircraft-accidents-analysis/
│
├── README.md
│
├── powerbi/
│   └── Maria-Canero_Accidentes_Aereos.pbix
│
├── sql/
│   └── consultas.sql
│
├── images/
│   ├── dashboard-general.png
│   ├── companias-supervivencia.png
│   ├── modelos-tecnicos.png
│   └── analisis-temporal.png
│
└── data/
    └── README.md
```

> Los archivos de datos originales no se incluyen en el repositorio cuando su distribución está restringida o no es necesaria para reproducir el análisis.

---

## 💡 Principales aprendizajes

El desarrollo de este proyecto permitió integrar diferentes etapas de un flujo de análisis de datos:

**Datos → Modelo relacional → Medidas DAX → Visualización → Análisis**

El proyecto pone especial énfasis en transformar datos estructurados en indicadores y visualizaciones que permitan identificar patrones y responder preguntas concretas.

---

## 👩‍💻 Autora

**María Florencia Canero**

Licenciada en Ciencias Oceanográficas — Universidad de Buenos Aires.

Perfil orientado al análisis de datos, programación y procesamiento de series temporales, con experiencia en análisis de datos científicos y formación en **Data Analytics y Data Science**.

🔗 [GitHub](https://github.com/FCPF-gk)
