# 🧠 Perceptrón Monocapa en Java (2x1)

Este repositorio contiene la implementación en Java de un **Perceptrón Monocapa** de dos entradas y una salida ($2 \times 1$). El proyecto está diseñado para simular el comportamiento de una neurona artificial entrenable mediante aprendizaje supervisado utilizando la regla de Rosenblatt, permitiendo resolver problemas de clasificación linealmente separables como las puertas lógicas `AND`, `OR` y `NAND`.

---

## 🚀 Características

* **Modelo $2 \times 1$:** Configuración con 2 entradas binarias/continuas y 1 salida.
* **Algoritmo del Perceptrón:** Ajuste iterativo de pesos sinápticos ($w_1, w_2$) y sesgo/bias ($b$) mediante la regla de corrección de error.
* **Entrenamiento Configurable:** Control de la tasa de aprendizaje ($\eta$) y del número máximo de épocas.
* **Modularidad:** Estructura limpia orientada a objetos (POO) en Java con separación de responsabilidades.
* **Interfaz / Ejecución:** Punto de entrada centralizado para probar y evaluar el entrenamiento.

---

## 🛠️ Estructura del Proyecto

El código fuente se encuentra en la carpeta `src/` y está organizado en las siguientes clases principales:

```text
src/
 ├── Neurona.java       # Representación de la unidad lógica (entradas, pesos, bias y función escalón)
 ├── Perceptron2x1.java # Lógica de entrenamiento, cálculo del error y actualización de pesos
 ├── Parametros.java    # Configuración de hiperparámetros (tasa de aprendizaje, épocas)
 └── MainPage.java      # Clase principal / Punto de entrada de la aplicación
