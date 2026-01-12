# OnlineFood

## Descripción

OnlineFood es un proyecto de análisis exploratorio de datos (EDA) sobre un conjunto de datos de pedidos/servicios de comida online. Este repositorio contiene el cuaderno principal de EDA, el dataset usado y documentación básica para reproducir el análisis.


## Estructura del repositorio

```
README.md
PORTADA.md         # Portada del proyecto (visual / presentación)
requirements.txt   # Dependencias para ejecutar el notebook
EDA/               # Carpeta con el análisis exploratorio
	EDA.ipynb        # Notebook principal
	onlinefoods.csv  # Dataset (si está incluido)
```


## Cómo reproducir el EDA (entorno mínimo)

1. Crear y activar un entorno virtual (recomendado):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Instalar dependencias:

```bash
pip install -r requirements.txt
```

3. Abrir el notebook:

```bash
jupyter notebook EDA/EDA.ipynb
```

4. Ejecuta las celdas del notebook en orden. El notebook contiene comentarios y visualizaciones para guiar el análisis.

## Dataset

El dataset principal se llama `onlinefoods.csv` y está pensado para análisis de pedidos y comportamiento de usuarios/establecimientos. Revisa el notebook `EDA/EDA.ipynb` para detalles sobre las columnas, limpieza y transformaciones aplicadas.


