
## Requisitos técnicos

- Uso de una estructura de datos eficiente: cola de prioridad (heap).
- Validación de entradas (nombre no vacío, prioridad válida).
- Persistencia de datos mediante archivo JSON.
- Cálculo automático de si una tarea puede ejecutarse (todas sus dependencias completadas).

## Estructuras y librerías utilizadas

- `heapq`: para implementar la cola de prioridad.
- `datetime`: para manejar fechas de vencimiento.
- `json`: para guardar y leer las tareas desde archivo.
- `set`: para gestionar tareas completadas de forma eficiente.

## Instrucciones de uso

1. Asegúrate de tener Python 3 instalado.
2. Ejecuta el script con el siguiente comando:
3. Usa el menú que aparece para interactuar con el sistema.

## Archivos del proyecto

- `gestor_tareas.py`: código fuente del programa.
- `tareas.json`: archivo donde se guardan las tareas automáticamente.
- `README.md`: este archivo con la documentación.
- `analisis_eficiencia.pdf`: análisis teórico de eficiencia del código.

