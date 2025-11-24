# ⚽ Análisis Predictivo de Resultados de Fútbol (La Liga)

---

**🛠️ Estado del Proyecto:** 
El análisis, la documentación y el informe (Trabajo Final de Máster) están completos. El código fuente está siendo **revisado, modularizado y documentado** para asegurar la máxima reproducibilidad y calidad de ingeniería. ¡Pronto disponible!

---

## 🌟 Resumen del Proyecto

Este trabajo presenta un estudio comparativo de modelos de Inteligencia Artificial (Machine Learning y Deep Learning) para la **predicción de resultados de partidos de fútbol** en la liga española (La Liga).

El objetivo principal es predecir una de tres categorías: **Victoria Local**, **Victoria Visitante** o **Empate**. El valor del proyecto radica en la robusta fase de **Feature Engineering** y en la **evaluación rigurosa** de los modelos, comparando su rendimiento directamente con los pronósticos del mercado (casas de apuestas).

## 💡 Metodología y Enfoque

El rigor metodológico fue clave para el éxito predictivo:

1.  **Análisis Exploratorio de Datos (EDA) Extenso:** Se realizó un análisis profundo para identificar los factores históricos y estadísticos que tienen mayor influencia en el resultado final de un partido de fútbol (variables como la diferencia de goles, la localía histórica, etc.).
2.  **Feature Engineering Avanzado:** Se creó un conjunto de **nuevas variables** clave diseñadas para capturar la *forma* y el *nivel actual* con el que cada equipo llegaba al encuentro. Estas incluyeron:
    * Rendimiento reciente (últimos 3-5 partidos).
    * Balance histórico de victorias/derrotas.
    * Puntos totales acumulados hasta la fecha del partido.
3.  **Modelos de Aprendizaje Comparados:**
    * **Machine Learning Clásico:** Soporte de Vectores de Máquinas (SVM) y Gradient Boosting.
    * **Deep Learning:** Redes Neuronales.

## 📈 Resultados y Evaluación Clave

El proyecto demostró que la combinación de un EDA exhaustivo y un Feature Engineering específico del dominio permite superar las predicciones basadas únicamente en el conocimiento experto o las probabilidades básicas.

* **Métricas Utilizadas:** El rendimiento se evaluó mediante **Accuracy** (Precisión) y **F1-Score**, además de la **Matriz de Confusión** para un análisis gráfico y detallado del rendimiento de cada clase (V/L, V/V, E).
* **Benchmarking (Punto Fuerte):** Los modelos entrenados se compararon directamente con los **pronósticos de las principales casas de apuestas**.
* **Conclusión de Impacto:** El **mejor modelo** logró un rendimiento notable, con métricas **comparables o superiores** a las de los expertos del mercado. Esto valida el modelo como una herramienta valiosa para el análisis deportivo.

## ⚙️ Tecnologías y Librerías Utilizadas

* **Python:** Lenguaje principal.
* **Scikit-learn:** Implementación de modelos clásicos (SVM, Gradient Boosting).
* **TensorFlow / Keras:** Construcción y entrenamiento de los modelos de Redes Neuronales.
* **Pandas/NumPy:** Limpieza de datos, Feature Engineering y manipulación de datos.
* **Matplotlib / Seaborn:** Visualización de resultados y matriz de confusión.

---

**Luis Pérez-Brotons Ballester**
* **LinkedIn:** www.linkedin.com/in/luis-perez-brotons-ballester
* **Email:** perezbrotonsluiss@gmail.com
