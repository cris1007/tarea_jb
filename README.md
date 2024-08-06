# tarea_jb

El presente proyecto presenta las tareas del curso Automatización de Pruebas Rest Api - JB

### Grupo 2:

- PALOMARES PAZ, SERGIO ANDRES
- AGAPITO GONZALES, VICTOR HUGO
- CHAMBERGO CONDEMARIN, CRISTIAN IVAN

#### Tarea 1
Usando como base la colección de peticiones creada en el taller de la herramienta Postman, realizar las verificaciones a los escenarios de error de cada uno de los métodos (POST,GET,PUT,PATCH,DELETE) elaborado

```sh
newman run producto_api.json --environment producto_env.json -d data.csv --folder "Sad Path" -r 'cli,json,htmlextra'.
```