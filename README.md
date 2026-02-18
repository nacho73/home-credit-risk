
# Home Credit Default Risk (Kaggle)

Proyecto de *Machine Learning* basado en la competición/dataset **Home Credit Default Risk** de Kaggle.  
El notebook implementa un flujo completo: **EDA → limpieza → preparación/feature engineering → entrenamiento → generación de submission**.


## Estructura del repositorio
- `notebooks/home_credit_risk_notebook.ipynb`: notebook principal del proyecto.
- `requirements.txt`: dependencias para reproducir el entorno local.
- `reports/figures/`: carpeta para figuras/exportaciones (opcional).
- `src/`: utilidades auxiliares (opcional).


## Datos (no incluidos)
Por licencia y tamaño, los datos no se incluyen en este repositorio.

1. Descargar el dataset desde Kaggle: **Home Credit Default Risk**.
2. Colocar los CSV en:

data/raw/home-credit-default-risk/

## Ejecución local
1. Crear y activar un entorno virtual (recomendado)
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

2. Instalar dependencias
   pip install -r requirements.txt
  
3. Lanzar JupyterLab y abrir el notebook
   
   jupyter lab
   
   Abrir: `notebooks/home_credit_risk_notebook.ipynb`


## Ejecución en Kaggle

El notebook puede publicarse/ejecutarse en Kaggle añadiendo el dataset **Home Credit Default Risk** como *Input*.
Las rutas se resuelven en función del entorno (Kaggle vs local) para localizar los CSV.


## Resultados

* **Kaggle (Private Score): 0.79505**
* **Ranking:** 564 / 7180 — **12/02/2026**
* Flujo: **EDA → limpieza → feature engineering / preparación → modelo → submission**


## Autor

José Ignacio Gavara


