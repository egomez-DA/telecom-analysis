# Análisis ConnectaTel – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.

Se trabajó con tres datasets:

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)


## 📂 Contenido del repositorio

- `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18TKbMkINStdR5i1yh5VqDUnVdcxBJ5Yy?usp=sharing)
O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Crear segmentos de clientes,  identificar patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes.
- Generar insights para el equipo de ConnectaTel.
