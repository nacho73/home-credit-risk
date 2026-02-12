# Home Credit Default Risk —(Kaggle)

Este repositorio contiene un **notebook** para la competición/dataset **Home Credit Default Risk** de Kaggle. La competición había finalizado cuando se envió el archivo csv generado por el modelo incluido en el notebook, pero Kaggle la evaluó con un Private Score de 0,79505, correspondiente al puesto 564 de 7180 envíos a fecha de hoy, 12 de febrero de 2026, lo que supone estar en el top 10% de archivos enviados.

## Qué hay aquí
- `notebooks/home_credit_eda.ipynb`: notebook enviado. 
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

y abre `notebooks/home_credit_risk_notebook.ipynb`.

## Resultados

- **Kaggle (Private Score): 0.79505**
- **Ranking:** 564 / 7180 (≈ top 8%) — **12/02/2026**
- Pipeline: **EDA → limpieza → feature engineering / preparación → modelo → submission**.

## Autor
José Ignacio Gavara
