![Texto alternativo](cover.jpg)

**Título del Proyecto:**
Preparación de Datos para Modelado Predictivo en BMW

**Breve Descripción:**
En este proyecto el preprocessamiento de los datos fue fundamental ya que teníamos más de 100 columnas.

**Proceso de Preprocesamiento:**
1. **Eliminación de Columnas Redundantes:** Descartamos columnas que no aportaban significativamente al análisis, liberando espacio para datos más relevantes.
2. **Manejo de Valores Nulos:** Tomamos decisiones estratégicas sobre cómo manejar los valores nulos, priorizando la integridad de la variable objetivo (precio).
3. **Corrección de Formatos Erróneos:** Corregimos formatos erróneos de cadenas y los convertimos en formatos numéricos apropiados para un análisis preciso.
4. **Codificación de Variables Categóricas:** Utilizamos técnicas como One-Hot Encoding y Ordinal Encoding para manejar las variables categóricas de manera efectiva.
5. **Normalización de Valores:** Normalizamos los valores utilizando MinMaxScaler para garantizar que todas las variables estuvieran en la misma escala.
6. **Eliminación de Columnas Altamente Correlacionadas:** Eliminamos las columnas altamente correlacionadas entre sí, conservando aquellas con la mayor correlación con la variable objetivo.
7. **Reducción de Variables:** Eliminamos las columnas con una varianza inferior al 0.01 para reducir el número de variables y mejorar la eficiencia del análisis.

**Modelado Predictivo:**
Después del preprocesamiento, decidimos hacer un torneo de modelos para encontrar la mejor opción. Implementamos varios modelos de Machine Learning, incluyendo regresión lineal, árboles de decisión y Random Forest, para predecir los precios de los vehículos de BMW.

**Evaluación del Modelo:**
Evaluar la eficacia de nuestros modelos fue crucial. Utilizamos métricas como el error cuadrático medio (MSE) y el coeficiente de determinación (R²) para comparar y seleccionar el modelo más adecuado para nuestras necesidades.

**Validación Cruzada y Ajuste de Hiperparámetros:**
Implementamos la validación cruzada para garantizar la robustez de nuestros modelos y ajustamos los hiperparámetros para mejorar su rendimiento y generalización.

**Resultados y Conclusiones:**
Este proyecto ha sido un gran desafio y nos ha hecho ver la importancia de una buena limpieza de los datos para obtener el mejor modelo.
