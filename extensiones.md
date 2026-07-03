# Extensiones recomendadas para Ciencia de Datos en VS Code

Este documento contiene una lista organizada de extensiones recomendadas para trabajar con **Python, Jupyter Notebook, Markdown, SQL, análisis de datos, APIs, Git y autocompletado** dentro de Visual Studio Code.

La idea es tener una guía rápida para instalar todo lo necesario en una nueva computadora o entorno de trabajo.

---

## Requisitos previos

Antes de instalar las extensiones, se recomienda tener instalado:

* Visual Studio Code
* Python
* Git
* SQL Server / SQL Server Management Studio, si se trabajará con bases de datos SQL Server

También es recomendable verificar que el comando `code` funcione desde PowerShell o CMD:

```powershell
code --version
```

Si aparece la versión de VS Code, ya puedes instalar extensiones desde la terminal.

---

# 1. Extensiones principales para Python y Ciencia de Datos

| Nombre              | ID de extensión                | ¿Para qué sirve?                                 | ¿Qué hace?                                                                                                 | Comando de instalación                                  |
| ------------------- | ------------------------------ | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| Python              | `ms-python.python`             | Trabajar con Python dentro de VS Code            | Permite ejecutar archivos `.py`, seleccionar intérpretes, depurar código y trabajar con entornos virtuales | `code --install-extension ms-python.python`             |
| Pylance             | `ms-python.vscode-pylance`     | Mejorar el autocompletado de Python              | Da sugerencias inteligentes, detecta errores, muestra información de funciones, clases, tipos y librerías  | `code --install-extension ms-python.vscode-pylance`     |
| Jupyter             | `ms-toolsai.jupyter`           | Trabajar con notebooks dentro de VS Code         | Permite abrir, crear y ejecutar archivos `.ipynb`, usando celdas de código y texto                         | `code --install-extension ms-toolsai.jupyter`           |
| Jupyter Renderers   | `ms-toolsai.jupyter-renderers` | Mejorar la visualización de salidas en notebooks | Permite visualizar gráficos, imágenes, tablas, salidas interactivas y otros formatos dentro de Jupyter     | `code --install-extension ms-toolsai.jupyter-renderers` |
| Python Debugger     | `ms-python.debugpy`            | Depurar código Python                            | Permite usar puntos de interrupción, revisar variables y ejecutar el código paso a paso                    | `code --install-extension ms-python.debugpy`            |
| Python Environments | `ms-python.vscode-python-envs` | Manejar entornos de Python                       | Ayuda a administrar entornos virtuales, intérpretes y dependencias por proyecto                            | `code --install-extension ms-python.vscode-python-envs` |

---

# 2. Extensiones para autocompletado, ayuda y calidad de código

| Nombre                         | ID de extensión                                       | ¿Para qué sirve?                        | ¿Qué hace?                                                                        | Comando de instalación                                                         |
| ------------------------------ | ----------------------------------------------------- | --------------------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ |
| IntelliCode                    | `VisualStudioExptTeam.vscodeintellicode`              | Mejorar sugerencias de código           | Da recomendaciones inteligentes mientras escribes código                          | `code --install-extension VisualStudioExptTeam.vscodeintellicode`              |
| IntelliCode API Usage Examples | `VisualStudioExptTeam.intellicode-api-usage-examples` | Ver ejemplos de uso de APIs y librerías | Muestra ejemplos de cómo se usan funciones, métodos o librerías dentro del código | `code --install-extension VisualStudioExptTeam.intellicode-api-usage-examples` |
| Ruff                           | `charliermarsh.ruff`                                  | Revisar errores y estilo en Python      | Detecta errores, imports no usados, problemas de formato y malas prácticas        | `code --install-extension charliermarsh.ruff`                                  |
| Black Formatter                | `ms-python.black-formatter`                           | Formatear código Python automáticamente | Ordena y da formato uniforme al código Python                                     | `code --install-extension ms-python.black-formatter`                           |
| autoDocstring                  | `njpwerner.autodocstring`                             | Documentar funciones de Python          | Genera automáticamente docstrings para funciones, clases y métodos                | `code --install-extension njpwerner.autodocstring`                             |

---

# 3. Extensiones para Markdown y documentación

