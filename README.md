# ONE-Challenge-4
Challenge Telecom X: análisis de evasión de clientes - Parte 2
-----

# 📊 **Proyecto: Análisis y Predicción de Evasión de Clientes (Churn) en Telecom X**

## 🎯 **Propósito del Proyecto**

Este proyecto tiene un doble objetivo:

1.  **Análisis Exploratorio de Datos (EDA):** Identificar los factores y patrones que contribuyen a la evasión de clientes.
2.  **Modelado Predictivo:** Desarrollar modelos de aprendizaje automático capaces de predecir la probabilidad de que un cliente cancele su servicio.

La meta final es proporcionar a **Telecom X** `insights` accionables para la **prevención de la pérdida de clientes** y la mejora de las estrategias de retención.

-----

## 📂 **Estructura del Proyecto**

El proyecto está organizado en un solo `notebook` de Jupyter, que guía a través de todo el proceso de `data science`.

  * `Challenge Telecom X 2`: El `notebook` principal que contiene todo el código para la carga, limpieza, análisis, modelado y evaluación.
  * `README.md`: Este archivo, que proporciona una visión general del proyecto, los hallazgos clave y las instrucciones de uso.

-----

## 📈 **Hallazgos Clave y Visualizaciones**

El análisis reveló `insights` importantes sobre el comportamiento de los clientes y los factores de riesgo de `churn`.

### **1. La Evasión es un Problema Significativo**

El 25.8% de los clientes en la base de datos han cancelado su servicio, lo que subraya la necesidad de una estrategia de retención.

### **2. La Permanencia y el Gasto Son Claves**

Los clientes que evaden tienen una **permanencia mucho más corta** y un **gasto total acumulado significativamente menor**.

### **3. El Tipo de Contrato es el Principal Factor de Riesgo**

Los clientes con contratos **mes-a-mes** son el segmento de mayor riesgo, con una tasa de evasión notablemente alta en comparación con los contratos a largo plazo.

### **4. Principales Variables Predictivas**

El análisis de la importancia de las variables confirmó que las características más relevantes para predecir la evasión son el **gasto total**, la **permanencia del cliente**, y el **tipo de contrato**.
