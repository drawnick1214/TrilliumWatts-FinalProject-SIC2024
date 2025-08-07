# TrilliumWatts – Proyecto Final SIC 2024

**R3newAI: Modelado de Deep Learning para la Predicción de la Demanda de Energía Eléctrica y Evaluación de Soluciones Solares Fotovoltaicas en Leticia, Amazonas**

---

## Descripción general

Este proyecto propone un enfoque de inteligencia artificial para predecir la demanda energética diaria en la Zona No Interconectada (ZNI) de Leticia, Amazonas, Colombia. Utilizando redes neuronales recurrentes (GRU y LSTM), se construyó un modelo capaz de anticipar el comportamiento de consumo eléctrico a partir de datos históricos y variables climáticas satelitales. 

Además, se diseñó un módulo de simulación solar que permite estimar el impacto económico y ambiental de diferentes escenarios de generación fotovoltaica, con visualización interactiva.

---

## Modelos aplicados

- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

> El modelo GRU obtuvo el mejor desempeño con un R² = 0.63 y menor MAE, mostrando mejor estabilidad durante el entrenamiento.

---

## Estructura del repositorio
	TrilliumWatts-FinalProject-SIC2024
	  -NoteBook ejecución proyecto R3newAI.ipynb
	  -README.md
---

## Instrucciones de uso

Puedes abrir y ejecutar el notebook en Google Colab haciendo clic en el siguiente botón:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LauraRico03/TrilliumWatts-FinalProject-SIC2024/blob/main/NoteBook%20ejecución%20proyecto%20R3newAI.ipynb)

---

## Resultados y simulación

- Predicción multivariable de la demanda eléctrica en ventanas de 7, 15 y 30 días.
- Simulación solar en tres escalas (100kW, 1MW, 5MW).
- Estimación de ahorro en litros de diésel, emisiones de CO₂ evitadas y ahorro económico.
- Interfaz interactiva para explorar distintos escenarios mediante widgets en Colab.

---

## Autores

**Trillium Watts – Capstone Final Samsung Innovation Campus 2024**

-Edward Nicolás Díaz Cristancho – Líder de validación técnica y escenarios energéticos.

-Juliana Utrera Flórez – Líder de arquitectura del modelo y estrategia de datos.

-Laura Rico Aldana – Líder de simulación de impacto ambiental y económico.
