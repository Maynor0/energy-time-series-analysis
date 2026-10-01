# Datos

El notebook principal utiliza el archivo:

```text
energy_dataset.csv
```

Este archivo contiene datos horarios relacionados con el sistema eléctrico,
incluyendo carga real, carga prevista, precios y generación de distintas
fuentes de energía.

## Ubicación esperada

Coloca el archivo directamente en esta carpeta:

```text
data/energy_dataset.csv
```

La estructura del proyecto debe quedar así:

```text
energia-series-temporales-python/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── energia_series_temporales.ipynb
└── data/
    ├── README.md
    └── energy_dataset.csv
```

## Obtención del archivo

El archivo de datos no se incluye en este repositorio. Debe obtenerse desde
la fuente original del dataset, respetando sus condiciones de uso y licencia.

Una vez descargado, renómbralo como:

```text
energy_dataset.csv
```

y guárdalo dentro de esta carpeta.

## Ejecución

Después de colocar el archivo en la ubicación indicada, abre el notebook:

```text
notebooks/energia_series_temporales.ipynb
```

y ejecuta sus celdas en orden.

## Nota sobre el control de versiones

El archivo `energy_dataset.csv` está excluido del repositorio mediante
`.gitignore`. El repositorio conserva este README para documentar qué datos
se necesitan y dónde deben colocarse.