# Aprendizaje automatico

Notebook de la Clase 1: exploración del dataset Iris, visualización y división train/test con pandas, scikit-learn y matplotlib.

## Requisitos

- Python 3.10 o superior
- pip

## Configuración

1. Clonar o descargar este repositorio y entrar al directorio:

   ```bash
   cd tp1
   ```

2. (Recomendado) Crear y activar un entorno virtual:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # macOS / Linux
   # .venv\Scripts\activate    # Windows
   ```

3. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Registrar el entorno como kernel de Jupyter (necesario para Cursor / VS Code):

   ```bash
   python -m ipykernel install --user --name=tp1 --display-name="Python (tp1)"
   ```

## Ejecutar el notebook

### Cursor / VS Code (recomendado)

1. Abrir la carpeta `tp1` como workspace (no solo el archivo `.ipynb`).
2. Abrir `Clase01-Intro-ML.ipynb`.
3. En la esquina superior derecha del notebook, elegir el kernel **Python (tp1)** o **`.venv` (Python 3.x)**.
4. Ejecutar las celdas.

Si el kernel no aparece, usar **Command Palette → Python: Select Interpreter** y elegir `./.venv/bin/python`.

### Jupyter Notebook

```bash
pip install notebook
jupyter notebook Clase01-Intro-ML.ipynb
```

En el menú **Kernel → Change kernel**, seleccionar **Python (tp1)**.

### JupyterLab

```bash
pip install jupyterlab
jupyter lab Clase01-Intro-ML.ipynb
```

## Dependencias

| Paquete       | Uso en el notebook                          |
|---------------|---------------------------------------------|
| `pandas`      | Manipulación de datos en DataFrames         |
| `scikit-learn`| Carga del dataset Iris y `train_test_split` |
| `matplotlib`  | Gráficos de exploración                     |
