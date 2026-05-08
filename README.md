# Predicción de Robos al Paso en el Callao mediante Machine Learning

> Sistema predictivo basado en algoritmos de Machine Learning para identificar zonas y franjas horarias de mayor riesgo de robo al paso en la Provincia Constitucional del Callao, utilizando datos públicos del SIDPOL e INEI.

![Status](https://img.shields.io/badge/status-en%20desarrollo-yellow)
![Python](https://img.shields.io/badge/python-3.10+-blue)
![License](https://img.shields.io/badge/license-MIT-green)

---

## Sobre el proyecto

Proyecto académico desarrollado en el marco del curso **Innovación y Transformación Digital** de la carrera de **Ingeniería de Sistemas e Informática** en la **Universidad Tecnológica del Perú (UTP)**.

El proyecto propone aplicar técnicas supervisadas de Machine Learning (Random Forest y Regresión Logística) sobre datos históricos de criminalidad para apoyar la toma de decisiones policiales preventivas en el Callao, transitando del modelo reactivo tradicional hacia un modelo predictivo basado en evidencia.

## Objetivo

Predecir los robos al paso en la Provincia Constitucional del Callao mediante algoritmos de Machine Learning aplicados sobre datos del SIDPOL y el INEI.

## Stack tecnológico

| Categoría | Herramienta |
|-----------|-------------|
| Lenguaje | Python 3.10+ |
| Análisis de datos | pandas, numpy |
| Machine Learning | scikit-learn |
| Visualización | matplotlib, seaborn, folium |
| Entorno | Google Colab |
| Control de versiones | Git, GitHub |
| Gestión ágil | Trello (Scrumban) |

## Estructura del repositorio

callao-prediccion-robos/
├── data/               # Datasets (no se versionan archivos crudos pesados)
├── notebooks/          # Jupyter notebooks de análisis y modelado
│   ├── 01_EDA.ipynb
│   ├── 02_modelos.ipynb
│   └── 03_mapa_calor.ipynb
├── outputs/            # Modelos entrenados y mapas HTML
├── docs/               # Documentación del proyecto
├── .gitignore
├── LICENSE
└── README.md

## Fuentes de datos

- **SIDPOL** — Sistema de Denuncias Policiales (PNP)
- **DataCrim** — Sistema Integrado de Estadísticas de la Criminalidad (INEI)
- **ENAPRES** — Encuesta Nacional de Programas Presupuestales (INEI)
- **Datos Abiertos del Perú** — datosabiertos.gob.pe

## Metodología

El proyecto se gestiona bajo enfoque **Scrumban** (híbrido Scrum + Kanban) con sprints semanales y tablero visual para flujo continuo de tareas.

## Autores

- **Gerson William Barrientos Díaz** — U22222065
- **Antony Villanueva Casas** — U22233123

## Curso

**Innovación y Transformación Digital** — Universidad Tecnológica del Perú (UTP) · 2026  
Docente: Dante Castillo Ccorahua

## Licencia

Distribuido bajo licencia MIT. Ver `LICENSE` para más información.
