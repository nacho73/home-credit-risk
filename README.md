# Home Credit Default Risk (Kaggle) 📊

🇪🇸 **[Versión en Español abajo]**

## 🇬🇧 English

### Description
Machine Learning project based on the **Home Credit Default Risk** competition/dataset from Kaggle. 

The notebook implements a complete end-to-end workflow: EDA → data cleaning → preparation / feature engineering → model training → submission generation.

### Repository Structure
* `notebooks/home_credit_risk_notebook.ipynb`: Main project notebook.
* `requirements.txt`: Dependencies required to reproduce the local environment.
* `reports/figures/`: Folder for generated figures and exports (optional).
* `src/`: Auxiliary utilities and scripts (optional).

### Data (Not Included)
> Due to licensing and size constraints, the raw data is not included in this repository.

1. Download the dataset directly from Kaggle: [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/data).
2. Place the extracted CSV files in the following directory: `data/raw/home-credit-default-risk/`

### Local Execution

**1. Create and activate a virtual environment (recommended)**
`python -m venv .venv`

* **Windows:** `.venv\Scripts\activate`
* **macOS/Linux:** `source .venv/bin/activate`

**2. Install dependencies**
`pip install -r requirements.txt`

**3. Launch JupyterLab and open the notebook**
`jupyter lab`

*Open:* `notebooks/home_credit_risk_notebook.ipynb`

### Execution on Kaggle
The notebook can be directly published and executed on Kaggle by adding the *Home Credit Default Risk* dataset as an Input. File paths are automatically resolved based on the environment (Kaggle vs. Local) to locate the CSV files seamlessly.

### Results
* **Kaggle (Private Score):** 0.79505
* **Ranking:** 564 / 7180 — (12/02/2026)
* **Workflow:** EDA → Cleaning → Feature Engineering / Preparation → Modeling → Submission

### Author
**José Ignacio Gavara**

---

## 🇪🇸 Español

### Descripción
Proyecto de Machine Learning basado en la competición y dataset **Home Credit Default Risk** de Kaggle.

El notebook implementa un flujo completo de principio a fin: EDA → limpieza de datos → preparación / feature engineering → entrenamiento del modelo → generación de submission.

### Estructura del repositorio
* `notebooks/home_credit_risk_notebook.ipynb`: Notebook principal del proyecto.
* `requirements.txt`: Dependencias para reproducir el entorno local.
* `reports/figures/`: Carpeta para figuras y exportaciones (opcional).
* `src/`: Utilidades auxiliares y scripts (opcional).

### Datos (No incluidos)
> Por motivos de licencia y tamaño, los datos en bruto no se incluyen en este repositorio.

1. Descargar el dataset desde Kaggle: [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/data).
2. Colocar los archivos CSV en la siguiente ruta: `data/raw/home-credit-default-risk/`

### Ejecución local

**1. Crear y activar un entorno virtual (recomendado)**
`python -m venv .venv`

* **Windows:** `.venv\Scripts\activate`
* **macOS/Linux:** `source .venv/bin/activate`

**2. Instalar dependencias**
`pip install -r requirements.txt`

**3. Lanzar JupyterLab y abrir el notebook**
`jupyter lab`

*Abrir:* `notebooks/home_credit_risk_notebook.ipynb`

### Ejecución en Kaggle
El notebook puede publicarse y ejecutarse en Kaggle añadiendo el dataset *Home Credit Default Risk* como Input. Las rutas se resuelven automáticamente en función del entorno (Kaggle vs local) para localizar los archivos CSV sin problemas.

### Resultados
* **Kaggle (Private Score):** 0.79505
* **Ranking:** 564 / 7180 — (12/02/2026)
* **Flujo:** EDA → Limpieza → Feature Engineering / Preparación → Modelo → Submission

### Autor
**José Ignacio Gavara**
