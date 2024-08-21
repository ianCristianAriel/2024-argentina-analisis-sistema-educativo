## Estructura de Directorios y Archivos Resultantes

    Analisis_sistema_educativo_Argentina/
    │
    ├── data/                          # Datasets
    │   ├── bronze/                    # Datos brutos
    │   ├── silver/                    # Datos limpios y transformados para ML
    │   └── gold/                      # Datos listos para visualización de datos
    │
    ├── notebooks_and_scripts/         # Cuadernos y scripts en Python
    │   ├── 1_comprension_preparacion_datos/
    │   │   ├── 1_a_data_clean.ipynb   # Limpieza de datos
    │   │   ├── 1_b_transform.ipynb    # Transformación de datos
    │   │   └── 1_c_eda.ipynb          # Análisis exploratorio de datos
    │   ├── 2_modelado/                
    │   │   └── 2_b_nlp.ipynb          # Procesamiento de Lenguaje Natural (PLN)
    │   └── 3_data_viz/
    │       ├── 3_a_data_viz.ipynb     # Visualización de datos
    │       └── 3_b_tableau_file       # Archivo de Tableau
    │
    ├── .gitignore                     # Archivos a ignorar por Git
    ├── LICENSE.md                     # Licencia del proyecto
    ├── README.md                      # Documentación del proyecto
    └── requirements.txt               # Dependencias del proyecto

## Tecnologías Utilizadas
- Python
  - Bibliotecas para análisis de datos:
    - NumPy
    - pandas
    - missingno
  -	Bibliotecas para visualización de datos:
    -	Matplotlib
    -	Seaborn
  -	Bibliotecas para aprendizaje automático:
    -	scikit-learn
  -	Bibliotecas para Procesamiento de Lenguaje Natural (PLN):
    -	Keras
    -	spaCy

-	Tableau para la visualización avanzada de datos.

## Instalación de Paquetes
Para instalar las dependencias necesarias, ejecuta el siguiente comando:
```bash
pip3 install -r requerimientos.txt
```
## Estado del Proyecto
- **En proceso**