| Nombre              | ID de extensión                  | ¿Para qué sirve?                   | ¿Qué hace?                                                                     | Comando de instalación                                    |
| ------------------- | -------------------------------- | ---------------------------------- | ------------------------------------------------------------------------------ | --------------------------------------------------------- |
| Markdown All in One | `yzhang.markdown-all-in-one`     | Escribir documentación en Markdown | Ayuda con tablas de contenido, atajos, vista previa, listas y formato Markdown | `code --install-extension yzhang.markdown-all-in-one`     |
| markdownlint        | `DavidAnson.vscode-markdownlint` | Revisar archivos Markdown          | Detecta errores de estilo, estructura y formato en documentos `.md`            | `code --install-extension DavidAnson.vscode-markdownlint` |

---

# 4. Extensiones para datos, CSV, SQL y APIs

| Nombre             | ID de extensión           | ¿Para qué sirve?                      | ¿Qué hace?                                                                            | Comando de instalación                             |
| ------------------ | ------------------------- | ------------------------------------- | ------------------------------------------------------------------------------------- | -------------------------------------------------- |
| Data Wrangler      | `ms-toolsai.datawrangler` | Explorar y limpiar datos              | Permite trabajar visualmente con datos, especialmente DataFrames y archivos CSV       | `code --install-extension ms-toolsai.datawrangler` |
| Rainbow CSV        | `mechatroner.rainbow-csv` | Leer mejor archivos CSV               | Colorea columnas de archivos CSV/TSV para entenderlos mejor                           | `code --install-extension mechatroner.rainbow-csv` |
| SQL Server / MSSQL | `ms-mssql.mssql`          | Conectarse a SQL Server desde VS Code | Permite ejecutar consultas SQL, conectarse a servidores y trabajar con bases de datos | `code --install-extension ms-mssql.mssql`          |
| REST Client        | `humao.rest-client`       | Probar APIs desde VS Code             | Permite hacer peticiones HTTP desde archivos `.http` o `.rest`                        | `code --install-extension humao.rest-client`       |

---

# 5. Extensión para Git y control de versiones

| Nombre  | ID de extensión   | ¿Para qué sirve?           | ¿Qué hace?                                                        | Comando de instalación                     |
| ------- | ----------------- | -------------------------- | ----------------------------------------------------------------- | ------------------------------------------ |
| GitLens | `eamodio.gitlens` | Mejorar el trabajo con Git | Muestra historial, autores, cambios, ramas y evolución del código | `code --install-extension eamodio.gitlens` |

---

# 6. Extensión opcional de IA para programación

| Nombre         | ID de extensión  | ¿Para qué sirve?              | ¿Qué hace?                                                                    | Comando de instalación                    |
| -------------- | ---------------- | ----------------------------- | ----------------------------------------------------------------------------- | ----------------------------------------- |
| GitHub Copilot | `GitHub.copilot` | Asistencia de IA al programar | Sugiere código, funciones, fragmentos y posibles soluciones mientras escribes | `code --install-extension GitHub.copilot` |

> Nota: GitHub Copilot puede requerir iniciar sesión con una cuenta de GitHub y tener acceso habilitado al servicio.

---

# 7. Instalación rápida de extensiones recomendadas

Ejecutar en PowerShell o CMD:

```powershell
code --install-extension ms-python.python
code --install-extension ms-python.vscode-pylance
code --install-extension ms-toolsai.jupyter
code --install-extension ms-toolsai.jupyter-renderers
code --install-extension ms-python.debugpy
code --install-extension ms-python.vscode-python-envs
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension VisualStudioExptTeam.intellicode-api-usage-examples
code --install-extension charliermarsh.ruff
code --install-extension ms-python.black-formatter
code --install-extension njpwerner.autodocstring
code --install-extension yzhang.markdown-all-in-one
code --install-extension DavidAnson.vscode-markdownlint
code --install-extension ms-toolsai.datawrangler
code --install-extension mechatroner.rainbow-csv
code --install-extension ms-mssql.mssql
code --install-extension humao.rest-client
code --install-extension eamodio.gitlens
```

---

# 8. Instalación opcional de GitHub Copilot

```powershell
code --install-extension GitHub.copilot
```

---

# 9. Librerías recomendadas de Python para Ciencia de Datos

Después de instalar las extensiones, se recomienda instalar las librerías principales de Python.

