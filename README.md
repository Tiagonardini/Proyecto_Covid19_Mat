# Proyecto_Covid19_Mat

Este proyecto se centra en el análisis de datos relacionados con el COVID-19. 
Para su correcta ejecución, sigue los pasos de configuración y preparación del entorno.

## 1. Creación del Entorno de Desarrollo
Abre tu terminal (ej. VS Code Terminal) en la raíz del proyecto (```Proyecto_Covid19_Mat```) y ejecuta:

```python -m venv venv```

## 2. Activar entorno virtual para Windows:

```.\venv\Scripts\activate```

Verás (venv) en tu terminal una vez activado.

## 3. Instalación de Dependencias
Con el entorno virtual activado, instala todas las librerías listadas en ```requirements.txt```:

```pip install -r requirements.txt```

## 4. (Opcional) Si encuentras errores de compilación (C/C++)
Si aparecen errores relacionados con compiladores (ej. al instalar ```numpy``` o ```pandas```), es probable que falten las Build Tools de C++.

### 1. Descarga las Build Tools para Visual Studio:
Obtén el instalador desde: https://visualstudio.microsoft.com/es/downloads/.

### 2. Instala "Desarrollo de escritorio con C++":
Ejecuta el instalador. En "Cargas de trabajo" (Workloads), selecciona "Desarrollo de escritorio con C++" y procede con la instalación/modificación.

### 3. Reintento:
Cierra y reabre tu terminal. ```Activa el entorno virtual``` e ```instala las dependencias```

## 4. Ejecución del Proyecto
Abre la carpeta del proyecto en Visual Studio Code.

Abre el notebook mat4.ipynb. Puedes ejecutar las celdas del notebook usando ```Ctrl + Alt + Enter``` o los botones de ejecución.
