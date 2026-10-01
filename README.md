# Análisis de series temporales de energía

Análisis exploratorio y estadístico de datos horarios del sistema eléctrico
europeo mediante Python y Jupyter Notebook.

El proyecto estudia la evolución temporal de la carga eléctrica, los precios
de la energía y la generación renovable. El objetivo es identificar patrones
horarios, semanales y estacionales, así como analizar las relaciones entre las
principales variables energéticas.

## Objetivos

- Analizar la evolución temporal de la demanda eléctrica.
- Comparar el comportamiento de la carga entre días laborables y fines de semana.
- Estudiar los patrones horarios y semanales.
- Analizar la relación entre carga, precio y generación renovable.
- Examinar la estacionalidad de la serie.
- Comprobar la estacionariedad de la carga diaria.
- Comparar la carga real con la carga prevista disponible en los datos.

## Contenido del repositorio

```text
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── energia_series_temporales.ipynb
└── data/
    └── README.md
```

- `notebooks/energia_series_temporales.ipynb`: notebook principal con la
  preparación, el análisis y las visualizaciones.
- `requirements.txt`: librerías Python necesarias para ejecutar el notebook.
- `.gitignore`: archivos locales y temporales que no deben subirse a GitHub.
- `data/README.md`: instrucciones sobre la ubicación del dataset.

## Datos

El notebook utiliza el archivo `energy_dataset.csv`.

El archivo de datos no se incluye en este repositorio porque no se redistribuye
directamente desde GitHub. Para ejecutar el análisis, coloca el archivo en la
siguiente ubicación:

```text
data/energy_dataset.csv
```

El dataset debe conservar su nombre y estructura originales para que el
notebook pueda leerlo correctamente.

## Instalación

Clona el repositorio y accede a su carpeta:

```bash
git clone URL_DEL_REPOSITORIO
cd energia-series-temporales-python
```

Crea y activa un entorno virtual:

```bash
python -m venv .venv
```

En Windows:

```bash
.venv\Scripts\activate
```

En macOS o Linux:

```bash
source .venv/bin/activate
```

Instala las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecución

Coloca `energy_dataset.csv` en la carpeta `data/` y abre Jupyter:

```bash
jupyter notebook
```

A continuación, abre:

```text
notebooks/energia_series_temporales.ipynb
```

Ejecuta las celdas en orden, desde el principio hasta el final.

## Principales resultados

El análisis permite estudiar:

- La evolución de la carga eléctrica a lo largo del tiempo.
- Las diferencias entre horas, días laborables y fines de semana.
- Los patrones semanales y estacionales.
- La relación entre la demanda, el precio y la generación renovable.
- La diferencia entre la carga real y la previsión disponible.
- Las propiedades estadísticas de la serie diaria.

Los resultados detallados, las tablas y las visualizaciones se encuentran dentro
del notebook.

## Alcance

Este proyecto tiene un enfoque exploratorio y estadístico. No se incluye un
modelo predictivo porque esta versión se centra en comprender la dinámica de
los datos y no en generar predicciones futuras.

Una ampliación posterior tendría sentido si compara un modelo propio con la
previsión de carga ya disponible en el dataset y demuestra una mejora mediante
métricas como MAE o RMSE.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- statsmodels
