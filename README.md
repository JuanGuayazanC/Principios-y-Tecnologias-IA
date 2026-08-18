# Principios y Tecnologías IA (PTIA)

Repositorio general del curso Principios y Tecnologías IA, que agrupa —mediante submódulos de git— los laboratorios del curso y el proyecto final.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para saber cómo aprovechar este repositorio, ver [Cómo usar este repositorio](#cómo-usar-este-repositorio).

## Estructura del proyecto

```
Principios-y-Tecnologias-IA/
├── Laboratorios/
│   ├── Redes-neuronales-PTIA/
│   ├── Aprendizaje-PTIA/
│   ├── Minimax-Poda-Alfa-Beta-PTIA/
│   └── Motor-de-Inferencia-Sistema-Basado-en-Reglas-PTIA/
└── Proyectos/
    └── SITMF-PTIA/
```

## Temas del curso

El curso recorre los principios fundamentales de la inteligencia artificial, desde el aprendizaje automático hasta la IA simbólica y la búsqueda adversaria:

- **Aprendizaje automático supervisado**: árboles de decisión, entropía e índice Gini, ganancia de información, sobreajuste y generalización, poda (pre-pruning), y métodos de ensamble (Random Forest, Gradient Boosting).
- **Redes neuronales**: arquitectura de un perceptrón, fundamentos de aprendizaje profundo y entrenamiento de modelos; redes neuronales convolucionales (CNN) aplicadas a visión por computador (capas convolucionales, MaxPooling, softmax).
- **Búsqueda adversaria**: teoría de juegos para dos jugadores, algoritmo Minimax y poda alfa-beta.
- **IA simbólica**: sistemas basados en reglas, bases de conocimiento (hechos y reglas), motores de inferencia con razonamiento hacia adelante y hacia atrás, y explicación de conclusiones.
- **Visión por computador aplicada**: clasificación de imágenes para tareas del mundo real (proyecto final: clasificación de tendencias de mercado bursátil a partir de patrones de velas japonesas).
- **Consideraciones éticas de la IA**: sesgo y privacidad en el diseño de soluciones de aprendizaje automático.

## Cosas a tener en cuenta

- Los laboratorios de este curso se desarrollaron en pareja.
- `Minimax-Poda-Alfa-Beta-PTIA` y `Motor-de-Inferencia-Sistema-Basado-en-Reglas-PTIA` provienen del mismo laboratorio original de "Búsqueda adversaria" (labs 3/4 y 4/4 del curso), separados aquí en dos repositorios porque cada uno corresponde a una entrega y un tema distintos.
- `SITMF-PTIA` es el proyecto final del curso: un clasificador visual de tendencias de mercado financiero basado en IA y visión por computador.

## Herramientas

- Python (Jupyter/Google Colab)
- Redes neuronales / frameworks de deep learning
- Visión por computador

## Cómo usar este repositorio

Este repositorio no contiene código directamente: es una colección de repositorios independientes (laboratorios y proyecto final), organizados por carpetas. Cada carpeta es un submódulo de git que apunta al repositorio real de esa actividad.

- **Para consultar una actividad puntual**: entra directamente a su carpeta en GitHub (o navega el submódulo) y revisa su propio README.
- **Para tener todo el contenido en tu máquina**:

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Principios-y-Tecnologias-IA.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
