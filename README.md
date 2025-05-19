# Optimización TSP con TSPLIB

Este repositorio contiene implementaciones y comparaciones de diferentes algoritmos para resolver el Problema del Viajante (TSP) utilizando instancias de TSPLIB. El archivo principal es un Jupyter Notebook llamado **Codigos con TSPLIB.ipynb**, donde se encuentran todos los experimentos y ejemplos.

## Estructura del repositorio

- **Codigos con TSPLIB.ipynb**: Notebook principal con todos los códigos, explicaciones y visualizaciones de los algoritmos aplicados al TSP.
- **berlin52.tsp**: Archivo de instancia de TSPLIB utilizado en los ejemplos.
- **iter_solver.py** y **utility.py**: Archivos Python con funciones auxiliares y clases utilizadas en algunas celdas del notebook.

## Requisitos

- Python 3.8+
- Jupyter Notebook
- Paquetes:
  - tsplib95
  - numpy
  - matplotlib
  - python-tsp
  - scipy
  - tsp_solver2

Puedes instalar los paquetes necesarios ejecutando:

```bash
pip install tsplib95 numpy matplotlib python-tsp scipy tsp_solver2
```

## Uso

1. Abre el archivo `Codigos con TSPLIB.ipynb` en Jupyter Notebook o VS Code.
2. Ejecuta las celdas en orden. Cada sección del notebook corresponde a un enfoque diferente para resolver el TSP, incluyendo:
   - Uso de librerías externas (como `tsp_solver2`, `python-tsp`)
   - Implementaciones propias y de otros repositorios de GitHub
   - Visualización de rutas y análisis de resultados
3. Los archivos `iter_solver.py` y `utility.py` deben estar en el mismo directorio para que las celdas que los usan funcionen correctamente.

## Notas

- Algunas celdas del notebook pueden no ejecutarse correctamente cuando se utilizan los 52 nodos completos del archivo `.tsp` debido a limitaciones de memoria o tiempos de cómputo excesivos. Se recomienda probar con un menor número de nodos para ciertos algoritmos, especialmente los de fuerza bruta o ramificación y poda.
- El notebook incluye referencias a los repositorios de GitHub de donde se tomaron o adaptaron algunos algoritmos.
- Se recomienda revisar los comentarios y descripciones en cada celda para entender el funcionamiento de cada método.

## Créditos

- Instancias de TSPLIB: http://comopt.ifi.uni-heidelberg.de/software/TSPLIB95/
- Algoritmos y librerías: ver referencias en el notebook.

---

Entrega para la materia de Optimización - Problema del Viajante (TSP)
