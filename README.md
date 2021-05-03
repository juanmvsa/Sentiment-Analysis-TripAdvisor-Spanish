# Análisis de Sentimientos - TripAdvisor
Este repositorio contiene lo siguiente:
- Código que regresa un archivo .txt que contiene un ID (asociado a una reseña de TripAdvisor) y una clase asociada a ese ID. 
- Datos para el entrenamiento del modelo.
- Datos para la evaluación del modelo.
- Datos de entrenamiento modificados. Cada fila contiene una oración de 128 caracteres. Dentro de DataFrame hay dos columnas: "Opinion" y "Labels", siendo la primera la reseña, y la segunda la clase asociada a dicha reseña.

## Notas:
- El programa genera cinco clases (0, 1, 2, 3, 4, 5), que indican sentimientos positivos ascendentemente.
- El código fue escrito con base en BETO -- un modelo de BERT entrenado con un corpus en español.

