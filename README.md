# Recursos de Código para Libros

Este repositorio almacena los códigos, notebooks y datos que acompañan los libros de matemáticas, estadística, optimización y aprendizaje máquina.

## Estructura

- `intro-machine-learning-trees/`: notebooks y ejemplos sobre árboles de decisión.
- `datos/`: conjuntos de datos usados por los notebooks.

## Criterios de reproducibilidad

- Los notebooks deben poder ejecutarse sin depender de descargas en tiempo de ejecución cuando el dataset sea pequeño y estable.
- Los datos compartidos por varios capítulos viven en `datos/`.
- Cada notebook debe fijar semillas aleatorias cuando el resultado dependa de aleatoriedad.
- Las salidas pesadas o generadas se deben evitar en el control de versiones, salvo que sean necesarias para el libro.

## Entorno inicial

```bash
pip install -r requirements.txt
```