```powershell
pip install numpy pandas matplotlib seaborn scikit-learn jupyter ipykernel openpyxl
```

---

## ¿Para qué sirve cada librería?

| Librería     | ¿Para qué sirve?            | ¿Qué hace?                                                                            |
| ------------ | --------------------------- | ------------------------------------------------------------------------------------- |
| NumPy        | Cálculo numérico            | Permite trabajar con arreglos, matrices y operaciones matemáticas rápidas             |
| Pandas       | Análisis de datos tabulares | Permite leer, limpiar, transformar y analizar datos en tablas                         |
| Matplotlib   | Visualización de datos      | Permite crear gráficos básicos como líneas, barras, histogramas y dispersión          |
| Seaborn      | Visualización estadística   | Permite crear gráficos estadísticos más fáciles y visualmente ordenados               |
| Scikit-learn | Machine Learning clásico    | Permite crear modelos de regresión, clasificación, clustering y evaluación de modelos |
| Jupyter      | Notebooks interactivos      | Permite trabajar con documentos que combinan código, texto, gráficos y resultados     |
| ipykernel    | Kernel para Jupyter         | Permite usar un entorno de Python dentro de notebooks                                 |
| openpyxl     | Archivos Excel              | Permite leer y escribir archivos `.xlsx` desde Python y pandas                        |

---

# 10. Verificar instalación de Python y librerías

Ejecutar:

```powershell
python --version
pip --version
```

Luego probar si las librerías funcionan:

```powershell
python -c "import numpy, pandas, matplotlib, sklearn, jupyter, openpyxl; print('Librerías instaladas correctamente')"
```

---

# 11. Crear un entorno virtual recomendado

Dentro de la carpeta del proyecto:

```powershell
python -m venv .venv
```

Activar el entorno virtual en PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Instalar librerías dentro del entorno:

```powershell
pip install numpy pandas matplotlib seaborn scikit-learn jupyter ipykernel openpyxl
```

Registrar el entorno para Jupyter:

```powershell
python -m ipykernel install --user --name ciencia-datos --display-name "Python - Ciencia de Datos"
```

---

# 12. Estructura recomendada para proyectos de Ciencia de Datos

```text
mi-proyecto-ciencia-datos/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── analisis_inicial.ipynb
│
├── src/
│   └── procesamiento.py
│
├── reports/
│   └── resultados.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Explicación de carpetas

| Carpeta o archivo  | Uso                                              |
| ------------------ | ------------------------------------------------ |
| `data/raw/`        | Datos originales sin modificar                   |
| `data/processed/`  | Datos limpiados o transformados                  |
| `notebooks/`       | Notebooks de análisis exploratorio               |
| `src/`             | Código Python reutilizable                       |
| `reports/`         | Reportes, gráficos, conclusiones y documentación |
| `README.md`        | Explicación general del proyecto                 |
| `requirements.txt` | Lista de librerías necesarias                    |
| `.gitignore`       | Archivos o carpetas que Git debe ignorar         |

---

# 13. Archivo `requirements.txt` recomendado

Contenido sugerido:

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
ipykernel
openpyxl
```

Para instalar todo desde `requirements.txt`:

```powershell
pip install -r requirements.txt
```

---

# 14. Archivo `.gitignore` recomendado para proyectos Python

```gitignore
# Entornos virtuales
.venv/
venv/
env/

# Caché de Python
__pycache__/
*.pyc
*.pyo

# Jupyter
.ipynb_checkpoints/

# Archivos del sistema
.DS_Store
Thumbs.db

# Archivos de VS Code
.vscode/

# Datos pesados o sensibles
data/raw/
data/processed/

# Variables de entorno
.env
```

---

# 15. Recomendación final

Para comenzar en Ciencia de Datos con VS Code, las extensiones más importantes son:

1. Python
2. Pylance
3. Jupyter
4. Jupyter Renderers
5. Python Debugger
6. Ruff
7. Black Formatter
8. Markdown All in One
9. Data Wrangler
10. Rainbow CSV
11. SQL Server / MSSQL
12. GitLens

Con esas extensiones ya se puede trabajar correctamente con:

* Python
* Notebooks Jupyter
* Markdown
* Archivos CSV
* SQL Server
* Git
* Limpieza y análisis de datos
* Documentación de proyectos
* Visualización de resultados
* Machine Learning básico
