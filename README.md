# Machine-Learning-Regression-Analysis

Desarrollo y evaluación de modelos de aprendizaje automático supervisado aplicados a problemas de regresión para una tasación predictiva. El proyecto se centra en la gestión de datos ruidosos, el preprocesamiento de variables y la comparativa entre modelos lineales robustos y arquitecturas de redes neuronales.

### Contribuciones y Evolución:

El desarrollo aborda el ciclo completo de diseño de un modelo predictivo, desde la curación de datos hasta la selección del modelo óptimo:

- **Preprocesamiento y Limpieza de Datos**: Implementación de técnicas de filtrado y gestión de valores espurios (outliers) para mejorar la calidad de las estimaciones en conjuntos de datos ruidosos.
- **Modelado Lineal Robusto**: Aplicación de algoritmos de regresión lineal y modelos de pérdida de Huber (Huber Loss) para garantizar la estabilidad del modelo frente a anomalías en los datos de entrenamiento.
- **Redes Neuronales para Regresión**: Diseño e implementación de una red neuronal (sin capas ocultas) para validar su comportamiento como regresor multivariable frente a modelos estadísticos tradicionales.
- **Análisis de Métricas de Rendimiento**: Evaluación detallada mediante el coeficiente de determinación ($R^2$) y el error cuadrático medio (MSE), estableciendo comparativas de precisión y coste computacional.

### Donde se analiza:

- **Principio de Parsimonia**: Estudio crítico sobre la eficiencia de los modelos; se demuestra cómo, en escenarios de tasación con ruido, un modelo Huber puede ofrecer resultados superiores a una red neuronal compleja con una fracción del coste computacional.
- **Robustez del Modelo Huber**: Análisis de la capacidad del estimador de Huber para ignorar datos ruidosos que desviarían una regresión lineal ordinaria, resultando en una herramienta más fiable para aplicaciones reales de tasación.
- **Interpretabilidad vs. Complejidad**: Evaluación de por qué el aumento de la complejidad arquitectónica no siempre garantiza una mejora en la generalización si no se introducen nuevas variables o se gestiona correctamente el ruido.

### Uso de tecnologías:

Python, Scikit-learn (Modelos lineales y robustos), Numpy para la manipulación matricial y Matplotlib para la visualización de la superficie de regresión y análisis de residuos.