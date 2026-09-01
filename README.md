# ✈️ Análisis de Accidentes Aéreos — Dashboard en Power BI

## 📊 Descripción del proyecto

Este proyecto consiste en el desarrollo de un dashboard interactivo en **Microsoft Power BI** para analizar accidentes aéreos ocurridos en distintos lugares y períodos.

El objetivo principal es transformar los datos de accidentes en información visual que permita identificar **patrones, tendencias y características asociadas a estos eventos**, facilitando su exploración y análisis.

El dashboard busca responder preguntas como:

- ¿Qué aerolíneas presentan mayor cantidad de accidentes?
- ¿Qué modelos de aviones y motores aparecen con mayor frecuencia?
- ¿Cómo evolucionó la cantidad de accidentes a lo largo de los años?
- ¿En qué meses y días de la semana se concentran más accidentes?
- ¿En qué regiones geográficas se producen más accidentes?
- ¿Qué aerolíneas presentan mayores tasas de supervivencia?
- ¿Qué características técnicas aparecen asociadas con mayor frecuencia a los accidentes?

---

## 🎯 Objetivos

- Explorar y analizar información histórica sobre accidentes aéreos.
- Identificar patrones temporales y geográficos.
- Analizar la frecuencia de accidentes por aerolínea.
- Analizar modelos de aeronaves y motores asociados a los accidentes.
- Evaluar indicadores relacionados con fallecimientos y supervivencia.
- Construir visualizaciones interactivas para facilitar la interpretación de los datos.
- Presentar la información de manera clara para usuarios técnicos y no técnicos.

---

## 🛠️ Herramientas utilizadas

- **Microsoft Power BI**
- **Power Query** para transformación y preparación de datos
- **DAX** para la creación de medidas y cálculos
- **Modelo relacional de datos**
- Visualizaciones interactivas y filtros de Power BI
- Mapas para análisis geográfico

---

## 🗂️ Modelo de datos

El proyecto utiliza un modelo relacional compuesto por diferentes tablas relacionadas con los accidentes, aerolíneas, vuelos, aeronaves, motores y pasajeros.

Entre las principales entidades utilizadas se encuentran:

- `Tabla_Accidente`
- `Tabla_Aerolinea`
- `Tabla_Avion`
- `Tabla_Modelo_Motor`
- `Tabla_Vuelo`
- `Tabla_Pasajeros`
- `Calendario`

El modelo permite analizar la información desde diferentes dimensiones y aplicar filtros cruzados sobre las visualizaciones.

---

# 📈 Dashboard

## 1. Visión Global de los Accidentes Aéreos

Esta sección presenta una visión general del conjunto de datos mediante indicadores y visualizaciones relacionadas con:

- Cantidad total de accidentes
- Total de fallecidos
- Tasa de supervivencia
- Evolución de accidentes por año
- Distribución de accidentes por continente
- Distribución geográfica de los accidentes

También incorpora filtros por año para facilitar el análisis de períodos específicos.

[Visión Global de los Accidentes Aéreos](screenshots/vision-global.png)

---

## 2. Compañías y Supervivencia

Esta sección analiza el comportamiento de las aerolíneas frente a los accidentes registrados.

Se incluyen indicadores y visualizaciones para analizar:

- Aerolínea con mayor cantidad de accidentes
- Cantidad de accidentes
- Cantidad de fallecidos
- Porcentaje de supervivencia por aerolínea
- Distribución geográfica de supervivientes

La visualización permite comparar diferentes aerolíneas y explorar la relación entre accidentes y supervivencia.

[Compañías y Supervivencia](screenshots/companias-supervivencia.png)

---

## 3. Análisis Temporal y Estacional

Esta sección estudia la distribución temporal de los accidentes.

Se analizan:

- Mes con mayor cantidad de accidentes
- Día de la semana con mayor cantidad de accidentes
- Cantidad de accidentes por mes
- Distribución por estación del año
- Evolución según año
- Ubicación geográfica

Los filtros permiten analizar diferentes años y ubicaciones para explorar posibles patrones temporales.

[Análisis Temporal y Estacional](screenshots/analisis-temporal.png)

---

## 4. Modelos Técnicos Asociados a Accidentes

Esta sección analiza las características técnicas de las aeronaves involucradas en los accidentes.

Se incluyen análisis relacionados con:

- Modelo de avión más frecuente
- Modelo de motor más frecuente
- Cantidad de accidentes por modelo de aeronave
- Cantidad de accidentes por modelo de motor
- Autonomía
- Capacidad total
- Año y ubicación

Esto permite explorar qué modelos aparecen con mayor frecuencia dentro del conjunto analizado.

[Modelos Técnicos Asociados a Accidentes](screenshots/modelos-tecnicos.png)

---

# 🔎 Principales análisis

El dashboard permite realizar análisis desde diferentes perspectivas:

### Temporal

Permite estudiar la evolución de los accidentes a través de los años y analizar su distribución mensual, semanal y estacional.

### Geográfica

Los mapas permiten visualizar la distribución espacial de los accidentes y de los supervivientes.

### Aerolíneas

Permite comparar la cantidad de accidentes y los indicadores de supervivencia entre compañías.

### Técnica

Permite analizar los modelos de aeronaves y motores más frecuentes dentro de los accidentes registrados.

---

# 💡 Competencias demostradas

Este proyecto demuestra experiencia práctica en:

- Preparación y transformación de datos
- Modelado de datos
- Construcción de relaciones entre tablas
- Creación de medidas con DAX
- Desarrollo de dashboards interactivos
- Análisis exploratorio de datos
- Análisis temporal
- Análisis geográfico
- Diseño de visualizaciones
- Interpretación y comunicación de información
- Construcción de indicadores para análisis de negocio

---

# 📁 Contenido del repositorio

```text
├── Maria-Canero_Accidentes_Aereos.pbix
├── README.md
└── screenshots/
    ├── vision-global.png
    ├── companias-supervivencia.png
    ├── analisis-temporal.png
    └── modelos-tecnicos.png
