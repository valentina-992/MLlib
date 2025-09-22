# Desarrollo de sistema de clasificación de productos de skincare para recomendaciones según tipo de piel utilizando MLlib
(Actividad sesión 5 del módulo 9)
</br>
Lenguaje utilizado: Python

El objetivo de este proyecto es clasificar productos de skincare según sus ingredientes claves, nivel de hidratación, nivel de absorción, y factor de protección solar, con la finalidad de generar recomendaciones personalizadas al tipo de piel de cada usuario.

**Técnicas utilizadas:**
- Análisis exploratorio de datos: estadísticas descriptivas.
- Preprocesamiento de datos: Codificación de variables categóricas, creación de nueva columna tipo vector (para uso posterior en el modelo de clasificación con MLlib).
- Modelo de clasificación:
  - División de dato (método Hold-Out).
  - Creación y entrenamiento de modelo DecisionTreeClassifier.
  - Obtención de predicciones.
  - Evaluación del modelo utilizando MulticlassClassificationEvaluator.
  - Comparación con RandomForestClassifier incluyendo optimización de hiperparámetros.
 
**Resultados:** Indicados al final del proyecto.

**Reflexión personal:** Gracias a la realización de este proyecto pude observar la posibilidad de utilizar métodos más eficientes en cuanto a la necesidad de recursos computacionales para implementar modelos de clasificación. Si bien el dataset es pequeño, se refleja claramente la mecánica que permite este ahorro de recursos y que me gustaría probar con datatsets más grandes y desafiantes. También quedo en evidencia la importancia de probar distintos métodos de clásificación y optimizar hiperparámetros cuando no hemos obtenido resultados óptimos (o aunque sean óptimos, si aún son perfectibles).

