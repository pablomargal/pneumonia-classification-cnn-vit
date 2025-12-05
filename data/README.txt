================================================================================
INSTRUCCIONES DE DESCARGA Y CONFIGURACIÓN DEL DATASET
================================================================================

Este repositorio NO contiene las imágenes médicas debido a las limitaciones de
almacenamiento de GitHub (el dataset pesa >1GB).

Para reproducir los resultados y ejecutar los notebooks, debes descargar el
dataset original y colocarlo en esta carpeta siguiendo estas instrucciones.

--------------------------------------------------------------------------------
1. FUENTE DEL DATASET
--------------------------------------------------------------------------------
Dataset: Chest X-Ray Images (Pneumonia)
Autor:   Paul Mooney / Guangzhou Women and Children’s Medical Center
URL:     https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

--------------------------------------------------------------------------------
2. INSTRUCCIONES DE INSTALACIÓN
--------------------------------------------------------------------------------
1. Accede a la URL de Kaggle proporcionada arriba.
2. Descarga el archivo `archive.zip`.
3. Descomprime el contenido DENTRO de esta carpeta `data/`.

--------------------------------------------------------------------------------
3. ESTRUCTURA DE CARPETAS REQUERIDA
--------------------------------------------------------------------------------
Para que el código funcione sin modificaciones, la estructura de archivos
debe quedar exactamente así dentro de la carpeta `data/`:

data/
│
├── train/
│   ├── NORMAL/
│   │   ├── IM-0115-0001.jpeg
│   │   └── ...
│   └── PNEUMONIA/
│       ├── person1000_bacteria_2931.jpeg
│       └── ...
│
├── test/
│   ├── NORMAL/
│   └── PNEUMONIA/
│
└── val/
    ├── NORMAL/
    └── PNEUMONIA/

--------------------------------------------------------------------------------
NOTAS IMPORTANTES
--------------------------------------------------------------------------------
* El archivo `.gitkeep` en este directorio sirve únicamente para mantener la
  estructura de carpetas en el repositorio de Git.
* Todas las imágenes (`.jpeg`, `.png`) han sido ignoradas en el `.gitignore`
  para evitar subidas accidentales al repositorio.