# Home Credit Default Risk — EDA (Kaggle)

Este repositorio contiene un **notebook de exploración y preparación de datos (EDA)** para la competición/dataset **Home Credit Default Risk** de Kaggle.

## Qué hay aquí
- `notebooks/home_credit_eda.ipynb`: notebook principal (EDA).
- `requirements.txt`: dependencias para reproducir el entorno.
- `reports/figures/`: carpeta para guardar imágenes/exportaciones (opcional).
- `src/`: código auxiliar (opcional; por ahora vacío).

## Datos (no incluidos)
Por licencia/tamaño, **los datos no se suben a GitHub**.

1. Descarga el dataset desde Kaggle: **Home Credit Default Risk**.
2. Coloca los CSV en la ruta:

```
data/raw/home-credit-default-risk/
```

> Nota: Si tu notebook usa otra ruta, ajusta el bloque de “paths” dentro del notebook a esta estructura, o cambia esta ruta en el README.

## Cómo ejecutar
1. Crea y activa un entorno (opcional pero recomendado)
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

2. Instala dependencias
```bash
pip install -r requirements.txt
```

3. Lanza JupyterLab
```bash
jupyter lab
```

y abre `notebooks/home_credit_eda.ipynb`.

## Resultados
- Este repo está enfocado a EDA / limpieza / análisis de variables.
- Si más adelante añades modelado (baseline + CV + AUC), crea un notebook extra (por ejemplo `notebooks/02_modeling.ipynb`) y resume métricas aquí.

## Autor
Nacho
