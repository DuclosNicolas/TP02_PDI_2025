TP02 - Procesamiento de Imágenes
Estructura Requerida
Para ejecutar correctamente los scripts, organizar los archivos de la siguiente manera:
proyecto/
├── TP02-Problema1.py
├── TP02-Problema2.py
├── placa.png                  # REQUERIDO para Problema 1
├── Resistencias/              # REQUERIDO para Problema 2
│   ├── R1_001.jpg
│   ├── R2_002.png
│   └── ...
└── README.md

Ejecución
Problema 1 - Análisis PCB
bashpython TP02-Problema1.py
Requiere: placa.png en el mismo directorio
Problema 2 - Procesamiento Resistencias
bashpython TP02-Problema2.py
Requiere: Carpeta Resistencias/ con imágenes formato R*_*.*
Notas

Problema 1: Necesita placa.png para detectar componentes
Problema 2: Necesita carpeta Resistencias/ con imágenes de resistencias
Los resultados del Problema 2 se guardan en Resistencias_output/ (se crea automáticamente)
