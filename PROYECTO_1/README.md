# Proyecto 1
# Análisis de señales ECG y detección de arritmias

### Allisson Julieth Rojas Niebles
### Fabio Velez Osorio

A continuación se describen los pasos principales del flujo de trabajo y cómo utilizar los datos en este proyecto.

## Descripción del Proyecto

Se ha creado un conjunto de datos filtrado llamado `diagnosticfiltered` que contiene los datos relevantes despues de hacer un filtrado de los datos para formar un subconjunto de interes.

## Carga de Archivos Comprimidos de las señales

Para optimizar el tiempo de carga y facilitar el procesamiento, se ha decidido almacenar los archivos de datos de las arritmias en formato Parquet, que es un formato eficiente para almacenar y leer grandes volúmenes de datos. Las señales de las arritmias comprimidas en formato Parquet están disponibles en la ruta:

PROYECTO_1/
│
├── data/
│   ├── Diagnostics.xlsx
│   ├── Diagnosticsfiltered.xlsx              
│   ├── ECGDataDenoised.zip           
│   └── processed/                    
│       ├── parquet/        # Aqui estan las arritmias por carpeta
│      
│
└── Proyecto1_EKG.ipynb                        

