# Proyecto-1_PROCESAMIENTO_MULTIMEDIA_EIE401
# Procesamiento de Ondas Gravitacionales: Evento GW170814

Este repositorio contiene el desarrollo del Proyecto 1 para la asignatura de **Procesamiento Digital de Multimedia** (EIE 401) en la **Pontificia Universidad Católica de Valparaíso**.

## Descripción del Proyecto
El objetivo principal es la detección y aislamiento de la señal de ondas gravitacionales provenientes del evento GW170814, utilizando datos abiertos de la colaboración **LIGO-Virgo**. El flujo de trabajo aborda la mitigación de ruido instrumental mediante técnicas avanzadas de procesamiento digital de señales (DSP).

## Técnicas Implementadas
*   **Análisis Espectral:** Comparación de densidades espectrales de potencia (PSD).
*   **Windowing:** Implementación de ventana de **Hann** para eliminar el "efecto peine" y fugas espectrales.
*   **Aislamiento de Señal:** Aplicación de blanqueo (*whitening*) y filtrado Butterworth pasabanda (30-400 Hz).
*   **Validación Multimodal:** Resampleo a 8 kHz para generación de audio (.wav) y análisis visual mediante espectrogramas.

## Contenido del Repositorio
*   `Proyecto1_GW170814.ipynb`: Notebook principal con el código en Python.
*   `Reporte_Karen_Ingala.pdf`: Informe técnico final en formato IEEE.
*   `/audio`: Archivos de sonido procesados para validación auditiva.
*   `/figures`: Gráficas de PSD, señales temporales y espectrogramas.

## Requisitos
Para ejecutar este proyecto, necesitas las siguientes librerías de Python:
- `numpy`
- `scipy`
- `matplotlib`

## Institución
*   **Universidad:** Pontificia Universidad Católica de Valparaíso (PUCV).
*   **Carrera:** Ingeniería Civil Electrónica.
*   **Fecha:** Mayo 2026.
