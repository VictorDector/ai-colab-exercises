# AI Colab Exercises

Repositorio de ejercicios y prácticas de Inteligencia Artificial realizados en Google Colab (notebooks `.ipynb`).
El objetivo es documentar el proceso y facilitar la verificación de resultados (tablas, cálculos y gráficas) a partir del temario del curso/máster.

## Estructura del repositorio

- `00_setup/` — utilidades y funciones comunes (si aplica)
- `01_supervised/` — aprendizaje supervisado (árboles, regresión, SVM, etc.)
- `02_unsupervised/` — aprendizaje no supervisado (clustering, reducción de dimensión, etc.)
- `03_deep_learning/` — redes neuronales y deep learning
- `04_nlp/` — procesamiento de lenguaje natural
- `05_cv/` — computer vision (visión por computador)
- `06_rl/` — aprendizaje por refuerzo
- `case_studies/` — casos prácticos completos (entregables tipo “informe” + notebook de verificación)

## Convenciones (para mantener orden)

### Nombres de notebooks
Formato recomendado:
- `EjXX_Tema.ipynb` o `Caso_Tema.ipynb`

Ejemplos:
- `Ej03_ArbolesDecision_IG.ipynb`
- `Ej07_Clustering_KMeans.ipynb`

### Contenido mínimo dentro de cada notebook
Cada notebook intenta incluir:
1. Enunciado (literal o resumido)
2. Método (según el temario)
3. Desarrollo (pasos + código)
4. Resultados (tablas/gráficas)
5. Conclusión (una frase verificable)

## Cómo ejecutar los notebooks

### Opción A — Abrir desde GitHub en Google Colab (recomendado)
1. Abre el notebook `.ipynb` desde GitHub.
2. Copia la URL del notebook.
3. Ve a `https://colab.research.google.com/`
4. `File → Open notebook → GitHub` y pega la URL (o busca el repo).
5. Ejecuta: `Runtime → Run all`

### Opción B — Ejecutar en local (opcional)
Requiere Python 3 y Jupyter:
1. Instala dependencias si existe `requirements.txt`
2. Ejecuta `jupyter notebook` y abre el `.ipynb`

## Índice de ejercicios (actualizar)

### 01_supervised
- `01_supervised/Ej03_ArbolesDecision_IG.ipynb` — Árboles de decisión: cálculo de entropía y ganancia de información (IG)

### 02_unsupervised
- (pendiente)

### 03_deep_learning
- (pendiente)

### 04_nlp
- (pendiente)

### 05_cv
- (pendiente)

### 06_rl
- (pendiente)

### case_studies
- (pendiente)

## Notas
- Este repositorio es de práctica/estudio. Los notebooks se centran en seguir el temario y dejar resultados verificables.
- Si un notebook requiere datasets externos, se indicará al inicio del notebook cómo obtenerlos.
