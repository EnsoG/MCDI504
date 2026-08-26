# CuídateDeLaDiabete - Predicción de diabetes

Este repositorio presenta un proyecto de análisis de datos y aprendizaje automático para la predicción de diabetes en pacientes de la India. El estudio compara modelos de referencia con arquitecturas de redes neuronales para evaluar su capacidad predictiva y generalización.

## Descripción general

El proyecto corresponde a la Fase 3 del curso y aborda la clasificación supervisada y la regresión aplicada sobre variables clínicas, antropométricas y de estilo de vida. Se utiliza el dataset de pacientes para comparar distintos enfoques de modelado y analizar el comportamiento de las redes neuronales en un problema de salud.

## Objetivos

- Explorar y preparar el dataset para modelado.
- Evaluar el rendimiento de modelos de clasificación y regresión.
- Comparar algoritmos tradicionales con redes neuronales.
- Interpretar los resultados y su relevancia clínica.
- Documentar el proceso de análisis de forma reproducible.

## Dataset

El archivo principal se encuentra en:

- `data/diabetes_prediction_india.csv`

Contiene información clínica y demográfica de pacientes, así como variables relacionadas con riesgo y diagnóstico de diabetes.

## Estructura del proyecto

- `data/` : archivos del conjunto de datos.
- `Notebooks/` : cuaderno principal de análisis y modelado.
- `figures/` : gráficos y visualizaciones generadas.
- `README.md` : documentación del proyecto.
- `requirements.txt` : dependencias del proyecto.

## Notebook principal

- `Notebooks/F3_RedesNeuronales.ipynb`

En este cuaderno se desarrollan las etapas principales del proyecto, incluyendo:

- exploración inicial del dataset,
- limpieza y preparación de variables,
- codificación de atributos categóricos,
- entrenamiento y evaluación de modelos,
- análisis comparativo de arquitecturas neuronales,
- visualización de resultados.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Requisitos

Se recomienda utilizar Python 3.10 o superior y un entorno virtual para mantener dependencias aisladas y reproducibles.

## Instalación

### macOS

```bash
cd "/Users/enso/Documents/Machine Learning/Semana 3/Sumativa 2"
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (PowerShell)

```powershell
cd "C:\ruta\al\proyecto\Sumativa 2"
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Windows (CMD)

```cmd
cd C:\ruta\al\proyecto\Sumativa 2
python -m venv .venv
.\.venv\Scripts\activate.bat
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Ejecución

### Opción 1: Jupyter Notebook

1. Abrir una terminal dentro del proyecto.
2. Activar el entorno virtual.
3. Ejecutar:

```bash
jupyter notebook
```

4. Ir a la carpeta `Notebooks/`.
5. Abrir `F3_RedesNeuronales.ipynb`.
6. Ejecutar todas las celdas del notebook.

### Opción 2: VS Code

1. Abrir la carpeta del proyecto en VS Code.
2. Seleccionar el intérprete del entorno virtual `.venv`.
3. Abrir el notebook `Notebooks/F3_RedesNeuronales.ipynb`.
4. Ejecutar las celdas del análisis.

## Resultados esperados

El proyecto busca identificar qué enfoque ofrece la mejor capacidad predictiva para el diagnóstico de diabetes, comparando modelos tradicionales y redes neuronales con distintas configuraciones arquitectónicas.

## Nota

Este repositorio está orientado a fines académicos y de análisis de datos dentro del marco de la asignatura correspondiente.