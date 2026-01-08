# Whale Migration Predictor

Este proyecto forma parte del **Trabajo Fin de Máster en Big Data**. Su objetivo es **desarrollar un modelo predictivo y una visualización interactiva para analizar y anticipar las rutas migratorias de ballenas** a partir de datos satelitales y oceanográficos.

## Objetivos
- Recopilar y limpiar datos satelitales y oceanográficos relevantes (temperatura, corrientes, avistamientos).
- Implementar un modelo predictivo (Machine Learning) para estimar rutas migratorias.
- Diseñar un dashboard interactivo para visualizar patrones y predicciones.
- Evaluar el impacto de variables ambientales en las migraciones.

## Características principales
- Integración de datos reales desde **OBIS**, **NOAA** y **GBIF**.
- Procesamiento y análisis con **Python** y **R**.
- Modelos predictivos basados en **Machine Learning**.
- Visualización interactiva mediante **Power BI**, **Tableau** o librerías como **Plotly Dash**.
- Arquitectura escalable para manejo de grandes volúmenes de datos (Spark/Hadoop).

## Estructura del repositorio
```
whale-migration-predictor/
│
├── data/                # Datasets originales y procesados
├── notebooks/           # Jupyter Notebooks para análisis y pruebas
├── src/                 # Código fuente (scripts de limpieza, modelado, visualización)
├── docs/                # Documentación del proyecto
├── README.md            # Descripción del proyecto
└── requirements.txt     # Dependencias del proyecto
```

## Herramientas utilizadas
- **Lenguajes**: Python, R
- **Librerías**: pandas, scikit-learn, matplotlib, seaborn, Plotly, TensorFlow/Keras
- **Big Data**: Apache Spark, Hadoop
- **Visualización**: Power BI, Tableau, Plotly Dash

## Instalación
1. Clonar el repositorio:
```
git clone https://github.com/tuusuario/whale-migration-predictor.git
```
2. Crear entorno virtual e instalar dependencias:
```
cd whale-migration-predictor
python -m venv venv
source venv/bin/activate   # En Linux/Mac
venv\Scripts ctivate      # En Windows
pip install -r requirements.txt
```

## Uso
- Ejecutar notebooks para análisis exploratorio y modelado.
- Scripts en `src/` para limpieza, entrenamiento y visualización.

## Licencia
Este proyecto se distribuye bajo la licencia MIT.
