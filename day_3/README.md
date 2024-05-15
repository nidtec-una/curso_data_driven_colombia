## Configuración del Entorno Conda

Para trabajar con los cuadernos Jupyter proporcionados, necesitarás configurar un entorno Conda e instalar las bibliotecas requeridas. Sigue estos pasos para configurar tu entorno:

### 1. Crear el entorno Conda
Primero, crea un nuevo entorno Conda con Python 3.11. Puedes cambiar el nombre del entorno y la versión de Python según tus necesidades:

```bash
conda create -n mi_entorno python=3.11
```

### 2. Activar el entorno
Una vez creado el entorno, actívalo con:

```bash
conda activate mi_entorno
```

### 3. Instalar las bibliotecas necesarias
Instala todas las bibliotecas requeridas utilizando el siguiente comando. Esto incluirá todos los paquetes necesarios para los cuadernos:

```bash
conda install numpy pandas matplotlib seaborn scikit-learn plotly pytorch -c pytorch -c conda-forge
```

Este comando instala los paquetes utilizando los canales ``pytorch`` y ``conda-forge``, que contienen los paquetes necesarios que no están disponibles en el canal predeterminado de Conda.

### 4. Verificar la instalación
Para asegurarte de que todas las bibliotecas se han instalado correctamente, puedes iniciar un cuaderno Jupyter y ejecutar el siguiente código:

```python3
import numpy
import pandas
import matplotlib
import seaborn
import sklearn
import plotly
import torch

print("Todos los paquetes están instalados correctamente!")
```

### 5. Comenzar a trabajar
Ahora que tu entorno está configurado y las bibliotecas están instaladas, puedes comenzar a trabajar en los cuadernos Jupyter.

Recuerda activar tu entorno Conda ``mi_entorno`` cada vez que trabajes en este proyecto para acceder a estas bibliotecas.


