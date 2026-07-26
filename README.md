# Analisis-ConnectaTel
Análisis de empresa de telecomunicaciones ConnectaTel

Este repositorio contiene el análisis realizado a el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos.
- Explorar, limpiar y analizar los datos para construir un perfil estadístico de los clientes.
- Detectar comportamientos atípicos y crear segmentos de clientes.
- Identificar patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes ofrecidos por la empresa.

 El proyecto incluye 3 datasets:

- plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

## 📂 Contenido del repositorio

- `Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](S7_Version_Estudiante_Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## Etapas de análisis realizadas

- Exploración de la estructura de los datasets.
- Revisión de valores nulos.
- Detección de valores inválidos y sentinels.
- Revisión y estandarización de fechas.
- Limpieza básica de datos.
- Summary statistics de uso por usuario.
- Visualización de distribuciones (uso y clientes) y outliers.
- Segmentación de Clientes.
- Insight Ejecutivo para Stakeholders.

