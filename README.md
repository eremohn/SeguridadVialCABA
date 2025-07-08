<p align="center">
  <img src="Informe/Imagenes/Banner_Proyecto.jpg" width="100%" alt="Banner del Proyecto">
</p>

# Análisis de Siniestros Viales en CABA (2016–2021)

---

## 🧭 Índice

- [📌 Introducción del Proyecto](#-introducción-del-proyecto)
- [🎯 Propósito](#-propósito)
- [🔎 Finalidad](#-finalidad)
- [📊 Visualizaciones](#-visualizaciones)
- [📈 Dashboard](#-dashboard)
- [📥 Fuentes de Datos](#-fuentes-de-datos)
- [📁 Estructura del Repositorio](#-estructura-del-repositorio)
- [📚 Informe y Resultados](#-informe-y-resultados)

---

## 📌 Introducción del Proyecto

En entornos urbanos como la Ciudad Autónoma de Buenos Aires, los siniestros viales representan una problemática crítica que afecta tanto a la seguridad pública como al desarrollo urbano sostenible.

Este proyecto surge como una iniciativa de **análisis de datos** con el objetivo de comprender en profundidad las características y dinámicas de los accidentes de tránsito ocurridos entre los años **2016 y 2021**.

A través del tratamiento, visualización e interpretación de datos proporcionados por el **Observatorio de Movilidad y Seguridad Vial (OMSV)**, se busca obtener hallazgos relevantes que sirvan de base para la toma de decisiones en políticas públicas de seguridad vial.

---

## 🎯 Propósito

El propósito de este proyecto es **identificar patrones, tendencias y factores de riesgo** asociados a los siniestros viales en CABA.  
Mediante técnicas de **Análisis Exploratorio de Datos (EDA)** se busca:

- Detectar los segmentos de población más vulnerables.
- Identificar momentos críticos del día o del año.
- Analizar las categorías de vehículos con mayor participación en siniestros.

Todo con el fin de **generar información clara, comprensible y basada en evidencia.**

---

## 🔎 Finalidad

La finalidad de este trabajo es **contribuir a la mejora de la seguridad vial urbana**, facilitando:

- El diseño de estrategias preventivas.
- La implementación de campañas de concientización.
- La planificación de acciones de gestión pública más eficaces.

Los resultados obtenidos apuntan a **reducir la tasa de siniestros y víctimas fatales**, fortaleciendo la movilidad segura en la ciudad.

---

## 📊 Visualizaciones

Las visualizaciones del proyecto fueron desarrolladas en **Power BI** y también exportadas como imágenes y gráficos incluidos en el informe.

- 📁 Ver [carpeta del dashboard](dashboard/)
- 📁 Ver [visualizaciones exportadas](reports/figures/)

---

## 📈 Dashboard

Podés explorar el dashboard interactivo completo en Power BI:

- 🗂️ Archivo: [`siniestros_viales.pbix`](dashboard/siniestros_viales.pbix)  
  > Requiere Power BI Desktop para ser visualizado.

Este dashboard permite filtrar los siniestros por año, tipo de vehículo, horario, comuna y otras dimensiones clave.

---

## 📥 Fuentes de Datos

Los datos fueron obtenidos del Observatorio de Movilidad y Seguridad Vial de CABA.

- 📁 Dataset original: [`data/raw/`](data/raw/)  
- 🔗 [Portal de datos públicos de CABA](https://data.buenosaires.gob.ar/dataset/siniestros-viales)

---

## 📚 Informe y Resultados

Podés consultar el informe completo del proyecto aquí:

- 📄 [`Informe.md`](reports/informe.md)
- 📄 [`Informe.pdf`](reports/informe.pdf)

Contiene explicaciones metodológicas, resultados clave y reflexiones finales.

---

## 📁 Estructura del Repositorio

```bash
SeguridadVialCABA/
│
├── data/               # Datos crudos, procesados y complementarios
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/          # Notebooks de exploración, ETL y análisis
│
├── src/                # Código fuente modular
│
├── reports/            # Visualizaciones y documentos entregables
│   └── figures/
│
├── dashboard/          # Archivo Power BI del proyecto
│
├── README.md           # Documentación principal del proyecto
├── requirements.txt    # Requisitos de entorno
└── .gitignore          # Exclusión de archivos del control de versiones
```
📌 Este repositorio se encuentra en proceso de actualización y mejora continua.
El objetivo es garantizar la máxima claridad, reproducibilidad y valor analítico para su uso en futuros proyectos y presentaciones.
